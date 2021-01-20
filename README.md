# Projeto Formulário com Card
## Sobre
###O Projeto Angular 8 Formulário com Card é um projeto para prática de conhecimentos adquiridos durante curso do professor Edson Belém. Ideia é utilizar dois aprendizados anteriores, que é o preenchimento de um formulário e colocar foto.  
---
## Tecnologias utilizadas
O projeto foi desenvolvido utilizando as seguintes tecnologias
- Angular 8, versão 8.1.2.	
- Html,
- JavaScript,
- Visual Studio Code 
---
# Descrição
-Todo nosso desenvolvimento acontece no núcleo do Angular que é a pasta “app”. 
Em nossa classe “app.module.ts”, entramos com as extensões que precisaremos para rodar nosso projeto, tudo de forma reativa. Entramos com tudo que iremos programar(Formulário reativo=FormsModule).
Ainda em na pasta “app”, criamos as pastas modelo(model) e serviço(service).
Dentro de nosso model criamos nossa classe usuário, sempre pensando em uma estrutura limpa e uma forma de aproveitar a velocidade da linguagem. Nela entramos com a estrutura de nossos dados como: tipo, entrada(constructor) e saída(toString).
Pronto para receber os dados!
Em “app” criamos uma classe serviço(service), para logar, registrar e criamos classe mock que vai enviar funcionar como um fornecedor de dados.
Na variável global ServiceUsuario vamos criar o método create
Usado em HTML comando offset para dar um espaço no lado esquerdo(offset-md-5)

---
## Como baixar o projeto
```bash
## Clonar o repositório
$git clone https://github.com/WalaceLima/Angular9_Fomulario-Card.git
$cd projetoCard_Fotos

## Entrar no diretório
$cd Angular9_Fomulario-Card

## Instalar as dependências
$yarn install

## Instalar o projeto
$yarn start
```
---
Desenvolvido por Walace Luiz de Souza Lima
