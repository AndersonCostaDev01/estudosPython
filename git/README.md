# Estudos sobre git/gitHub

## o que e Git

> Git e uma sistema/ferramenta de versionamento de codigo para programadores, nele podemso manter nosso codigo versionado de forma segura podendo retornar uma ou mais versoes se nessesario, alem de manter tudo organizado e facilitar o trabalho em equipe podendo trabalhar com diversas branches/galhos 

### Principais funcionalidades:

- Rastrear alteraçoes no codigo ao longo do tempo 
- Versionar o codigo assim tendo controle de varias versoes diferentes do codigo (v1, v2, v2.3, .....)
- Reverter mudanças se for nessesario 
- Colaborar em eequipe 
- Fazer *Backup* do codigo (em plataformas na nuvem ou na propria maquina)

### Porque usar git? 
 
- Colaboração em equipe - permite que varios programadores trabalhem no mesmo projeto 
- Backup - Seu codigo sera salvo em dversos locais mitigando a chance de perder o mesmo 
- Versionamento - permite manter guardado versoes antigas do seu codigo de forma muito facil 
- Integrar com plataformas - como GitHub, GitLab, Bitbucket, etc.


### Exemplos de comandos basicos 

```bash
    # Inicializar um repositório Git
    git init

    # Adicionar arquivos ao repositório
    git add .

    # Comitar as alterações
    git commit -m "Primeiro commit"

    # Adicionar um remoto (ex: GitHub)
    git remote add origin https://github.com/usuario/projeto.git

    # Pushar para o repositório remoto
    git push -u origin main

    # Ver histórico de commits
    git log

    # Ver o estado atual
    git status

    # Criar um branch
    git checkout -b feature/new-feature

    # Alterar o branch atual
    git checkout main

    # Juntar branches (merge)
    git merge feature/new-feature

    # Reverter um commit
    git reset --hard HEAD~1

    # Criar um branch a partir de outro
    git checkout -b feature/new-feature main

```

### Exemplo pratico 

comando para clonar um repositorio da plataforma **[gitHub](https://github.com/)**
```bash
    git clone https://github.com/seu-usuario/projeto.git
```

Alterando este repositorio 
```bash
    git add README.md
    git commit -m "Adicionado README"
    git push origin main
```

### Breve resumo 

- Git	Sistema de controle de versões
- Commit	Salva uma versão do código
- Branch	Linha de desenvolvimento separada
- Push	Envio de alterações para o repositório remoto
- Pull Request	Sugestão de merge entre branches
- GitHub	Plataforma para hospedar repositórios Git