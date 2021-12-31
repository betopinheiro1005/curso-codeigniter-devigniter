# Curso de Codeigniter  

## Devigniter (Pedro Henrique)

### Lista de aulas  

001 - Introdução e organização do projeto  
002 - Recaptulando o produto do curso anterior  
003 - Controle de sessão e ajustes de redirecionamento  
004 - Projeção do Dashboard  
005 - Barra de Navegação Navbar  
006 - O Controller Usuário, inicio  
007 - Exibindo Usuários  
008 - Editando Usuários (Parte 1: Obtendo informações)  
009 - Editando Usuários (Parte 2: Exibindo informações)  
010 - Editando Usuários (Parte 3: Validação e persistência)  
011 - Editando Usuários (Parte 4: Verificando erros sem cortes)  
012 - Editando Usuários (Parte 5: Corrindo outros erros)  
013 - Editando Usuários (Parte 6: BÔNUS Repopulando campos do formulário)  
014 - Editando Usuários (Parte 7: FINAL Dando um Review)  
015 - Excluindo Usuários (DELETE)  
016 - Cadastrando Usuários - INSERT  
017 - Configurando a Rota Default Rota Padrão  
018 - Sistema de Templates  
019 - Sistema de Templates FINAL  
020 - Removendo o Menu do Login  
021 - Upload de Arquivos - Parte 1 Pesca na Documentação  
022 - Upload de Arquivos - Parte 2 Esboço  
023 - Upload de Arquivos - Parte 3 Enviando os arquivos e salvando no banco  
024 - Upload de Arquivos - Parte 4 Exibindo os arquivos enviados  
025 - Upload de Arquivos - Parte 5 Excluindo os arquivos enviados  

# I'm DevIgniter
Curso voltado a ensinar o Framework PHP conhecido como CodeIgniter para criarmos um sistema dinâmico.

## Pré-requisitos
* 1- Ter feito meu curso anterior: https://youtu.be/wnkYF9ptxVU
* 2- Ter conhecimento de GIT (É sério!) ou assistir este vídeo: https://youtu.be/TReVFOxhh7E

## Configuração do ambiente
* 1- Instale o seu servidor WAMP, LAMP ou MAMP
* 2- Habilite o mod_rewrite do apache
* 3- Clone este repositório com o comando git clone em uma pasta que esteja dentro do seu servidor local...
```md
# Comando para clonar:
git clone https://github.com/pedrohills/im-devigniter.git
```
* 4- Entre na pasta do repositório clonado
* 5- Resete o repositório clonado para este [commit](https://github.com/pedrohills/im-devigniter/commit/4503513a7bc2eb6efb4b7b62c87277c945b4a74c):
```md
# Basta executar este commando...
git reset --hard 4503513a7bc2eb6efb4b7b62c87277c945b4a74c
```
* 6- Crie um banco de dados chamado cursocodeigniter
* 7- Entre no banco criado e adicione esta query SQL
```SQL
CREATE TABLE IF NOT EXISTS `usuarios` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `email` varchar(200) NOT NULL,
  `senha` varchar(20) NOT NULL,
  `created` timestamp NULL DEFAULT CURRENT_TIMESTAMP,
  PRIMARY KEY (`id`)
) ENGINE=MyISAM DEFAULT CHARSET=latin1 AUTO_INCREMENT=1 ;
```
* 8- Vamos começar? 

## Quero ajudar, como faço?
Você pode ajudar de duas formas, ambas opcionais e não obrigatórias, são elas:

### 1- Campanha no site kickante
Eu criei uma campanha no site kickante para poder ter um meio para receber a
contribuição de vocês, então fiquem à vontade para contribuir como quiserem...

Para participar da campanha, basta acessar este link:
http://www.kickante.com.br/campanhas/codeigniter-completo

### 2- Clube mensal
Confeso para vocês que não manjo muito do kickante ainda, mas, após criar a
campanha o kickante me ofereceu a possibilidade de criar um clube mensal,
aproveitei que já estava ali e criei.

Para participar do clube mensal, basta acessar este link:
http://www.kickante.com.br/campanhas/contribuicao-mensal/devigniter
