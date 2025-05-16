# 🚀 Hackathon Datas 2025

---

## 🧱 Estrutura de Branches

- `main`: versão estável e pronta para produção
- `developer`: branch de integração contínua (desenvolvimento ativo)
- `feature/*`: branches para desenvolvimento de funcionalidades específicas

---

## 👨‍💻 Como Contribuir

### 1. Faça o clone do repositório

```bash
git clone  https://github.com/oliveirakay/hackathon-datas-2025
cd hackathon-datas-2025
```


### 2. Crie uma branch de feature a partir da dev
```bash

# Vá para a branch de desenvolvimento
git checkout developer

# Atualize com as últimas mudanças
git pull origin developer

# Crie uma nova branch de feature
git checkout -b feature/nome-da-sua-feature
```

Exemplo:

```bash
git checkout -b feature/user-authentication
```
### 3. Faça alterações e commits
```bash
git add .
git commit -m "feat: EDA - base do SISU"
```
### 4. Suba sua branch para o repositório remoto
```bash
git push origin feature/nome-da-sua-feature
```
### 5. Crie um Pull Request

Acesse o repositório no GitHub

Vá em "Pull Requests" e clique em "New Pull Request"

Compare a sua branch feature/* com a developer

Descreva claramente o que foi desenvolvido

Aguarde a revisão

### 📌 Boas Práticas

Use nomes de branch descritivos, como feature/login-page

Commits padronizados:

feat: nova funcionalidade

fix: correção de bug

refactor: refatoração sem mudança de funcionalidade

docs: alterações na documentação

chore: tarefas de manutenção

Mantenha a branch dev atualizada antes de criar novas features

Escreva código limpo e comentado

### 👥 Time
Cake - @oliveirakay

Bruno Gallani - @githubuser

Ruh - @githubuser
