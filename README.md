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

Nome: Campo que armazena o nome do cliente.

Sobrenome: Campo que armazena o sobrenome do cliente.

CPF: Campo que armazena o cadastro de pessoa física do cliente.

e-mail: Campo que armazena o e-mail de contato do cliente.

Senha: Campo que armazena a senha individual do cliente.

telefone: Campo que armazena o telefone de contato do cliente.

Código fiscal de operação: Campo que corresponde a um atributo único, pois para cada conta cliente existirá um código fiscal de operação diferente.

Código de identificação: Campo que corresponde a um atributo único, pois para cada conta cliente existirá um código de identificação diferente.

Número medidor: Campo que corresponde a leitura no equipamento em relação ao consumo, este é a diferença entre a leitura atual e a última realizada, multiplicado pela constante do medidor. Tanto a última leitura como a constante estão disponíveis em sua conta de energia.

Tensão elétrica: Campo onde é informada a tensão elétrica da região do cliente.

AMBIENTE CLIENTE: Tabela onde se incorpora os ambientes da sua casa.

Classificação: Classifica o ambiente que receberá os cômodos como residencial, industrial ou comercial.

CÔMODO: Tabela onde se gerencia o consumo de energia de um determinado cômodo. 

Nome: Campo que armazena os nomes de cada cômodo cadastrado pelo cliente.

Consumo de kw/h: Campo onde se armazena o consumo total de cada cômodo. 

APARELHOS DO AMBIENTE: Tabela onde se adiciona aparelhos a um ambiente.

Data início: Data de instalação do aparelho em seu respectivo cômodo. 

Data fim:  Data de retirada do aparelho em seu respectivo cômodo. 

APARELHOS: Tabela de identificação de aparelhos. 

Indicador economia: Indica se o aparelho possui a função de economia de energia. 

Função Stand-by: Indica se o aparelho possui a função Stand-By.

Potência: Campo onde se armazena a potência do aparelho.

Modelo: Campo onde identifica o modelo do aparelho.

Nome: Campo onde se nomeia o aparelho.

Quantidade de aparelhos: Campo onde se adiciona a quantidade de aparelhos de um mesmo tipo.

MARCAS: Tabela de identificação e qualificação de marcas.

Aprovação: Campo onde se classifica a marca como boa ou não baseada nas avaliações dos clientes.

Eficiência: Campo onde se classifica a marca como eficiente ou não baseado em pesquisas.

CONSUMO: Tabela que registra o consumo dos aparelhos.

Data hora início: Campo onde se adiciona a data e hora de início de uso do aparelho.

Data hora fim: Campo onde se adiciona a data e hora de fim do uso do aparelho.

Kw gastos: Campo que possui a quantidade de kw gastos no total por aparelho.

HISTÓRICO DE PAGAMENTO: Tabela onde se tem todo o histórico de pagamento de contas.

Data de pagamento: Campo onde se tem a data de quando foi efetuado o pagamento.

Data de vencimento: Campo onde se possui a data de vencimento da conta.

Data leitura: Campo onde se tem a data de leitura da conta de um respectivo mês. 

Valor: Campo onde se encontra o valor total a ser pago em um respectivo mês. 

Mês referência: Campo onde se tem um mês referência, o mês atual sempre será atualizado e os posteriores registrados.

TRIBUTO: Tabela que armazena valor do tributo e seu tipo.

Tipo: Campo onde identifica qual é o tributo aplicado.

Valor: Campo onde identifica qual é o valor aplicado.

BANDEIRA: Tabela que armazena o tipo da bandeira e o seu valor.

Tipo: Campo onde se tem o grau da bandeira: verde (sem acréscimo), amarela (R$1,50 de acréscimo) e vermelha (R$3,00 de acréscimo).

Valor: Campo onde se tem o valor de cada bandeira. 

MULTA: Tabela que armazena as multas aplicadas na conta.

Multa diária: Campo onde é visto as multas de atrasos diários.

Multa mensal: Campo onde é visto as multas de atrasos mensais.

Mês referência: Campo onde se tem um mês referência, o mês atual sempre será atualizado e os posteriores registrados.


   
### 6	MODELO LÓGICO<br>
       
   AA

### 7	MODELO FÍSICO<br>
       
   AA

        




 


