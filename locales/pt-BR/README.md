# Ajude a traduzir o ARAS

[🇦🇪 العربية](../ar/README.md) • [🇩🇪 Deutsch](../de/README.md) • [🇺🇸 English](../../README.md) • [🇪🇸 Español](../es/README.md) • [🇵🇭 Filipino](../fil/README.md) • [🇫🇷 Français](../fr/README.md)  
[🇮🇳 हिन्दी](../hi/README.md) • [🇮🇩 Bahasa Indonesia](../id/README.md) • [🇮🇹 Italiano](../it/README.md) • [🇰🇭 ខ្មែរ](../km/README.md) • [🇰🇷 한국어](../ko/README.md) • [🇲🇾 Bahasa Melayu](../ms/README.md)  
[🇳🇱 Nederlands](../nl/README.md) • [🇵🇱 Polski](../pl/README.md) • **[🇧🇷 Português (Brasil)](../pt-BR/README.md)** • [🇷🇴 Română](../ro/README.md) • [🇷🇺 Русский](../ru/README.md) • [🇱🇰 සිංහල](../si/README.md)  
[🇹🇷 Türkçe](../tr/README.md) • [🇺🇦 Українська](../uk/README.md) • [🇵🇰 اردو](../ur/README.md) • [🇻🇳 Tiếng Việt](../vi/README.md) • [🇨🇳 简体中文](../zh-Hans/README.md)  

---

O ARAS é traduzido por pessoas da nossa comunidade. Se você fala outro idioma, pode ajudar a fazer com que seus menus, botões e mensagens pareçam naturais para mais pessoas.

Você não precisa de experiência em programação, softwares especiais ou acesso ao código-fonte do ARAS. Tudo pode ser feito diretamente no GitHub usando o seu navegador web.

## Como ajudar

- Adicionar um idioma que ainda não esteja listado
- Completar textos que ainda estão em inglês
- Corrigir ortografia ou gramática
- Tornar as frases mais naturais em português
- Melhorar a consistência entre menus e mensagens
- Revisar traduções enviadas por outros colaboradores

Pequenas melhorias são sempre bem-vindas. Você não precisa traduzir tudo de uma vez.

## Editar um idioma existente

1. Encontre seu idioma na lista de arquivos `.json`. Por exemplo, o português do Brasil é `pt-BR.json` e o espanhol é `es.json`.
2. Abra o arquivo e clique no botão com ícone de lápis (**Edit this file**).
3. Altere somente o texto traduzido no lado direito de cada par.
4. Clique em **Preview changes** para conferir suas alterações.
5. Clique em **Propose changes** e abra uma pull request.

```json
"Cancel": "Cancelar"
```

`Cancel` à esquerda é o texto original em inglês. `Cancelar` à direita é a tradução em português. Altere apenas o lado direito.

## Solicitar um novo idioma

Abra uma issue e informe:

- O nome do idioma
- O país ou região, caso haja variações regionais
- O nome do idioma escrito na própria língua
- Se você pode traduzir ou revisar

Um mantenedor criará o arquivo para você começar a traduzir pelo GitHub.

## Dicas importantes de tradução

- Mantenha `ARAS` inalterado. É o nome do produto.
- Geralmente mantenha nomes como Android, macOS, Mac, ProMotion e Adreno inalterados.
- Mantenha siglas técnicas como ADB, QEMU, QCOW2, DPI, FPS e GiB inalteradas.
- Escreva com naturalidade para quem fala português brasileiro. Evite traduções literais duras.
- Mantenha textos de menus e botões curtos e diretos.
- Use o mesmo termo em português para 'dispositivo', 'ajustes', 'armazenamento' e 'atualização'.
- Avisos de exclusão ou restauração de dados devem ser explícitos e sérios.
- Deixe termos incertos em inglês e peça orientação na pull request.
- Traduções automáticas servem apenas como rascunho e exigem revisão humana fluente.
- Nunca insira propagandas, links ou informações pessoais.

Alguns textos contêm marcadores especiais como `%@`, `%ld`, `%s`, `%.1f` ou `\n`. Mantenha-os exatamente como estão. O ARAS os substitui durante a execução por nomes, números ou quebras de linha.

Veja o [guia de estilo de tradução](STYLE_GUIDE.md) para orientações detalhadas.

## Nomes dos arquivos de idioma

As letras no nome do arquivo identificam o idioma:

- `de.json` — Alemão
- `es.json` — Espanhol
- `pt-BR.json` — Português (Brasil)
- `zh-Hans.json` — Chinês simplificado

Em caso de dúvidas, abra uma issue e teremos prazer em ajudar.

## Revisões

Pull requests são avaliadas por mantenedores e pela comunidade para garantir clareza, fluidez e encaixe na interface.

Nosso [Código de Conduta](CODE_OF_CONDUCT.md) se aplica a todas as discussões e revisões.

## [CONTRIBUTING.md](CONTRIBUTING.md)

## Arquivos da comunidade

- `README.md` — Visão geral e primeiros passos
- `CONTRIBUTING.md` — Como contribuir e regras de envio
- `CODE_OF_CONDUCT.md` — Código de conduta da comunidade
- `STYLE_GUIDE.md` — Guia de estilo e terminologia
- `REVIEW_CHECKLIST.md` — Lista de verificação para revisores
- `../../pt-BR.json` — Arquivo de traduções em português do Brasil

## Licença

Os arquivos e documentações de tradução são compartilhados sob a [Licença MIT](../../LICENSE). Ao colaborar, você concorda com esses termos de compartilhamento.
