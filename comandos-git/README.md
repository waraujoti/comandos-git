Comando         Descrição

git init        Inicia um repositório

git remote add origin https://github.com/usuario/repositorio.git 	Indica a origem do repositório

git status      Lista sua branch atual, os commits atuais e os arquivos modificados

git add         <arquivo> 	Prepara o arquivo para ser adicionado ao próximo commit

git add .       Prepara todos os arquivos modificados para serem adicionados ao próximo commit

git reset       <arquivo> 	Desprepara um arquivo

git reset . 	Desprepara todos os arquivos

git commit -m "Mensagem" 	Cria um commit com todos os arquivos preparados

git checkout -b nome-da-branch 	Cria uma nova branch e da checkout nela

git checkout nome-da-branch 	Da checkout em uma branch

git pull nome-da-branch 	Puxa uma branch local para a branch atual, dando merge em suas mudanças

git pull origin nome-da-branch 	Puxa uma branch na origem para a branch atual, dando merge em suas mudanças
git push nome-da-branch 	Empurra a branch atual para uma branch local, dando merge em suas mudanças
git push origin nome-da-branch 	Empurra a branch atual para uma branch na origem, dando merge em suas mudanças se tiver permissão para isso