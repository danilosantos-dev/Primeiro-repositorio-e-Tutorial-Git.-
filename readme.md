#Opaa, como vai ? , Meu nome é Danilo e esse é meu primeiro repositorio e um manual de instruções pra você que ainda não sabe como subir seus arquivos para seu repositorio no github.

Criando nosso primeiro repositorio:

Assim que estiver logado no seu github poderá ver no canto esquerdo superior "new", caso não ache va até seu perfil e entre em "repositories" lá você vai encontrar a opção de criar um novo repositorio. Assim que clicar, o github ira pedir um nome para seu repositorio, se quiser pode colocar uma descrição e logo em baixo duas opções: "public" e "private", sugiro que clique em public para que as pessoas possam ver seu repositorio e consigam contribuir com voce.
Recomendo que marque a opção "readme file", O README é um arquivo com extensão . md, ou seja, ele é escrito em Markdown que é uma linguagem de marcação utilizada para converter o texto em um HTML válido, ou seja, você poderá adicionar textos no seu repositorio, assim como esse que você está lendo agora. 
 
Agora é so clicar em "create repository".

Adicionando arquivos no repositorio:

Para que possamos adionar aquivos no nosso recem criado repositorio no github iremos usar o Git, caso não tenha instalado está aqui o link para download : https://git-scm.com/ .

Com uma pasta criada e com os arquivos que você deseja subir dentro, iremos abri-la, clique com o botao direito do mause e selecione "git bash here", com o terminal do git aberto vamos cadastrar nossas credenciais com "git config --global user.email'seu email.com'  " e para o nome "user.name ' seu nome ' ".
Logo apos digite "git init" para criar o repositorio local em sua pasta, em seguida um "git add . " , um "git status"  para mostrar os arquivos dentro da pasta que foram adicionados, em seguida "git comit -m 'primeiro repositorio' ", para comitar.
Para sincronizarmos o repositorio da sua maquina com o github, copie a opção "https" no seu repositorio recem criado no github e digite no terminal " git remote add origin 'cole o https' ",em seguida "git push -u origin main", irá pedir para logar no seu github, faca isso e será adionado seus arquivos. 

Como iniciante e estudante espero ter ajudado e lembrar que caso tenha algum erro ou duvida existem muitos videos-tutoriais detalhados que podem ajudar.