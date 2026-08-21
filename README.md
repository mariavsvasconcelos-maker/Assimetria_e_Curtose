ASSIMETRIA E CURTOSE

Assimetria (Skewness)
A **assimetria** é a medida estatística que indica o grau de desvio ou deformação da distribuição de frequências de um conjunto de dados em relação à simetria em torno da sua média. 

Em palavras simples, enquanto a média nos dá o centro geométrico e o desvio padrão mede a dispersão dos dados, a assimetria revela para qual dos lados a "cauda" do gráfico está sendo esticada.

Curtose (Kurtosis)
A **curtose** é a medida estatística que quantifica a "concentração de pico" (o quão afunilado é o topo) e o "peso das caudas" (tail-heaviness) de uma distribuição em comparação com a curva Normal. 

Em palavras simples, a curtose nos diz se os eventos extremos (outliers) acontecem com mais ou menos frequência do que o esperado em uma curva gaussiana.

Primeiro Bloco: O que é

A assimetria mede o grau de distorção ou a falta de simetria no formato de uma distribuição de dados em relação ao seu ponto central. A pergunta principal que a assimetria responde é sobre a tendência de concentração dos dados, ou seja, para qual lado do gráfico os valores estão pendendo.

A curtose mede o grau de achatamento do pico da distribuição e a intensidade das suas caudas em comparação com uma distribuição normal. A pergunta principal que a curtose responde é sobre a probabilidade de ocorrência de valores extremamente afastados da média, conhecidos como eventos raros ou outliers.

Segundo Bloco: Como se interpreta

Em relação à assimetria, quando ela é positiva, a cauda mais longa do gráfico está do lado direito e a maioria dos dados concentra-se do lado esquerdo, representando valores menores. Quando ela é negativa, a cauda mais longa está do lado esquerdo e a maioria dos dados concentra-se do lado direito, representando valores maiores. Quando a distribuição é simétrica, os dois lados em relação ao centro são perfeitamente espelhados.

Em relação à curtose, o termo leptocúrtica indica uma distribuição com pico elevado e caudas pesadas, sinalizando maior chance de eventos extremos. O termo mesocúrtica representa o comportamento padrão de uma distribuição normal. O termo platicúrtica indica uma distribuição de pico achatado e caudas leves, com dados mais espalhados e menor chance de ocorrência de valores discrepantes.

Terceiro Bloco: Para que serve

A identificação de assimetria ou caudas pesadas impacta decisões práticas. Na gestão de risco, reconhecer uma distribuição leptocúrtica impede que analistas considerem eventos catastróficos como impossíveis, o que exige um ajuste para cima no provisionamento de capital de segurança. Na escolha de métricas, em distribuições muito assimétricas, a média deixa de ser confiável por sofrer distorção de valores extremos, sendo substituída pela mediana como referência principal. Na modelagem estatística, o formato dos dados determina se será necessário aplicar transformações matemáticas antes de utilizar algoritmos de inteligência artificial ou testes que exigem normalidade.

Quarto Bloco: Onde aparece no mercado

No mercado financeiro, o retorno de investimentos costuma apresentar assimetria negativa e curtose elevada com caudas pesadas. Avaliar apenas o retorno médio de uma carteira falha porque esconde o risco latente de quedas bruscas e perdas extremas em momentos de crise.

Na distribuição de renda populacional, observa-se uma forte assimetria positiva, onde a maior parte da população ganha salários mais baixos e um grupo muito reduzido ganha valores extremamente elevados. A média salarial falha nesse cenário porque é puxada para cima pela renda dos bilionários, transmitindo a falsa ideia de que o poder aquisitivo geral da população é alto. A mediana é a métrica adequada nesse contexto.

Quinto Bloco: A ligação com tendência central

O formato da distribuição altera a posição relativa entre média, mediana e moda. Em uma distribuição com assimetria positiva, os valores altos da cauda longa puxam a média para a direita, fazendo com que a moda fique no pico com o menor valor, a mediana fique no centro e a média assuma o maior valor. Em uma distribuição simétrica, a média, a mediana e a moda coincidem no mesmo valor central. Em uma distribuição com assimetria negativa, os valores muito baixos da cauda esquerda puxam a média para baixo, fazendo com que a média tenha o menor valor, a mediana fique no centro e a moda tenha o maior valor no pico da curva.

Sexto Bloco: Onde os dois modelos divergiram

Durante a comparação entre os dois modelos de inteligência artificial consultados, identificou-se uma divergência em relação ao valor numérico da curtose na distribuição normal. O primeiro modelo afirmou que a curtose da distribuição normal é igual a três. O segundo modelo afirmou que a curtose da distribuição normal é igual a zero. Ao verificar em literatura estatística adicional, constatou-se que ambas as respostas estão corretas, pois o primeiro modelo utilizou a convenção da curtose bruta e o segundo modelo utilizou a convenção do excesso de curtose, na qual se subtrai o valor três para padronizar a distribuição normal em zero, padrão adotado por bibliotecas de programação estatística.
