- 

## Introdução a Git e GitHub

##### **Entendendo a sua importância:**

- Ferramenta Git: é um software de versionamento( Versões )  de código que nos ajudar a monitorar deferentes versões do nosso código

 Principais coisa que iremos aprender:

- Controle de versão

- Armazenamento em nuvem

- trabalho em equipe 

- melhorar seu codigo

- Reconhecimento

_____________________________________________________________________________________________________

##### **Navegação via command line interface e instalação**

GUI ( Graphical User Interface ) X CLI ( Command line Interface )

O que vamos aprender?
- Mudar de pastas
- Lista as pastas
- Criar pastas/arquivos
- Deletar pastar/arquivos

Terminal Windows
seta pra cima ( ^ ) você navega entre os comnados já utilizados 
-cd ( vai possibilitar que a gente navegue entre as pastas entrando , podemos usar o TAB para completar)
-cd.. ( vai possibilitar voltar das pastas)
-dir ( lista de diretorio que tem no local que a gente está )
-mkdir ( criar uma pasta )
-del  ( apaga um arquivo que está no repositório ) &  rmdir ( apga um repositório )
Ex: rmdir workspace /S /Q
-cls ( limpar o visor )
-echo ( printa o que escrevemos) e se usarmos echo mais uma string > texto.txt podemos criar arquivos nele

_____________________________________________________________________________________________________

##### **Git por baxo dos panos**

- SHA1( Secure Hash Algotithm  - é um conjunto de funções hash criptográficas projetadas pela NSA( agência de Segurança Nacional dos Eua) Encriptação e gera um caracter de 40 digitos

- Objetos Fundamentais:
Blobs(bolhas)
Trees(arvores) (contem as blobs) 
Commits(  

- Sistema distribuido Seguro 

- Chave SSH E Token

_____________________________________________________________________________________________________

##### Primeiros comandos com Git

- ##### git init ( inicia o repositorio no git ) 
- git add ( mover arquivos e começar o versionamentos )
- git commit ( cria commit )

flag para mostrar arquivos ocultos = ls -a

Markdown - forma mas humana de escrever o html 
Todo arquivo markdown temos que colocar no final dele .md
Depois que criamos o arquivo .md, temos que voltar no CLI para poder adicionar esse arquivo no commit
Passos:
$ git add *
$ git commit -m "nome que iremos dar para o commit"

------

##### Ciclo de vida dos arquivos git

git init - Além de criar a pasta " .git/" , cria um **repositório** na pasta

git add "nomeArquivo"

git add * - que pega tudo que foi modificado e adiciona para o staged

mv - move o arquivo entre as pastas

<img src="C:\Users\samuc\AppData\Roaming\Typora\typora-user-images\image-20211022004540031.png" alt="image-20211022004540031" style="zoom:60%;" />



git status - monitora os status dos arquivos:

- Untracked
- Unmodifield
- Modifield
- Staged

Processo: git add . -> git commit -m "msg" -> git push origin master(main)



![image-20211022011511784](C:\Users\samuc\AppData\Roaming\Typora\typora-user-images\image-20211022011511784.png)

"Movemos os arquivos Untracked ,Modifield para staged"



![image-20211022011635150](C:\Users\samuc\AppData\Roaming\Typora\typora-user-images\image-20211022011635150.png)

" Criamos o commit"
Na parte de "mgs" colocamos o que a gente alterou no processo e continuamos / colocar um comentário coerentes e que façam sentido

![image-20211022011926346](C:\Users\samuc\AppData\Roaming\Typora\typora-user-images\image-20211022011926346.png)

"Processo de transição dos arquivos entre os ambientes de desenvolvimento"



Para fazer a vinculação do **repositório remoto** com o **repositório local**, temos que:

- git remote add origin com a **URL** que foi criada quando fizemos o repositório remoto( GitHub)

Após isso usamos o "git push origin master" 

**OBS** : Para podermos salvar novos arquivos em alguma pasta do nosso **repositório remoto** , temos que nos atentar o local que esta as pastas do **diretório local**

D:\Workspace\livro-receitas\receitas

------

##### Resolvendo conflitos GitHub

git clone - clona o seu repositório para fazer alguma contrinuição 

git pull - pucha o que tem lá no remoto para a sua maquina


- ###### baixando um repositório do github para o repositório local:

1. ir no repositória que queremos e ir Code > 
2. clone with https ( copiar o link URL) >
3. Vamos usar o diretório base ( Workspace), abrimos um git hash nele com o botão direito do mouse >
4. git clone e cola a URL copiada

------

##### Dicas para achar um repositório

Para achar qualquer repositório usamos o **" / "** e o nome do repositório depois.

------

------

## Criando seu Primeiro Repositório no GitHub Para Compartilhar Seu Progresso

> "Alguém está sentado na sombra hoje porque alguém plantou uma arvore há muito tempo". Warren Buffett
>

##### Criando um repositório no github

vai no seu perfil e vai em new repositórios > 
coloca o nome, e pode ativar a opção README ( que vai servir como um cartão de boas vindas indicando o que tem no código ) >



























































