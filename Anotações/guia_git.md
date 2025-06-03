# 💻 Guia de Git para Colaboração

## 🌳 Branches
- `main`: versão final/testada
- `dev`: desenvolvimento ativo
- `feature/nome-da-feature`: para cada funcionalidade nova

## 🔧 Comandos práticos
```bash
# Criar nova branch
$ git checkout -b feature/login

# Trabalhar normalmente
$ git add .
$ git commit -m "add login funcionalidade"
$ git push origin feature/login