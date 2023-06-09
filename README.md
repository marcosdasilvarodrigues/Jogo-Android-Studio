Título do Jogo: (Jogo da Forca)

Docente: Robson Keemps

Discente: Marcos da Silva Rodrigues, Leidiane Cruzeiro, Raiane Costa.

Plataforma em que será lançada:
(Plataforma Android, plataforma Google Play, App Store )

Público-alvo (Ex.: Jogadores Casuais, Fãs de Jogos de Tabuleiro, etc):
O jogo conterá níveis de dificuldades fácil, médio e difícil, isso permitirá que
diversas pessoas independentes da idade e de seu nível de conhecimento usufruam
deste aplicativo, assim escolhendo a dificuldade conforme a opinião do usuário.
 Logo, qualquer pessoa pode jogar o Forca.
 
Classificação Indicativa;
Indicado para pessoas acima de 6 anos de idade.

Gênero do Jogo;
Pode-se dizer que o jogo da forca se enquadra no gênero de jogos de
tabuleiro ou jogos de palavras. Ele envolve adivinhar letras e palavras, usando o
raciocínio lógico e o conhecimento do vocabulário.

Resumo do Conceito do Jogo;
Como jogar:
Você também pode jogar Jogo da Forca por categoria, no qual cada tema
conta com uma quantidade de palavras disponíveis para ser jogada. A cada jogo há
uma palavra diferente.

• A palavra oculta está relacionada com a dica “Cidade”;

• O tamanho da palavra oculta (quantidade de letras) está representado pelos
traços;

• Clique em uma das letras. Se a letra existir na palavra, a letra será exibida.
Caso contrário, seu bonequinho ficará cada vez mais preso;

• A cada erro uma parte do corpo do bonequinho é desenhada: cabeça, tronco,
braço direito, braço esquerdo, perna direita e perna esquerda;

• O objetivo é descobrir a palavra oculta antes que o bonequinho fique
desenhado.

Pontos de Destaques (Mecânicas que se destacam em seu jogo).
O jogo contará com imagens relacionada a palavra oculta no jogo, o sistema
pré definirá a foto de acordo com a palavra a ser acertada, dando a dica da palavra
com a foto.
Nas categorias o sistema consegue emitir sons com o nome da categoria
selecionada.

No Resumo do Conceito Jogo é onde nós detalharemos vários pontos da
história e da jogabilidade, como:

 Diferentes níveis de dificuldade;

 Pontuação, que será dada pelo nível de dificuldade e tempo para resolução da
palavra-chave, onde o sistema classifica os melhores;

 Possibilidade de pausar a qualquer momento o jogo;

 Ranking com os melhores jogadores;

 Verificação do tempo que o jogador demora pra resolver a palavra-chave;

 Sistema completo de ajuda.

Aonde o seu jogo se passa?
Portanto, o jogo da forca pode ser jogado em qualquer lugar e não possui um
local específico onde se passa, mas sim depende da interação entre os jogadores
ou do meio escolhido para jogá-lo, seja físico ou digital.

 Qual o objetivo do jogador?
É o jogador acertar qual é a palavra proposta de acordo com tempo estabelecido.
Como é a interação do jogador com o jogo?
A interação do jogador é com número de letras e o tema ligado à palavra. A
cada letra errada, é uma parte desenhada no corpo do enforcado. E a cada palavra
certa, ganha pontos ou classificação.

 Que sentimento você quer causar no jogador ou que experiência você quer
fornecer a ele?
Desenvolver no jogador, a atenção, a concentração, a lógica e agilidade na
hora de jogar. Especialistas defendem que o jogo da forca ajuda as crianças a
ultrapassar problemas de dislexia. Pois ajuda treina a memória e estimula a
criatividade dos jogadores. Trabalha a socialização e interação entre os jogadores
em divertidas disputas. A ideia do jogo é de adivinhar qual a palavra que está oculta.
A informação inicial que o jogador dispõe é a do número de letras que compõem a
palavra.


Funcionalidades

Erro da letra

![Erro tela 1](https://github.com/marcosdasilvarodrigues/Jogo-Android-Studio/assets/105816659/89380153-e8fc-45d7-89d3-1db4ebdc34ac)

![Erro tela 2 - Copia](https://github.com/marcosdasilvarodrigues/Jogo-Android-Studio/assets/105816659/177900ea-dff9-46e1-b67f-134d895a62d7)

A classe (ForcaController) gerencia a exibição da imagem da forca no jogo, conforme os erros do jogador. Ela recebe um ImageView no construtor e possui o método (mudaForca) para atualizar a imagem com base nos erros. Essa classe controla a exibição da forca no jogo.

O ImageView, como o próprio nome diz, é um componente que nos permite trabalhar com imagens.

switch, funciona Se um desses valores for igual ao valor da variável, o bloco de código do case em questão será executado.

setImageResource, define a imagem correta utilizando o método (setImageResource) da ImageView forca.



![26](https://github.com/marcosdasilvarodrigues/Jogo-Android-Studio/assets/105816659/c0265668-d36b-4041-902b-c7eb01f2f919)

![25](https://github.com/marcosdasilvarodrigues/Jogo-Android-Studio/assets/105816659/2501fa8b-6c4e-48fb-9b6d-d527347674d5)

![24](https://github.com/marcosdasilvarodrigues/Jogo-Android-Studio/assets/105816659/ae7d307c-2227-4234-b4c5-2f0aa3361d05)

![23](https://github.com/marcosdasilvarodrigues/Jogo-Android-Studio/assets/105816659/2d03194e-f512-4be0-8226-ad245084b603)

![22](https://github.com/marcosdasilvarodrigues/Jogo-Android-Studio/assets/105816659/135fec3c-9922-4092-a5e3-76408fc1e55d)

![21](https://github.com/marcosdasilvarodrigues/Jogo-Android-Studio/assets/105816659/203f8428-2f6f-4623-b8da-542f338e5341)



caminho Erro: br/ufpb/dcx/appalpha/control/ForcaController.java





Pontuação

![Pontuação tela 1](https://github.com/marcosdasilvarodrigues/Jogo-Android-Studio/assets/105816659/e59dae50-6fb3-4340-8a3c-22690fd101f1)



![pontuação tela 2 - Copia](https://github.com/marcosdasilvarodrigues/Jogo-Android-Studio/assets/105816659/40e47aab-a123-40a0-8647-623426ce79fe)

A classe Record tem dois atributos privados: nome (do tipo String) e pontuacao (do tipo double),
que representa o nome do jogador e a pontuação obtida. Ela possui um construtor que recebe o nome e a pontuação e os atribui aos atributos correspondentes.
Métodos de acesso (getNome e get Pontuação) para obter os valores dos atributos nome e pontuação.
A anotação @Override indica que o método compareTo está substituindo o método da interface Comparable.
O método compareTo compara o objeto atual (this) com outro objeto Record passado como parâmetro. Assim ele retorna um valor negativo (-1) se a pontuação do objeto atual for maior que a pontuação do outro objeto, retorna um valor positivo (1) se for menor e retorna zero se as pontuações forem iguais. Essa classe pode ser usada para armazenar registros de pontuação em uma lista e ordená-los com base na pontuação.

Caminho: java/br/ufpb/dcx/appalpha/model/bean/Record.java







Dica




![Dica 01](https://github.com/marcosdasilvarodrigues/Jogo-Android-Studio/assets/105816659/81e40465-7fc2-4efd-acb8-1b2323c530ef)




![dica 02](https://github.com/marcosdasilvarodrigues/Jogo-Android-Studio/assets/105816659/7c7f7463-7e0a-4131-927f-1edcbe1822c8)

A classe MockThemes implementa a interface Runnable e é usada para simular a inserção de temas e desafios dentro do banco de dados ou seja jogo de forca
Ela possui um atributo privado do tipo `ThemeSqlService` para interagir com o banco de dados.
O construtor recebe um contexto e inicializa o serviço.
A classe substitui o método "run" da interface "Runnable". Dentro do método "run", ele chama o método "insert" do objeto "service" com uma nova instância da classe "Theme" como primeiro argumento
O método "insert" é chamado com uma lista de objetos "Challenge" como segundo argumento.
Esses objetos são criados com diferentes nomes relacionados a alimentos ("arroz", "peixe", "batata", etc.), e assim como o objeto "Theme", eles também possuem IDs de recursos para um arquivo raw e um drawable associados a cada desafio.



Caminho: br/ufpb/dcx/appalpha/control/service/MockThemes.java







