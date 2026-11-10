# reportslatam

Aplicação estática de qualidade LATAM. Abra `index.html` para gerar reports ou `qualidade.html` para consultar o painel.

## Publicar no GitHub Pages

O workflow em `.github/workflows/pages.yml` publica os arquivos da raiz quando há push para `main`.

1. No GitHub, abra **Settings > Pages** e selecione **GitHub Actions** como fonte de publicação.
2. Envie as alterações para a branch `main` ou execute **Publish GitHub Pages** manualmente na aba **Actions**.
3. Consulte o link publicado no resumo da execução do workflow.

Bootstrap, Bootstrap Icons, Chart.js e o logo LATAM são carregados de CDNs; a publicação e o uso visual desses recursos dependem de acesso à internet.