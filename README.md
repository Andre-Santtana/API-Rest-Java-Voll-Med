# API-Rest-Java-Voll-Med
Curso de Spring Boot 3: desenvolva uma API Rest em Java


Crie do zero uma API Rest em Java com Spring Boot
Desenvolva CRUDs utilizando o banco de dados MySQL
Utilize o Flyway como ferramenta de Migrations da API
Realize validações utilizando o Bean Validation
Realize paginação dos dados da API


Cadastro de médicos:

Descrição
O sistema deve possuir uma funcionalidade de cadastro de médicos, na qual as seguintes informações deverão ser preenchidas:

Nome
E-mail
Telefone
CRM
Especialidade (Ortopedia, Cardiologia, Ginecologia ou Dermatologia)
Endereço completo (logradouro, número, complemento, bairro, cidade, UF e CEP)
Todas as informações são de preenchimento obrigatório, exceto o número e o complemento do endereço.


Listagem de médicos

Descrição
O sistema deve possuir uma funcionalidade de listagem de médicos, na qual as seguintes informações, de cada um dos médicos cadastrados, deverão ser exibidas:

Nome
E-mail
CRM
Especialidade
A listagem deve ser ordenada pelo nome do médico, de maneira crescente, bem como ser paginada, trazendo 10 registros por página.


Atualização de médicos:

Descrição
O sistema deve possuir uma funcionalidade de atualização de dados cadastrais de médicos, na qual as seguintes informações poderão ser atualizadas:

Nome
Telefone
Endereço
As seguintes regras de negócio devem ser validadas pelo sistema:

Não permitir a alteração do e-mail do médico;
Não permitir a alteração do CRM do médico;
Não permitir a alteração da Especialidade do médico.


Exclusão de médicos:

Descrição
O sistema deve possuir uma funcionalidade que permita a exclusão de médicos cadastrados.

As seguintes regras de negócio devem ser validadas pelo sistema:

A exclusão não deve apagar os dados do médico, mas torná-lo como "inativo" no sistema.


Cadastro de pacientes:

Descrição
O sistema deve possuir uma funcionalidade de cadastro de pacientes, na qual as seguintes informações deverão ser preenchidas:

Nome
E-mail
Telefone
CPF
Endereço completo (logradouro, número, complemento, bairro, cidade, UF e CEP)
Todas as informações são de preenchimento obrigatório, exceto o número e o complemento do endereço.


Listagem de pacientes:

Descrição
O sistema deve possuir uma funcionalidade de listagem de pacientes, na qual as seguintes informações, de cada um dos pacientes cadastrados, deverão ser exibidas:

Nome
E-mail
CPF
A listagem deve ser ordenada pelo nome do paciente, de maneira crescente, bem como ser paginada, trazendo 10 registros por página.


Atualização de pacientes:

Descrição
O sistema deve possuir uma funcionalidade de atualização de dados cadastrais de pacientes, na qual as seguintes informações poderão ser atualizadas:

Nome
Telefone
Endereço
As seguintes regras de negócio devem ser validadas pelo sistema:

Não permitir a alteração do e-mail do paciente;
Não permitir a alteração do CPF do paciente.


Exclusão de pacientes:

Descrição
O sistema deve possuir uma funcionalidade que permita a exclusão de pacientes cadastrados.

As seguintes regras de negócio devem ser validadas pelo sistema:

A exclusão não deve apagar os dados do paciente, mas torná-lo como "inativo" no sistema.







