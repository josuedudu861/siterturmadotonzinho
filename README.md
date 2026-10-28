# Turma do Tonzinho

Site estático pronto para GitHub Pages. Não precisa de instalação, npm, banco de dados ou build.

## Publicar

1. Extraia o ZIP no computador.
2. Crie um repositório no GitHub, por exemplo `turma-do-tonzinho`.
3. Envie o CONTEÚDO desta pasta para a raiz do repositório: `index.html`, `apresentacoes.html`, arquivos CSS/JS e a pasta `assets`. Não envie apenas o ZIP.
4. Confirme o envio na branch `main`.
5. Em Settings → Pages → Build and deployment, escolha Source: Deploy from a branch, branch `main` e pasta `/ (root)`. Clique em Save.
6. Aguarde a publicação e abra a URL exibida pelo GitHub Pages.

Guia oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Conteúdo

- Página inicial, personagens separados (incluindo Kaká), apresentações e Instagram.
- Imagens, quatro vídeos de eventos, capas e vinheta de abertura em `assets/`.
- Formulário que abre WhatsApp para +55 61 99206-1190 com mensagem preenchida. A pessoa confirma o envio no WhatsApp.
- Caminhos relativos compatíveis com repositórios de projeto no GitHub Pages.

## Serviços externos

Instagram é incorporado por links/iframes: os arquivos dos vídeos do Instagram não estão neste pacote e dependem da plataforma, que pode pedir login ou bloquear a incorporação. Google Fonts carrega as fontes pela internet. Os quatro vídeos enviados e a vinheta estão incluídos localmente.

## Pré-visualizar

Na pasta extraída, execute `python3 -m http.server 8000` e abra http://localhost:8000 .

## Editar

Textos e seções: `index.html` e `apresentacoes.html`. Aparência: arquivos `.css`. WhatsApp: `script.js` (número em formato internacional, sem espaços).

Este pacote não inclui credenciais, histórico Git ou configurações internas do serviço de hospedagem anterior.
