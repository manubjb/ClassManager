# ClassManager

## Etapas para quando começar a trabalhar:

### Entrar no diretório do projeto pelo cmd
```bash
cd ~/ClassManager
git checkout main
git pull origin main
git checkout dev-Emanuelly
git merge main
```

### Vá para a branch principal##
```bash
git checkout main
```

### Pegue as atualizações do servidor remoto
```bash
git pull origin main
```

### Vá para sua branch de trabalho
```bash
git checkout dev-Emanuelly
```

### Atualize sua branch com as mudanças da main
```bash
git merge main
```

### Depois de terminar de trabalhar
##Veja os arquivos que foram modificados
```bash
git status
```

### Adicione todos os arquivos modificados
```bash
git add .
```
### Faça o commit com uma mensagem descritiva
```bash
git commit -m "feat: adiciona botão para salvar turma"
```

### Verifique se sua branch está atualizada com o servidor
```bash
git fetch origin
```

### Se houver mudanças, faça:
```bash
git checkout main
git pull origin main
git checkout dev-Emanuelly
git merge main
```

### Se houver conflitos, resolva no código, depois:
```bash
git add .
git commit
```
### Envie suas mudanças para o GitHub
```bash
git push origin dev-Emanuelly
```
#### Obs: Se for o primeiro push dessa branch, use:
```bash
git push --set-upstream origin dev-Emanuelly
```
Fim

#### Comandos extras
Ver em qual branch você está e para onde ela aponta
```bash
git branch -vv
```
##### Ver todas as branches locais e remotas
```bash
git branch -a
```

##### Ver um histórico visual simplificado
```bash
git log --oneline --graph --all
```
