# SPeARS_site

Landing page do SPeARS, projeto de formatura da Escola Politécnica da USP.
Site estático em português, feito com HTML e CSS, sem dependências ou etapa de build.

## Estrutura

```text
public/
  index.html          Conteúdo da página
  assets/styles.css   Estilos e layout responsivo
.github/workflows/pages.yml   Publicação no GitHub Pages
```

## Visualizar localmente

Na pasta deste repositório:

```powershell
python -m http.server 8000 --directory public
```

Abra http://localhost:8000. Para parar o servidor, pressione Ctrl+C.
Também é possível abrir `public/index.html` diretamente no navegador.

## Publicar no GitHub Pages

1. No GitHub, abra **Settings → Pages** e selecione **GitHub Actions** em **Build and deployment → Source**.
2. Envie os arquivos para `main`. O workflow `Deploy GitHub Pages` publica somente a pasta `public/`.
3. Acompanhe a execução na aba **Actions**. Também é possível executar o workflow manualmente.

Endereço esperado após a primeira publicação: https://pturini.github.io/SPeARS_site/

Este repositório é privado: GitHub Pages exige GitHub Pro ou outro plano elegível para repositórios privados. Com GitHub Free, é necessário tornar o repositório público ou escolher outra hospedagem. A publicação comum no Pages torna o site acessível publicamente mesmo quando o código está em um repositório privado.

Documentação: https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages

## Editar

- Altere textos, equipe e links em `public/index.html`.
- Altere cores, espaçamentos e responsividade em `public/assets/styles.css`.
- Use caminhos relativos para os arquivos locais, pois o site fica sob `/SPeARS_site/`.
- O diagrama da página é ilustrativo. Resultados quantitativos e materiais finais podem ser acrescentados após revisão.
