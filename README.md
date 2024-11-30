Este código em Java é para uma aplicação Android que simula o lançamento de dois dados. 
A classe principal, MainActivity, estende AppCompatActivity e define a interface gráfica da aplicação no método onCreate. 
Ao iniciar, o layout é configurado para activity_main.xml, que contém um botão "ROLL", dois ImageView para representar os dados e um TextView com o título "Dicee".

Quando o botão "ROLL" é clicado, um listener de clique é acionado, gerando aleatoriamente dois números entre 1 e 6 usando a classe Random. 
Esses números correspondem às faces dos dados, e as imagens dos dados são atualizadas de acordo com os resultados gerados. 
O resultado da soma dos dois dados é calculado e exibido em uma mensagem de toast, além de ser registrado no log de depuração para fins de monitoramento.

O layout é estruturado com um ConstraintLayout, permitindo um posicionamento flexível dos elementos. 
O TextView exibe o título da aplicação, enquanto o ImageView central apresenta o logotipo. 
Os dados são dispostos lado a lado, e o botão "ROLL" está posicionado abaixo deles. 
Assim, a aplicação oferece uma experiência interativa e visual, permitindo que os usuários simulem o lançamento de dados de forma divertida e simples.

Um grande abranço para meu Amigo Marcos Diego Sousa Marques que foi fundamental nesse projeto. 




