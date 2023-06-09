# Cuidar+
Projeto Senac 

# Sobre o projeto 

Link de uso do projeto :

O projeto Cuidar+ é uma aplicação, que foi desenvolvido pensando em facilitar a gestão e monitoramento dos pacientes idosos que necessitam do acompanhamento hospitalar, ela permite que médicos, enfermeiros e outros profissionais de saúde possam se cadastrar e oferecer seus serviços de maneira integral, proporcionando um atendimento eficiente e seguro aos pacientes. 

## Layout
<img src="https://github.com/GrupoSenac/CuidarMais/blob/main/img/Tela%20inicial.png"  width="400" height="220"> <img src="https://github.com/GrupoSenac/CuidarMais/blob/main/img/Fluxo%201%20Tela%20Contrate%20Aqui.png" width="400" height="220">
<img src="https://github.com/GrupoSenac/CuidarMais/blob/main/img/Fluxo%202%20Tela%20de%20Login%20Cuidadores.png" width="400" height="220"> 
<img src="https://github.com/GrupoSenac/CuidarMais/blob/main/img/Fluxo%202%20Tela%20de%20Cadastro%20Cuidadores.png" width="400" height="220">
<img src="https://github.com/GrupoSenac/CuidarMais/blob/main/img/Fluxo%202%20Tela%20de%20Cadastro%20Pop-UP%20cadastro%20realizado.png" width="400" height="220">



## Padrão arquitetural
A aplicação Cuidar+ foi projetada através da arquitetura padrão MVC (Model View Controller). Por meio deste padrão de arquitetura, o projeto fica separado em camadas (camadas lógicas), promovendo a separação do código em partes distintas, dependendo da separação de responsabilidade dos componentes.
Neste padrão, o Model do projeto, conterá a parte da lógica de negócios, a view irá apresentar nas telas, como informações para o usuário. E por fim, temos a intermediação das camadas que serão executadas pelo controlador.

# Tecnologias utilizadas
## Back end
•	C#

•	Entity Framework

•	BCrypt

## Front-end
•	Html

•Css

•	Javascript

•	SweetAlert

## Banco de dados relacional
• Microsoft SQL Server Management Studio 18

# IDE utilizada
• Visual Studio Code

# Executando o projeto
## Front-end

iniciando o projeto: Control + F5 na pasta inicial do projeto.

## Back end
Dependências para rodar o projeto: BCrypt, EntityFramework, .NET 6.

Banco de dados: Microsoft SQL

iniciando o projeto: comando dotnet run no terminal do Visual Studio Code.

# Testando a aplicação
## Tela inicial
Na primeira página, há duas opções de caminho para o usuário: clicar no botão de contrate aqui ou seja um cuidador. Ao clicar em contrate aqui, o usuário será direcionado para uma tela na qual ele terá os cuidadores a disposição. Ao clicar no botão seja um cuidador, será carregado uma tela de login.

## Tela de login
Na tela de login, caso o usuário não possuir cadastro, ele poderá clicar em “Se não possui cadastro clique aqui”.
Ao receber a confirmação de análise dos dados cadastrais, o usuário poderá realizar o login. Lembrando que ambos os campos dessa tela são obrigatórios e que a senha deve ter no mínimo 8 caracteres. Há validações sendo feitas pelo servidor, onde é verificado se os dados informados estão no formato válido, caso contrário o usuário ira receber um pop-up de erro solicitando que preencha os dados corretamente.

## Tela de contrate aqui
Nesta tela, é apresentada uma tabela com a ficha técnica dos profissionais e o preço que estes cobram pelo serviço.

## Tela de cadastro
Nesta tela, o usuário deverá digitar seus dados e preencher todos os campos obrigatórios (nome, e-mail, CPF, idade, Telefone, Estado, Cidade, Área de atuação, Valor de cobrança – Dia, Valor de cobrança – Noite, Número da carteira profissional, Senha). 

Obs. Importantes: O CPF deve ter 11 caracteres; A senha deve ter 8 caracteres, no mínimo; Senha e confirmação de senha devem ser iguais.
Caso as informações estejam de acordo, ele receberá um pop-up informando que o cadastro foi executado com sucesso! E ele será redirecionado para a tela de login.

Ao realizar o cadastro, as informações do usuário serão validadas pelo servidor e armazenadas em um banco de dados relacional.

## Resultados
O backend e o frontend foram desenvolvidos, testados e estão funcionando separadamente e a integração entre as duas partes está funcionando de forma eficaz.

# Autores:
- Amanda Barreto Rocha
- Lucas Pereira Costa
- Lúcio Dos Santos Júnior
- Priscila Cristina de Melo
- Rafaela Eduarda Teixeira Silva
- Roberto Macedo
