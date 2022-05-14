<!--
ESTUDO SOBRE GIT E GITHUB

GIT: Controle de versão e histórico (Sistemas parecidos “SVN Subversion” e “CSV”).

ESTRUTURA GIT - BRANCH: Master (Código) > Develop (Clone do Master) > Feature1 (Acréscimo1) > Feature2 (Acréscimo2) > Feature3 (Acrescimo3) > …

CONCLUSÃO DAS BRANCH:	1º Merge (Mesclar as branch)
					2º Commit (brach concluido)
					3º Push (Enviar as branch para o Master)
					*4º Pull Request (Pedir para incluir a branch num repositório)

COMANDOS MAIS COMUNS:	CTRL+J (Entra no terminal VSCode)
					ls (Lista conteudo da pasta)
					cd ../ (Sai do diretório)
					cd NomePasta (Entra)
					git status (Mostra como esta o arquivo)
					git checkout -b Nomebranch (Verifica e cria branch)
					git add . (Prepara todos os arquivos alterados para o commit)
					git commit -m “Comentário” (Registra as alterações)
					git push (Envia para o repositório)
					git pull (Atualiza o arquivo principal com o alterado) 						https://woliveiras.com.br/posts/comandos-mais-utilizados-no-git/

GITHUB: Sistema de gestão de projetos como portfólio, é um repositório, podendo ser compartilhado os projetos com outros desenvolvedores.

EXEMPLO DE NOVO PROJETO: 
1º Criar um novo projeto no site da GITHUB;
2º Criar uma pasta do projeto no computador;
3º Clicar com o BD do mouse dentro da pasta do projeto e clicar em "Git Bash Here", abrirá o prompt do GIT;
4º Digite os seguintes comandos:
git init (Iniciar o serviço);
git add . Ou git add “nomearquivo.extencao” (Adiciona os aquivos no controle de versão);
git commit -m "Boa Pratica de Comentar" (Cria a uma nova versao e se for a primeira vez deve configurar com email e usuario do GITHUB com o comando GIT CONFIG);
git branch -M main (Add no clone do principal);
git remote add origin https://github.com/usuario-github/nome-projeto.git (Define o caminho remoto que será enviado os arquivos);
git push -u origin main (Envia os arquivos para o GITHUB, se for a primeira vez tera que autenticar).

RESUMO DE COMANDOS DO GIT:
git init
git add .
git commit -m “”
git branch -M main
git remote add origin https://… (SOMENTE NO PRIMEIRO COMMIT)
git push -u origin main
-->