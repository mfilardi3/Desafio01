# Desafio_Attributor

<p>Desafio processo seletivo Attributor</p>

<h1><b>Criando o projeto</b></h1>

1.Clique em <b>criar novo projeto</b> ao abrir o Visual Studio

2.Insisa ASP.NET na tabela de pesquisa e escolha C# na linguagem de programação

3.Escolha o <b>Aplicativo Web ASP.NET (.NET Framework)</b> e clique em <b>Próximo</b>

4.Nomeie seu aplicativo e clique em <b>Criar</b> 

5.Selecione <b>MVC</b> e clique em <b>Criar</b>

<h1><b>Criando e enviando arquivos para o repositório no github</b></h1>

1.Abra a conta do github, faça login e clique em <b>New Repository</b>

2.Abra o prompt de comando vá até o caminho da sua pasta e para transformar ela em um repositório digiti <b>git init</b>

<code> $ git init </code>

3.Adicione o caminho para o repositório

<code>$ git remote add origin https://github.com/mfilardi3/Desafio_Attributor/</code>

4.Para verificar as alterações no git digite <b>git status</b>

5.Adicione os seus arquivos ao repositório 

<code>$ git add *</code>

6.Para confirmar as mudanças feitas digite <b>git commit</b>

<code>$ git commit -m "comentário"</code>

7.Envie as mudanças feitas ao repositório remoto

<code>$ git push -u origin master</code>

Obs: Caso haja mudanças no repositório que não estão no seu arquivo é preciso usar o <b>git pull</b>

<code>$ git pull</code>

<h1><b>Codificando</h1></b>
<h2>Aplicações MVC:</h2>
<img src="https://cdn-images-1.medium.com/max/1600/1*1qspMILbe0d48nq4sEhKLQ.png">
É uma arquitetura para implementar a interface do usuário.
<h2>View</h2>
Responsável pela exibição de dados .

<h2>Controller</h2>
Recebe as requisições do usuário controlando qual Model usar e qual view será mostrado ao usuário.

<h2>Model</h2>
Responsável pela leitura, escrita e validação dos dados 

<h1><b>Deploy AWS</b></h1>
 
 1.Abra o Console do Elastic Beanstalk com este link pré-configurado: console.aws.amazon.com/elasticbeanstalk/home#/newApplication?applicationName=tutorials&environmentType=LoadBalanced
 
 2.Para Platform, escolha a Plataforma que corresponde à linguagem usada pelo aplicativo.
 
 3.Selecione Review clique em duas regiões e subregiôes
 
 4.Selecione launch
 
 5.Examine as opções disponíveis. Quando estiver satisfeito com elas, escolha Create app.
 
 6.Certifique-se de que o ambiente foi iniciado com êxito verificando o status de Health (Integridade) no Console do Elastic Beanstalk. O status deve ser Green.
 
 7.No Visual Studio, abra Desafio01.sln.
 
 8.No menu View, escolha Solution Explorer.
 
 9.Abra o menu de contexto (clique com o botão direito) de MVC5App e escolha Publish to AWS.
 
 10.Na página Publish to AWS Elastic Beanstalk, para Deployment Target, escolha o ambiente que você acabou de criar e, em seguida, escolha Próximo.
 
 11.Na página Application Options, aceite todos os valores padrão e escolha Próximo.

12.Na página Análise, escolha Deploy.

13.Volte para o Console do Elastic Beanstalk e escolha o nome do aplicativo que aparece ao lado do nome do ambiente.

