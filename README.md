# projeto-1
Aprendendo github

# Comandos terminal/git

ls = para ver arquivos no diretório

cd [nome da pasta] = para entrar em pastas

touch = cria arquivos, tem que ser levado em conta o espaçamento em - ou _ .tipo do arquivo

rm [nome]= digita-se rm [nome do arquivo] para deletar ele do diretório

cd ..= é usado para voltar para o diretório anterior

clear = limpa o terminal

mkdir [nome] = Cria um diretório

nano [nome do arquivo] = abre um arquivo e é possivel editar ele

cat [nome do arquivoo] = exibe o conteúdo do arquivo sem execulado

mv [nome da pasta] = renomeia a pasta

git init= para criar um repositório git

ls -a = exibe arquivos ocultos

cd ../[nome da pasta] = para sair de uma e entrar em outra

git status = para saber quais arquivos estão em cada estágio

git add = para adicionar os arquivos não adicionados ao estágio de commit

git rm--cached [nome do arquivo] = para tirar ele do estágio de commit

git add . = adiciona todos os arquivos para o proximo estagio

git commit -m= para commitar e escrever uma mensagem

git log = para ver o log de modificações e oque os usuarios commitaram

git log --oneline = para visualizar os commits em uma forma condensada em 1 linha por id de usuario

Junções de comandos, usa-se && E comercial 2 vezes Ex. git add . && git commit -m "Mensagem" = aqui iremos usar o git add . e logo após sua execução, já será comittado com a mensagem

git checkout= para voltar a linha do passado no commit específico

git checkout [master/main] = volta para a linha presente

git revert = para reverter um commit feito

git reset = para resetar de um certo commit porém não limpa todo o histórico do futuro

git reset --hard = para deletar o histórico do futuro e ficar no commit solicitado

normalmente nos projetos tem o arquivo .env e esse arquivo tem informações confidenciais, então criamos uma pasta .gitignore e dentro dela colocamos o nome dos arquivos a serem ignorados no git status por exemplo .env

git branch = visualiza todos os branchs o * indica em qual branch você está

git branch [nome] = cria uma branch

git checkout [nome da branch] = para trocar de branch

git branch -D [nome branch] = para deletar

digite git merge [nome da branch] estando na branch de destino para copiar os arquivos da branch [nome da branch]

git push [chave ssh do repositório] [branch main/master]

git remote add [nome] [endereço ssh]

git remote -v = para visualizar as palavras lincadas a endereços

git clone [endereço ssh] [nome do projeto]

rm -rf [nome da pasta] = deleta uma pasta mesmo que tenha coisas dentro

git pull origin main - para receber as atualizaçẽs do repositório

git checkout -b [nome do branch] = cria o branch e troca para esse branch

git clone [endereço ssh] [novo nome opcional]
