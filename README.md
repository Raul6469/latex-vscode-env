# latex-vscode-remote-env

A ready-to-go Visual Studio Code environment for writing LaTeX documents

**Works out of the box with Docker or GitHub Codespaces!**

![image](https://github.com/Raul6469/latex-vscode-env/assets/24607388/ef3b2d81-c5e1-4e7b-841a-cb69d777107d)

## Features
- All features from [latex-workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) VS Code extension, including live PDF previews
- Autoformatting with [latexindent](https://github.com/cmhughes/latexindent.pl)
- Linting with [chktex](https://www.nongnu.org/chktex/)

## How to use
First [create your repository from this template](https://github.com/Raul6469/latex-vscode-env/generate), and clone it on your computer.

### Docker
With the [GitHub Codespaces extension installed](https://marketplace.visualstudio.com/items?itemName=GitHub.codespaces), click on the bottom left corner, and select **Reopen in container**

Docker will build the image with the needed dependencies, so it may take a while. But don't worry, this will only be done once (as long as you don't delete the image on your computer of course)

### GitHub Codespaces
You can just click on the green **Use this template** on the top right corner of this repository homepage, and **Open in a codespace**!