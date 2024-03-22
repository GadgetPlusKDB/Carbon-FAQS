# Ajustar posição do material

<figure markdown="span">
  
  ![](../images/construcao-light.png#only-light){ width="610" }
  <figcaption></figcaption>

  ![](../images/construcao-dark.png#only-dark){ width="610" }
  <figcaption></figcaption>
  
</figure>

Aqui vamos explorar um passo essencial para garantir o sucesso dos nossos cortes: o posicionamento do desenho no material. Para isso, é crucial compreender o funcionamento do painel de controle no Carbon Studio. Que tal dar uma olhada a esse artigo da nossa série sobre o [Studio]?

Já se sente confortável em operar a máquina? Então vamos para o próximo passo!

[Studio]: https://gadgetpluskdb.github.io/Carbon-FAQS/studio/primeiros-passos/comando-movimento/

Ajustando o desenho na área de trabalho do Carbon Studio
Independentemente se o desenho foi criado dentro do Carbon Studio ou importado de outro software, é necessário posicioná-lo na posição zero dentro do software.

* Selecione os elementos que deseja cortar. A posição em relação aos eixos X e Y é indicada nas caixas destacadas na Figura 1.

<figure markdown="span">

  ![FrenteMaq](../images/image-placeholder.png){ width="450" }
  <figcaption></figcaption>

</figure>

Figura 1 - Desenhos em local aleatório da área de trabalho

* Ajuste a posição dos desenhos para X=0 e Y=0. Isso moverá os elementos selecionados para a posição zero dentro do software.

<figure markdown="span">

  ![FrenteMaq](../images/image-placeholder.png){ width="450" }
  <figcaption></figcaption>

</figure>

Figura 2 - Desenhos na posição zero DS

O Carbon Studio reconhece o canto superior esquerdo como ponto inicial.

## Definindo o ponto inicial de corte na Carbon

Para que a máquina saiba de onde iniciar o corte, é necessário definir o ponto inicial.

* Movimente o cabeçote do laser com as setas no painel de controle.

<figure markdown="span">

  ![FrenteMaq](../images/image-placeholder.png){ width="450" }
  <figcaption></figcaption>

</figure>

Figura 1 - Movimentação cabeçote laser setas

* Escolha o local onde deseja iniciar o corte. Para otimizar o uso do material, posicione-o no canto superior esquerdo.

<figure markdown="span">

  ![FrenteMaq](../images/image-placeholder.png){ width="450" }
  <figcaption></figcaption>

</figure>

Figura 2 - Posicionamento do cabeçote no material 

* Considerando a posição do bico do laser, clique em "definir início" no painel de controle.

<figure markdown="span">

  ![FrenteMaq](../images/image-placeholder.png){ width="450" }
  <figcaption></figcaption>

</figure>

Figura 3 - Definir início

## Criando referências

Ao fazer esses ajustes de posicionamento, estabelecemos uma relação entre a posição do desenho no material e o início do corte: o ponto zero do desenho coincide com o ponto de início do corte!

A máquina considera sempre como ponto inicial a última definição realizada. Portanto, se mover o cabeçote do laser para uma nova posição e iniciar um novo corte, ele retornará ao ponto definido anteriormente! Defina sempre o ponto de início no software (Figura 3).

## Verificando o posicionamento do desenho no material

Para garantir o melhor aproveitamento da área de trabalho, é importante conhecer o espaço que o desenho ocupará no material. Para isso, utilizamos o recurso "Frame".

* Selecione os elementos do desenho que deseja verificar e clique em "preview > frame", conforme indicado na Figura 4.

<figure markdown="span">

  ![FrenteMaq](../images/image-placeholder.png){ width="450" }
  <figcaption></figcaption>

</figure>

Figura 4 - Preview > Frame

!!! note "Obeservação"

    Com a nova atualização do Carbon Studio, o recurso frame do painel de controle foi desativado! Portanto, a máquina não responderá mais ao comando de frame feito pela barra de controle.

<figure markdown="span">

  ![FrenteMaq](../images/image-placeholder.png){ width="450" }
  <figcaption></figcaption>

</figure>

Figuras 5 - Recurso Preview - Barra de controle    

Para usar o frame, você deve ir em "preview > frame", conforme mencionado acima.

* O recurso de frame facilita a utilização de retalhos de material, pois permite verificar se o desenho caberá no espaço desejado.

<figure markdown="span">

  ![FrenteMaq](../images/image-placeholder.png){ width="450" }
  <figcaption></figcaption>

</figure>

Figura 6 - Aproveitamento de retalhos utilizando frame

## Tamanho do desenho vs. área de trabalho da Carbon.

É crucial lembrar que o tamanho do objeto não pode exceder a área de trabalho da máquina, que é de 600mm de comprimento por 400mm de largura. Caso isso ocorra, seu trabalho não será executado corretamente e/ou o cabeçote do laser começará a bater nas laterais da máquina, emitindo um ruído indicando que está forçar o motor. Portanto, verifique sempre o tamanho do desenho na área de trabalho usando o recurso "frame".

Neste artigo, exploramos como posicionar o desenho no material para otimizar nosso trabalho! Acompanhe-nos no próximo artigo, onde explicaremos como definir a [velocidade e potência] da máquina.

[velocidade e potência]: https://gadgetpluskdb.github.io/Carbon-FAQS/manual/primeiros-trabalhos/velocidade-potencia/
