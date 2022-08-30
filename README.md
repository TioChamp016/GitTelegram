# GitTelegram
Repositório de Aprendizado

GIT = Software Gerenciador de Versões (Version Control System)VCS

GITHUB = Plataforma que nos permite hospedar projetos versionados com o GIT (Hospedagens de Repositórios)

	Início

//baixar o GIT
www.git-scm.com
UNTRACKED -Adição do arquivo-> UNMODIFIED -Edição do arquivo-> MODIFIED -Seleção do arquivo-> STAGED -commit-> COMMITED -Automaticamente depois do commit-> UNMODIFIED...

git init //dentro da pasta que está projetando
// para controlar as versões dos arquivos eles devem entrar mara o modo STAGE
git add // para adicionar o arquivo no STAGE
git commit -m // para registrar a foto do estagio atual e junto criar um comentário
git commit -am // para não precisar fazer add toda vez antes do commit
git log // vizualizar o histórico de alterações
	(q) para encerrar o processo
git checkout (código obtido no histórico) // retoma o arquivo como era
-------------------------------------------------------------------------------

30-08-2019
arquivo de README
	instruções e observações
git clone (https://github.com/TioChamp016/GitTelegram.git) <- link do seu repositório la no git hub
    criar os arquivos pelo VSCode dentro da pasta e gerada após o clone
    após criado é preciso upar ele pro github assim:
    git add . (para adicionar tudo) OU git add (nome do arquivo) //adiciona no stage
    git status //para conferir se foi mesmo adicionado
    git commit -m '' // para subir e comentar na pasta local
    git push // para subir online para o github
    git pull // para upar do github para a pasta local no pc
