SOBRE ESTE DIRETÓRIO
====================

## Aqui constam arquivos de teste que criei durante o curso online de Git da escola Code Education => https://code.education

### Durante o curso aprendi:
1. A instalar o git
2. Configurar o git com os meus dados de acesso e prefências, usando o comando git config --global user.[name, email] e git config --global core.editor nome-editor (para escolher o editor padão para trabalhar com o git)
3. Verificar as minhas configurações no git, com o comando git config --list
4. Aprendi a criar repositório git e a iniciar o uso do repositório com o comando git init
5. Alernei o uso de repositórios git utilizando o comando cd /diretorio/
6. Criar o arquivo .gitignore, para definir arquivos e diretórios que não quero que o git versione
7. Os três estados de um arquivo no git: 1 commited, 2 modificado e 3 preparado
8. Qual é o fluxo básico de trabalho do Git: 
   1. Você modifica arquivos no seu diretório
   2. Você prepara os arquivos com o comando git add nome-arquivo
   3. Você faz commit e armazena as imagens(snapshots) no diretório Git
9. Aprendi a preparar os arquivos para commit, utilizando o comando git add nome-do-arquivo
10. Fiz commit utilizando o comando git commit -m "Mensagem descritiva do que foi realizado no arquivo"
11. Fiz commit pulando a área de stage, utilizando o comando git commit -a -m "Mensagem descritiva do que foi realizado no arquivo"
12. Alterei a mensagem de commit utilizando o comando git commit --amend
Esse comando pega a área stage e a usa para realizar o commit. 
Se você não fez nenhuma alteração desde o último commit (por exemplo, se você executar o comando imediatamente depois do commit anterior), então sua imagem dos arquivos irá ser exatamente a mesma, e tudo o que você alterará será a mensagem do commit.
13. Aprendi a ver o estado dos arquivos(commited, modificado, preparado) com o comando git status
14. Verifiquei os arquivos que modifiquei e ainda não estão preparados para commit, para isso, utilizei o comando git diff
15. Verifiquei os logs de commits, utilizando os comandos git log (Para ver todo o histórico de commits executados no projeto), git log -p -2 (Para ver o log dos dois últimos commits), git log --stat (Para ver estatísticas abreviadas para cada commit), git log --pretty=oneline (Mostra cada commit em uma única linha), git log --pretty=format:"%h - %an, %ar : %s" (Formatando para trazer no log os seguintes dados => h: abreviação do hash do commit, an: nome do autor do commit, ar: data do commit e s: Mensagem gravada no commit) 
16. Criei branchs com o comando git checkout -b nome-do-branch
17. A identificar em qual branch estou trabalhando com o comando git branch
18. Alternar(trocar de um branch para outro) com o comando git checkout nome-do-branch
19. Excluir branchs locais não utilizados com o comando git branch -D nome-do-branch
20. Excluir branchs do servidor remoto não utilizados com o comando git push origin :nome-do-branch
21. Fiz merge de branchs com o comando git merge nome-do-branch
22. Configurei o GITHUB. Gerei uma chave privada utilizando o comando ssh-keygen, adicionei essa chave na minha conta do GITHUB para não ter que ficar informando usuário e senha sempre que precisar interagir com o servidor remoto.
23. Fiz push de branchs do servidor local para o GITHUB, utizando o comando git push origin nome-dobranch      
24. Clonei servidor remoto para o local com o comando git clone url-do-repositorio nome-do-repositorio-local - Sendo opcional o item nome-do-repositorio-local
25. Listei todos os branchs locais e remotos para ver se todos os branchs locais foram criado remoto. Para isso, utilizei o comando git branch -a
26. Após realizar um clone de um diretório remoto, aprendi a veriricar se todos os arquivos foram baixados corretamente, para isso, utilizei o comando git pull
27. Peguei atualizações dos branchs do servidor remoto utilizando o comando git pull origin nome-do-branch-remoto
 



