# Gerador de currículos dinâmico

## 🔧 Stack utilizada:

<div align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,nodejs,git&theme=dark" />
</div>

## 📁 Estrutura do Projeto

```text
gerador-curriculo
 ┣ public
 ┃ ┗ index.html              # Estrutura HTML da aplicação
 ┣ src
 ┃ ┣ data
 ┃ ┃ ┗ baseProfile.js      # Dados fixos do currículo base (experiências, formação, contatos)
 ┃ ┣ core
 ┃ ┃ ┣ resumeBuilder.js    # Mescla o perfil base com os ajustes da vaga (título, stack)
 ┃ ┃ ┗ storage.js          # Persistência local (localStorage / exportação JSON)
 ┃ ┣ services
 ┃ ┃ ┗ aiAdapter.js        # [Futuro] Integração com IA para adaptar o currículo à vaga
 ┃ ┣ ui
 ┃ ┃ ┣ formHandler.js      # Captura dados do formulário e edições por vaga
 ┃ ┃ ┗ previewRenderer.js  # Renderiza o template visual do currículo na tela
 ┃ ┣ utils
 ┃ ┃ ┗ exportPdf.js        # Exportação e impressão limpa (@media print)
 ┃ ┣ styles
 ┃ ┃ ┣ main.css            # Estilos da interface da aplicação
 ┃ ┃ ┗ resume-print.css    # Estilos exclusivos do layout do currículo e impressão PDF
 ┃ ┗ main.js               # Ponto de entrada que inicializa e conecta os módulos
 ┣ package.json
 ┗ README.md               # Documentação do repositório
```
