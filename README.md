# TRABALHO 01:  Ecolamp.
Trabalho desenvolvido durante a disciplina de Banco de Dados do Integrado

# Sumário

### 1. COMPONENTES<br>
Integrantes do grupo<br>
Maria Gabriela Siqueira Tavares: gabi_bailarina2002@hotmail.com<br>
Pedro Caio Miranda de Araujo: pc_788@hotmail.com<br>
...

### 2.INTRODUÇÃO E MOTIVAÇAO<br>

Sabendo-se dos desafios enfrentados pelo cidadão para compreender os dados exibidos na conta de energia elétrica e suas dúvidas ao se perguntar se está pagando um preço justo ou não, a dupla correspondente ao 2º ano de Informática Integrado a Internet se viu instigada a desenvolver esse projeto com o objetivo de  transmitir o conhecimento e a verdade para o consumidor. O sistema de banco de dados denominado ECOlamp tem como motivação principal solucionar a complexidade das contas de energia elétrica, envolvendo desde a composição da tarifa até os impostos sobre esta, e propor opções econômicas para reduzir o gasto de energia elétrica, através do armazenamento de dados sobre o custo, rotina e reconhecimento do consumo dos equipamentos elétricos do ambiente em aplicação.

 

### 3.MINI-MUNDO Novo<br>

O sistema constituinte do projeto Ecolamp apresentará os dados armazenados a seguir. Da Conta Cliente serão coletados nome, sobrenome, CPF, senha, e-mail, telefone de contato, bairro, estado e cidade, além disso também serão coletados dados como código fiscal de operação, código fiscal de identificação, número do medidor, número de instalação e a tensão elétrica. Assim como o cliente, o fornecedor de energia também irá apresentar bairro, estado e cidade, além de nome e CNPJ. O estado em que o fornecedor se encontra será o mesmo estado em que ele realizará os serviços. Esta conta será associada a um histórico de pagamentos que cobrará um custo envolvendo o valor, mês referente, data da leitura, data de pagamento e data de vencimento. O custo vai exigir vários tributos que possuirão tipo e valor, este também requer a bandeira correspondente ao custo da energia elétrica do período, possuindo também o seu tipo e valor.
	A conta cliente registra um ambiente cliente pertencente a uma classificação, como residencial, industrial, comercial, entre outros. Este ambiente pertencerá a apenas uma conta cliente e deve apresentar um ou vários cômodos, que será específico daquele meio. O cômodo pode possuir vários ou nenhum aparelho, que possuem nome, modelo, potência, função stand-by, indicador de economia e a quantidade do aparelho determinado. 
	Um ou vários aparelhos devem pertencer obrigatoriamente a um cômodo. Os aparelhos pertencem a uma marca avaliada em sua eficiência e aprovação pelos próprios clientes e consumidores. Uma marca pode pertencer a vários ou nenhum aparelho registrado no cômodo. Um ou mais aparelhos dispõe do seu consumo que pode variar de acordo com a data e hora de ínicio e fim do consumo de energia num período de tempo e o kw gasto por hora. Um aparelho pode consumir nenhuma energia num determinado período de tempo e um consumo só pertencerá a um aparelho. Os aparelhos também irão abranger aparelhos de um determinado ambiente, para registrar e atualizar o sistema caso algum aparelho seja trocado de cômodo. 
	O sistema também coletará informações sobre possíveis multas taxadas sobre o valor, armazenando a multa diária, multa mensal e mês referente a estas.



### 4.RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)<br>

https://docs.google.com/document/d/1MemBWNTcKK8WOqaqrCdKcEWDyN0hmIT53nJta1VhsC0/edit?usp=sharing <br>


#### 4.1 TABELA DE DADOS DO SISTEMA:

https://docs.google.com/document/d/1IiGW4k9ATahRMywNqXrKiTDwStTmbR15Ba8o6wayJpU/edit?usp=sharing
    
    
#### 4.2 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?

 a) O sistema proposto poderá fornecer quais tipos de relatórios e informaçes? 
 
 O sistema fornecerá relatórios sobre os clientes, como a preferência de plataforma de e-mail entre os clientes, a principal tensão elétrica entre os usuários e os principais endereços, incluindo estado, cidade e bairro, que utilizam o sistema. Em relação ao ambiente serão fornecidos relatórios sobre a variedade de classificações e qual é a mais utilizada, a variedade de cômodos que um ambiente pode ter, o consumo médio em kw/h e a quantidade média de aparelhos dependendo do cômodo e ambiente, logo fornecendo também qual cômodo consome mais energia e qual ambiente e/ou cômodo possuem mais aparelhos. Já nos aparelhos é possível relatar sobre a diversidade de potências e a potência predominante nos aparelhos, os aparelhos que possuem ou não função stand-by, os aparelhos que mais economizam energia, a média do tempo de uso de um aparelho e o consumo médio de kw/h de cada aparelho, logo fornecendo também qual aparelho é utilizado por mais tempo e qual aparelho consome mais energia, além de expor as marcas dos aparelhos dos usuários, qual a marca mais aprovada entre os clientes e qual tem a maior eficiência segundo a avaliação destes.
	Sobre os fornecedores será possível informar sobre quais foram cadastrados, qual estado eles atendem e qual endereço, desde estado, cidade e bairro, ele se localiza, logo criando um relatório sobre quais os fornecedores pertencem a cada estado. 
	No histórico de pagamento relataremos o preço da conta de luz de cada mês e através destes informaremos qual o mês que houve o maior e menor gasto de energia, além do preço médio que o cliente pagará por mês. Outros relatórios serão responsáveis por verificar os pagamentos que foram realizados no prazo e os que não foram, sendo pagos após a data de vencimento, e indicar os meses que incluíram o valor de multa e os que não obtiveram uma multa cobrada, logo conseguindo fornecer qual o mês que possuiu o maior valor de multa. Por fim, serão informados os valores dos tributos e dos acréscimos das bandeiras em cada mês, referenciado já no histórico de pagamentos, e através destes será possível relatar o mês em que foi pago o maior e menor valor em impostos, além de qual cor de bandeira tarifária correspondeu ao mês determinado. 

   b) Crie uma lista com os 10 principais relatórios que poderão ser obtidos por meio do sistema proposto!
 
--> Histórico de pagamento.
--> Relatório de custos da conta.
--> Relatório de cômodos.
--> Relatório de  eficiência de aparelhos de acordo com sua marca.
--> Aparelhos registrados. 
--> Consumo individual de um aparelho num determinado período de tempo. 
--> Avaliação de marcas.
--> Principal tensão elétrica entre os clientes.
--> Relações entre ambiente, cômodo e aparelhos.
--> Aparelhos que possuem função stand-by. 

 

### 5.MODELO CONCEITUAL<br>
  
   FALTA COLOCAR
       
#### 5.1 Validação do Modelo Conceitual
    [Grupo01]: [Nomes dos que participaram na avaliação]
    [Grupo02]: [Nomes dos que participaram na avaliação]

#### 5.2 DECISÕES DE PROJETO
  
a) Campo CPF: corresponde a um atributo único, pois cada cliente possuirá um Cadastro de Pessoa Física diferente.

b) Campo Telefone: corresponde a um atributo único, pois cada cliente possuirá um telefone com números diferentes.

c) Campo Código Fiscal de Operação: corresponde a um atributo único, pois para cada conta cliente existirá um código fiscal de operação diferente.

d) Campo Código de Identificação: corresponde a um atributo único, pois para cada conta cliente existirá um código de identificação diferente.

e) Campo Data Início: existe para indicar a data inicial em que um aparelho foi colocado em um determinado ambiente.

f) Campo Data Fim: existe para indicar a data final de um aparelho num determinado ambiente, este campo determina se o aparelho foi trocado de ambiente ou não.

g) Campo Data/Hora Início: existe para armazenar a data e hora em que começa o consumo de energia de um determinado aparelho.

h) Campo Data/Hora Fim: existe para armazenar a data e hora em que finaliza o consumo de energia de um determinado aparelho, a diferença entre este campo e o anterior corresponderá ao tempo de uso do aparelho.

i) Campo Indicador Economia: existe para verificar se um aparelho possui ou não um modo econômico de energia.

j) Campo Função Stand-by: existe para verificar se um aparelho possui ou não função stand-by.




#### 5.3 DESCRIÇÃO DOS DADOS 
   
 BAIRRO: Tabela que armazena as informações relativas à bairro.

CIDADE: Tabela que armazena as informações relativas à cidade.

ESTADO: Tabela que armazena as informações relativas à Estado.

FORNECEDOR DE ENERGIA: Tabela que armazena as informações relativas a empresa fornecedora de energia.

Nome: Campo que armazena o nome da empresa fornecedora de energia.

CNPJ: Campo que armazena o cadastro nacional da pessoa jurídica.

CONTA CLIENTE: Tabela que armazena as informações do cliente.

Nome: Campo que armazena o nome do cliente

Sobrenome: Campo que armazena o sobrenome do cliente

CPF: Campo que armazena o cadastro de pessoa física do cliente.

e-mail: Campo que armazena o e-mail de contato do cliente.

Senha: Campo que armazena a senha individual do cliente.

telefone: Campo que armazena o telefone de contato do cliente.

Código fiscal de operação: Campo que corresponde a um atributo único, pois para cada conta cliente existirá um código fiscal de operação diferente.

Código de identificação: Campo que corresponde a um atributo único, pois para cada conta cliente existirá um código de identificação diferente.

Número medidor: Campo onde você 

Tensão elétrica: Campo onde é informada a tensão elétrica da sua casa.

AMBIENTE CLIENTE: Tabela onde se incorpora os ambientes da sua casa.

Classificação: Onde se classifica o tipo de cômodo 

CÔMODO: Tabela onde se gerencia o consumo de energia de um determinado cômodo. 

Nome: Campo que armazena os nomes de cada como cadastrado pelo cliente.

Consumo de kw/h: Campo onde se armazena o consumo total de cada cômodo. 

APARELHOS DO AMBIENTE: Tabela onde se adiciona aparelhos a um cômodo.

Data início: Data de instalação do aparelho em seu respectivo cômodo. 

Data fim:  Data de retirada do aparelho em seu respectivo cômodo. 

APARELHOS: Tabela de identificação de aparelhos. 

Indicador economia: Se o aparelho possui a função de economia de energia. 

Função Stand-by: Se o aparelho possui a função Stand-By

Potência: Campo onde se armazena a potência do aparelho

Modelo: Campo onde identifica o modelo do aparelho 

Nome: Campo onde classifica o nome do aparelho.

Quantidade de aparelhos: Campo onde se adiciona o quantidade de aparelhos de um mesmo tipo.

MARCAS: Tabela 

Aprovação:

Eficiência:

CONSUMO: 

Data hora início:

Data hora fim:

Kw gastos:

HISTÓRICO DE PAGAMENTO:

Data de pagamento:

Data de vencimento:

Data leitura: 

Valor: 

Mês referência: 

TRIBUTO:

Tipo:

Valor:

BANDEIRA:

Tipo:

Valor:

MULTA:

Multa diária: 

Multa mensal: 

Mês referência: 

   
### 6	MODELO LÓGICO<br>
       
   https://github.com/Ecolamp/Ecolamp.github.io/blob/master/imagens/ecolamp_logico.png

### 7	MODELO FÍSICO<br>
       
   https://github.com/Ecolamp/Ecolamp.github.io/blob/master/imagens/ecolamp_fisico.png

        
### 8	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
#### 8.1 DETALHAMENTO DAS INFORMAÇÕES
        a) inclusão das instruções de inserção dos dados nas tabelas criadas pelo script de modelo físic
        b) formato .SQL

#### 8.2 INCLUSÃO DO SCRIPT PARA CRIAÇÃO DE TABELA E INSERÇÃO DOS DADOS
        a) Junção dos scripts anteriores em um único script 
        (create para tabelas e estruturas de dados + dados a serem inseridos)
        b) Criar um novo banco de dados para testar a restauracao 
        (em caso de falha na restauração o grupo não pontuará neste quesito)
        c) formato .SQL
#### 8.3 INCLUSÃO DO SCRIPT PARA EXCLUSÃO DE TABELAS EXISTENTES, CRIAÇÃO DE TABELA NOVAS E INSERÇÃO DOS DADOS
        a) Junção dos scripts anteriores em um único script 
        (Drop table + Create de tabelas e estruturas de dados + dados a serem inseridos)
        b) Criar um novo banco de dados para testar a restauracao 
        (em caso de falha na restauração o grupo não pontuará neste quesito)
        c) formato .SQL


### 9	TABELAS E PRINCIPAIS CONSULTAS<br>
    OBS: Incluir para cada tópico as instruções SQL + imagens (print da tela) mostrando os resultados.<br>
#### 9.1	CONSULTAS DAS TABELAS COM TODOS OS DADOS INSERIDOS (Todas) <br>
#### 9.2	CONSULTAS DAS TABELAS COM FILTROS WHERE (Mínimo 4)<br>
#### 9.3	CONSULTAS QUE USAM OPERADORES LÓGICOS, ARITMÉTICOS E TABELAS OU CAMPOS RENOMEADOS (Mínimo 11)
    a) Criar 5 consultas que envolvam os operadores lógicos AND, OR e Not
    b) Criar no mínimo 3 consultas com operadores aritméticos 
    c) Criar no mínimo 3 consultas com operação de renomear nomes de campos ou tabelas
#### 9.4	CONSULTAS QUE USAM OPERADORES LIKE E DATAS (Mínimo 12) <br>
    a) Criar outras 5 consultas que envolvam like ou ilike
    b) Criar uma consulta para cada tipo de função data apresentada.


    
#### 9.5	ATUALIZAÇÃO E EXCLUSÃO DE DADOS (Mínimo 6)<br>


#### 9.6	CONSULTAS COM JUNÇÃO E ORDENAÇÃO (Mínimo 6)<br>
        a) Uma junção que envolva todas as tabelas possuindo no mínimo 3 registros no resultado
        b) Outras junções que o grupo considere como sendo as de principal importância para o trabalho
        

## Marco de Entrega 02 em: (16/06/2018)<br>
### ATUALIZAÇÃO DA DOCUMENTAÇÃO DOS SLIDES PARA APRESENTAÇAO SEMESTRAL (Mínimo 6 e Máximo 10)<br>
<br>
    Data de Entrega: (30/06/2018)
<br>

#### 9.7	CONSULTAS COM GROUP BY E FUNÇÕES DE AGRUPAMENTO (Mínimo 6)<br>

#### 9.8	CONSULTAS COM LEFT E RIGHT JOIN (Mínimo 4)<br>
#### 9.9	CONSULTAS COM SELF JOIN E VIEW (Mínimo 6)<br>
        a) Uma junção que envolva Self Join
        b) Outras junções com views que o grupo considere como sendo de relevante importância para o trabalho
#### 9.10	SUBCONSULTAS (Mínimo 3)<br>

#### 9.11	LISTA DE CODIGOS DAS FUNÇÕES E TRIGGERS<br>
        Detalhamento sobre funcionalidade de cada código.
        a) Objetivo
        b) Código do objeto (função/trigger)
        c) exemplo de dados para aplicação
        d) resultados em forma de tabela/imagem
<br>


#### 9.12	GERACAO DE DADOS (MÍNIMO DE 100 MIL REGISTROS PARA PRINCIPAL RELAÇAO)<br>
        a) principal tabela do sistema deve ter no mínimo 100 mil registros
        b) tabelas diretamente relacionadas a tabela principal 10 mil registros
        c) tabelas auxiliares de relacao multivalorada mínimo de 10 registros
        d) registrar o tempo de inserção em cada uma das tabelas do banco de dados
        e) especificar a quantidade de registros inseridos em cada tabela
        Para melhor compreensão verifiquem o exemplo na base de testes:<br>
        https://github.com/discipbd2/base-de-testes-locadora
        

#### 9.13	Backup do Banco de Dados<br>
        Detalhamento do backup.
        a) Tempo
        b) Tamanho
        c) Teste de restauração (backup)
        d) Tempo para restauração
        e) Teste de restauração (script sql)
        f) Tempo para restauração (script sql)
<br>

Data de Entrega: (Data a ser definida)
<br>

#### 9.14	APLICAÇAO DE ÍNDICES E TESTES DE PERFORMANCE<br>
    a) Lista de índices, tipos de índices com explicação de porque foram implementados nas consultas 
    b) Performance esperada VS Resultados obtidos
    c) Tabela de resultados comparando velocidades antes e depois da aplicação dos índices (constando velocidade esperada com planejamento, sem indice e com índice Vs velocidade de execucao real com índice e sem índice).
    d) Escolher as consultas mais complexas para serem analisadas (consultas com menos de 2 joins não serão aceitas)
    e) As imagens do Explain devem ser inclusas no trabalho, bem como explicações sobre os resultados obtidos.
    f) Inclusão de tabela mostrando as 10 execuções, excluindo-se o maior e menor tempos para cada consulta e 
    obtendo-se a media dos outros valores como resultado médio final.
<br>
    Data de Entrega: (Data a ser definida)
<br>   

### 10	ATUALIZAÇÃO DA DOCUMENTAÇÃO DOS SLIDES PARA APRESENTAÇAO FINAL (Mínimo 6 e Máximo 10)<br>
<br>
    Data de Entrega: (Data a ser definida)
<br>

### 11 Backup completo do banco de dados postgres 
    a) deve ser realizado no formato "backup" 
        (Em Dump Options #1 Habilitar opções Don't Save Owner e Privilege)
    b) antes de postar o arquivo no git o mesmo deve ser testado/restaurado por outro grupo de alunos/dupla
    c) informar aqui o grupo de alunos/dupla que realizou o teste.

    
### 12	TUTORIAL COMPLETO DE PASSOS PARA RESTAURACAO DO BANCO E EXECUCAO DE PROCEDIMENTOS ENVOLVIDOS NO TRABALHO PARA OBTENÇÃO DOS RESULTADOS<br>
        a) Outros grupos deverão ser capazes de restaurar o banco 
        b) executar todas as consultas presentes no trabalho
        c) executar códigos que tenham sido construídos para o trabalho 
        d) realizar qualquer procedimento executado pelo grupo que desenvolveu o trabalho

### 13	DIFICULDADES ENCONTRADAS PELO GRUPO<br>  

    
>## Marco de Entrega 04/Entrega Final em: (Data definida no cronograma)<br>

       
### 14  FORMATACAO NO GIT: https://help.github.com/articles/basic-writing-and-formatting-syntax/
<comentario no git>
    
##### About Formatting
    https://help.github.com/articles/about-writing-and-formatting-on-github/
    
##### Basic Formatting in Git
    
    https://help.github.com/articles/basic-writing-and-formatting-syntax/#referencing-issues-and-pull-requests
   
    
##### Working with advanced formatting
    https://help.github.com/articles/working-with-advanced-formatting/

#### Mastering Markdown
    https://guides.github.com/features/mastering-markdown/

### OBSERVAÇÕES IMPORTANTES

#### Todos os arquivos que fazem parte do projeto (Imagens, pdfs, arquivos fonte, etc..), devem estar presentes no GIT. Os arquivos do projeto vigente não devem ser armazenados em quaisquer outras plataformas.
1. Caso existam arquivos com conteúdos sigilosos, comunicar o professor que definirá em conjunto com o grupo a melhor forma de armazenamento do arquivo.

#### Todos os grupos deverão fazer Fork deste repositório e dar permissões administrativas ao usuário deste GIT, para acompanhamento do trabalho.

#### Os usuários criados no GIT devem possuir o nome de identificação do aluno (não serão aceitos nomes como Eu123, meuprojeto, pro456, etc). Em caso de dúvida comunicar o professor.


Link para BrModelo:<br>
http://sis4.com/brModelo/brModelo/download.html
<br>


Link para curso de GIT<br>
![https://www.youtube.com/curso_git](https://www.youtube.com/playlist?list=PLo7sFyCeiGUdIyEmHdfbuD2eR4XPDqnN2?raw=true "Title")



 


