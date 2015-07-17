#Curso de git oferecido pelo code.education

Este repositório é destinado ao curso de **git** e **github** oferecido pela **code.education**.

Pretendo, através deste repositório, demonstrar os passos básicos para enviar um projeto para o repositório github.

> 1. Inicializar git.
```
git init
```

> 2. Selecionar(stagged) arquivos para commit.
```
git add nomedoarquivo
```

> 3. Registar etapa do projeto, ou seja, commit.
```
git commit -m "descrição das tarefas realizadas"
```

> 4. Acessar o site [Github](https://github.com) e efetuar seu cadastro caso não tenha.

> 5. Criar um novo repositório através do botão *New Repository* na interface do github ou através deste [link](https://github.com/new).

> 6. Enviar seu repositório local para o repositório do github através dos seguintes comandos.
```
git remote add origin https://github.com/nomedeusuario/nomedorepositorio
git push origin master
```
*Obs.: não se esqueca de substituir nomedeusuario e nomedorepositorio*

Pronto!! Agora você já tem um repositório git local e remoto através github.