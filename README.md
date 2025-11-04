# Projeto git/Github
### Aprendendo como trabalhar com repositórios remotos

- Depois de configurar todo o VS code conectado com o Github
- Abri minha pasta local no VS code

- Iniciando o repositorio git
```bash
git init
```

- Criei na minha conta no github um respositório com o nome working_git_github e copiei a ULR do repositório.
```bash
https://github.com/icaroalmeidas/working_git_github
```

- Conectando a pasta local ao respositório remoto
```bash
git remote add origin https://github.com/icaroalmeidas/working_git_github
```

- Envia o código da sua branch "main" para o remoto "origin"
```bach
git push -u origin main
```

- Adiconando mudanças feitas no README.md
```bach
git add README.md
```

- Realizando o commit
```bach
git commit - m "Conectando local-remoto"
```

- Criando nova feature onde iremos fazer testes e apenas depois de aprovadas levaremos para a branch main
```bach
git checkout -b feature/desenvolvendo-git
```
- Enviando a nova feature para o remoto
```bash
git puch --set-upstream origin feature/desenvolvendo-git
```
### As novas alterações forma feitas apenas na branch desenvolvendo-git. Digamos que já foram todas testadas e queremos levar para a branch main.

