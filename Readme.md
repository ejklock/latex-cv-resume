# Latex CV/Resume with Github Actions

## Description

This repository contains a example for build CV/Resume in Latex using Github Actions. Every you update the the tex file, a Github Action is triggered to generate a new version of your resume. You can pass multiple tex files to the Github Action step:"Compile LaTeX document" and the Github Action will take care of the rest. The generated PDFs are available to download on your [GitHub repository] on the [Releases page]

## Sensitive information

You can pass your sensitive information to the Github Action step:"Compile LaTeX document" env variables, like: "MY_EMAIL" and "MY_PHONE_NUMBER" and others as you wish. To use in Latex document, update the tex file adding as follow:

```latex
     \getenv{YOUR_VARIABLE_NAME}}
```

## Credits

1 - The CV template was created by Omar Roldan available on [Overleaf](https://www.overleaf.com/latex/templates/cv-developer/rdycxzvvnvcc)

2 - This project uses the [latex-action](https://github.com/xu-cheng/latex-action) github action for build the CV/Resume

3 - Latex env vars solution available at <https://tex.stackexchange.com/a/62032>

4 - Built by [Evaldo Klock](https://github.com/ejklock)
