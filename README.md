# Studio Aura — Landing Page

Landing page estática para o Studio Aura, com visual escuro, acabamento dourado e vídeo de ambientação.

## Arquivos principais

- `landing-aura.html` — página principal do projeto
- `assets/` — vídeos, imagens e demais recursos usados pela página

## Destaques

- hero com vídeo de fundo e sobreposição escura
- botões com hover dourado e borda realçada
- seção de processo, portfólio, sobre, depoimentos e contato
- formulário com envio via `mailto:` e link para WhatsApp
- layout responsivo para desktop e mobile
- CSS e JavaScript inline, sem build

## Pré-requisitos

Basta um navegador moderno. Para visualizar localmente, você pode usar um servidor HTTP simples.

### Visualização local

No Windows, abra um terminal no diretório do projeto e execute:

```bash
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000/landing-aura.html
```

Se quiser usar a página como homepage sem precisar digitar o nome do arquivo, renomeie `landing-aura.html` para `index.html`.

## Deploy no GitHub Pages

### Opção 1 — mantendo `landing-aura.html`

1. Crie um repositório no GitHub e envie todo o conteúdo do projeto.
2. No repositório, vá em **Settings > Pages**.
3. Em **Source**, selecione a branch `main` (ou `master`) e a pasta `/ (root)`.
4. Salve.
5. Acesse:

```text
https://<seu-usuario>.github.io/<nome-do-repositorio>/landing-aura.html
```

### Opção 2 — usar como página principal (`index.html`)

1. Renomeie `landing-aura.html` para `index.html`.
2. Envie as mudanças para o GitHub.
3. Habilite o GitHub Pages na branch `main` (ou `master`) e pasta `/ (root)`.
4. Depois acesse:

```text
https://<seu-usuario>.github.io/<nome-do-repositorio>/
```

## Observações

- Não é necessário instalar dependências.
- Mantenha a pasta `assets/` no mesmo nível de `landing-aura.html`/`index.html`.
- Se o vídeo não carregar, verifique se os arquivos `assets/interior-dark-video.mp4` e `assets/video-camadas.mp4` estão presentes.
