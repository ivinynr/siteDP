

# Comandos



## 🚀 Como subir um projeto local para o GitHub

1. Inicie o Git na pasta do seu projeto:

```bash
git init
git add .
git commit -m "Primeiro commit do projeto"
```
2. Crie pasta no github

```bash
git remote add origin https://github.com/seu-usuario/seu-repositorio.git
git branch -M main
git push -u origin main
```
## 🚀Como clonar 

1. Entra no cd da pasta
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git

```
2. Abra vscode

```bash
code .
```
## 🚀Rodar aplicação

1. Ver o site rodando localmente
```bash
npm run dev
```
2. Gerar versão final do site
```bash
npm run build
```
