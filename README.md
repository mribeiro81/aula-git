SOBRE ESTE DIRETÓRIO
====================

## Aqui constam arquivos de teste que criei durante o curso online de Git da escola Code Education => https://code.education

### Durante o curso aprendi:
1. A instalar o git
2. Configurar o git com os meus dados de acesso e prefências, usando o comando git config --global user.[name, email] e git config --global core.editor nome-editor (para escolher o editor padão para trabalhar com o git)
3. Verificar as minhas configurações no git, com o comando git config --list
4. Aprendi a criar repositório git e a iniciar o uso do repositório com o comando git init
5. Alernei o uso de repositórios git utilizando o comando cd /diretorio/
6. Utilizar o comando ls para listar os arquivos no diretório
7. Criar o arquivo .gitignore, para definir arquivos e diretórios que não quero que o git versione
8. Os três estados de um arquivo no git: 1 commited, 2 modificado e 3 preparado
9. Qual é o fluxo básico de trabalho do Git: 
   1. Você modifica arquivos no seu diretório
   2. Você prepara os arquivos com o comando git add nome-arquivo
   3. Você faz commit e armazena as imagens(snapshots) no diretório Git
11. Aprendi a preparar os arquivos para commit, utilizando o comando git add nome-do-arquivo
12. Fiz commit utilizando o comando git commit -m "Mensagem descritiva do que foi realizado no arquivo"
13. Fiz commit pulando a área de stage, utilizando o comando git commit -a -m "Mensagem descritiva do que foi realizado no arquivo"
14. Alterei a mensagem de commit utilizando o comando git commit --amend
Esse comando pega a área stage e a usa para realizar o commit. 
Se você não fez nenhuma alteração desde o último commit (por exemplo, se você executar o comando imediatamente depois do commit anterior), então sua imagem dos arquivos irá ser exatamente a mesma, e tudo o que você alterará será a mensagem do commit.
15. Aprendi a ver o estado dos arquivos(commited, modificado, preparado) com o comando git status
16. Verifiquei os arquivos que modifiquei e ainda não estão preparados para commit, para isso, utilizei o comando git diff
17. Verifiquei os logs de commits, utilizando os comandos git log (Para ver todo o histórico de commits executados no projeto), git log -p -2 (Para ver o log dos dois últimos commits), git log --stat (Para ver estatísticas abreviadas para cada commit), git log --pretty=oneline (Mostra cada commit em uma única linha), git log --pretty=format:"%h - %an, %ar : %s" (Formatando para trazer no log os seguintes dados => h: abreviação do hash do commit, an: nome do autor do commit, ar: data do commit e s: Mensagem gravada no commit) 
18. Criei branchs com o comando git checkout -b nome-do-branch
19. A identificar em qual branch estou trabalhando com o comando git branch
20. Alternar(trocar de um branch para outro) com o comando git checkout nome-do-branch
21. Excluir branchs locais não utilizados com o comando git branch -D nome-do-branch
20. Excluir branchs do servidor remoto não utilizados com o comando git push origin :nome-do-branch
22. Fiz merge de branchs com o comando git merge nome-do-branch
23. Configurei o GITHUB. Gerei uma chave privada utilizando o comando ssh-keygen, adicionei essa chave na minha conta do GITHUB para não ter que ficar informando usuário e senha sempre que precisar interagir com o servidor remoto.
24. Fiz push de branchs do servidor local para o GITHUB, utizando o comando git push origin nome-dobranch      
25. Clonei servidor remoto para o local com o comando git clone url-do-repositorio nome-do-repositorio-local - Sendo opcional o item nome-do-repositorio-local
26. Listei todos os branchs locais e remotos para ver se todos os branchs locais foram criados remoto. Para isso, utilizei o comando git branch -a
27. Após realizar um clone de um diretório remoto, aprendi a veriricar se todos os arquivos foram baixados corretamente, para isso, utilizei o comando git pull
28. Peguei atualizações dos branchs do servidor remoto utilizando o comando git pull origin nome-do-branch-remoto
29. Criei tag no repositório local utilizando o padrão de versionamento semântico, para isso, utilizei comando git tag 0.1.0 -m "Mensagem explicativa sobre a versão" (0: MAJOR, 1: MINOR, 0: PATCH)
30. Fiz push para enviar para o repositório remoto as tags que criei localmente, para isso, utilizei o comando git push origin master --tags
31. Listei todas as tags que criei no local com o comando git tag -l
32. Exclui no repositório local uma tag que criei por erro de digitação, utilizei o comando git tag -d 0.0.1 (onde 0.0.1 é a tag que eu excluí)
33. Exclui no repositório remoto a tag que exclui localmente (descrita acima). Utilizei o comando git push origin :refs/tags/0.0.1 (onde 0.0.1 é a tag que eu excluí)
34. Fiz atualizações no projeto e gerei a tag da versão 0.1.1, utilizei o comando git tag 0.1.1 -m "Mensagem explicativa sobre a versão" (onde 0.1.1 é o código da versão)
35. Fiz um push da nova tag para o repositório remoto utilizando o comando git push origin master --tags



 



