**Descrição do programa**


Este aplicativo java se destina a calcular o alargamento e os esforços (força, torque e potência) de uma sequência de passes de laminação.
O usuário informa o tipo de aço laminado, o método de cálculo de alargamento e esforços, e se o trem é aberto ou contínuo.
No caso de trem aberto o usuário informa a rotação do cilindro em cada passe. O sistema calcula a velocidade e a produção horária.
No caso de trem contínuo, informa-se a produção horária. As rotações e velocidades serão calculadas em cada passe.


A seguir seleciona-se o tipo de seção de entrada (chato, redondo, oval ou losângo) e suas dimensões. 
Seleciona-se então o tipo de canal do primeiro passe (caixa, redondo. oval ou losângo).
Entra-se então com todas as informações do passe, a começar pelas dimensões do canal. 
Se a seção é suposta entrar no canal girada de 45 ou 90 graus informar esse ângulo. O defaut é zero.
O fator de alargamento é 1, a menos que o usuário tenha uma informação melhor para o caso específico.


Após a exibição dos resultados, tais como o alargamento e os esforços, seleciona-se a opção *mais um passe*.
Repete-se então para o passe seguinte o descrito acima, sendo que a seção calculada do primeiro passe será considerada a seção de entrada para o segundo, e assim por diante. Atenção para o ângulo de giro. É frequente numa sequência de passes que o sentido da laminação seja girado em 90 graus.

Quando todos os passes desejados forem calculados, anota-se os resultados. O programa não imprime ou salva.

Para rodar em linux, digita-se no terminal: *java -jar calibracao.jar*, com o diretório onde está esse arquivo tendo sido previamente selecionado. No windows, pode-se fazer o mesmo no equivalente ao terminal (prompt de comando). Ou simplesmente usar o lado direito do mouse e *abrir como* um aplicativo java.

Os arquivos fonte estão em *calibracaoFonte.zip*
