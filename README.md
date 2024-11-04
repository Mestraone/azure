Explicando um pouco dos códigos utlizados neste trabalho de banco de dados! 
DriverID Int primary key identify: Criação de usuario para cada motorista.
Nome Varchar(100) NOT NULL: Armazena o nome do motorista. Este campo não pode deixar vazio.
CNH Varchar(20) Not Null Unique: Armazena a cnh do motorista. O número introduzido aqui, devera ser único, para não ter conflitos com outros armazenamentos e também será obrigatorio a introduzação da CNH.
Endereço Varchar(200): Armazena o endereço.

Já a tabela de pedidos, também tem códigos parecidos com a de motoristas. Só as propostas mudam, porém muitos tem a mesma função como o "OrderID int primary key identity", criando um identificador único.
Nome VARCHAR(100) NOT NULL: guarda o nome do cliente e é um campo requerido.
Empresa VARCHAR(100): guarda o nome da empresa do cliente, caso exista.
Endereço VARCHAR(200): guarda o endereço do cliente.
Contato VARCHAR(50): guarda as informações de contato do cliente.
A tabela guarda ordens feitas pelos clientes. Aqui estão os campos na tabela e o que é: OrderID INT PRIMARY KEY IDENTITY(1,1);
