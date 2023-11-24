
# Automacação de e-mail em massa com Python

Este é meu mais novo projeto, desenvolvido em dois dias. Ele é simples, mas foi divertido de criar por vários aspectos.                                             
Minha primeira ideia era criar um muito mais simples, onde enviaria apenas um e-mail para apenas um contato, um código muito mais limitado, mas quis o implementar com a ajuda de videos, IA e meu conhecimento sobre a linguagem.

--------------------------

Um pouco sobre o projeto:
* Os e-mails precisam estar atualizados na planilha, para que funcione da maneira como deveria. E a planilha precisa estar na mesma dist que o .exe

* A senha comum do gmail não vai funcionar por politica do google, então precisa criar uma senha especifica para isso. Passo a passo em: 
https://www.youtube.com/watch?v=nFbZLX2U-5k

* A planilha precisa ser criada naturalmente, e salva como nome_que_escolher.xlsx

------------------------------

Pode servir para:

* Software bom para criar planilhas com nomes de empresas e mandar curriculo; para pegar clientes e mandar propostas ou promoções. Enfim, bom para muita coisa

-------------------------
  
Algumas de suas funcionalidades:

* Ele tenta enviar o e-mail ao se conectar com o servidor, caso não consiga ele volta um erro e o mostra no terminal

* Este código funciona muito bem como um .exe também, pois pode haver alterações na planilha e ainda assim não afetará o desempenho. Ele atualiza quando você inclui ou remove um email da lista, e manda para aqueles que apenas estão presentes lá.

------------------------
Sobre sua interface:

* Ele funciona diretamente no terminal, digitando seu atalho e o executando ou clicando no .exe criado

* Ele pedira que digite o e-mail que enviara as mensagens. Pedira a senha gerada pelo Senhas de App (por uma medida de segurança). A senha ficara invisivel ao ser digitada por causa da bibliteca getpass. Lembrando, tudo pelo terminal, mesmo após o .exe abrir.

* Os nomes das pessoas que o email foi enviado aparecerá após a confirmação dos requisitos.
---------------------------
# ATUALIZAÇÕES:

1.0
Foi adicionado agora a biblioteca tkinter, para abrir uma janela e uma caixa de dialogo para ser inserido e-mail, a senha, o assunto e o corpo do texto, em uma interface mais amigavel para quem for usar. A senha deu um trabalho a mais para se ajustar, pois a janela fechava ao pedir a senha, por causa da biblioteca que a deixava invisivel, então, a removi e troquei por '*'.

1.1
O tkinter foi substituito pelo PySimpleGUI para uma interface mais bonita, com duas caixas para escrever ao invés de uma de cada vez, mas com as mesmas funcionalidades.





