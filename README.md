#Top 250 Kdramas EDA 

## Introdução

O objetivo deste notebook foi analisar um dataset contendo informações sobre os 250 melhores kdramas , a fim de identificar as características mais comuns desses dramas e utilizar essas informações para ajudar dois produtores de kdramas com objetivos diferentes: um que busca criar um dos melhores kdramas já vistos(Hardcore), e outro que busca criar um kdrama que venda bem(Money).

<iframe src="https://giphy.com/embed/ZdAOatkOA7Q13ENNWz" width="480" height="244" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>
## Análise do Dataset

Com base na análise dos dados, podemos destacar as seguintes características mais comuns dos top 250 kdramas:

    O rating mediano é de 8.5;
    
    GRAFICO 1
    A restrição de idade mais comum é 15+;
    
    GRAFICO 2
    A maioria desses kdramas possui entre 16 e 20 episódios;
    
    GRAFICO 3
    
    A duração média do episódio é de 60 a 70 minutos;
    
    GRAFICO 4
    
    A maioria desses kdramas vai ao ar 2 vezes por semana;
    
    GRAFICO 5
    
    Os dias mais comuns para que os kdramas vão ao ar são sábado e quarta-feira (não combinados);
    
    GRAFICO 6
    
    Os top 5 gêneros mais comuns entre os kdramas são romance, drama, comédia, mistério e suspense, do mais comum para o menos.
    
    GRAFICO 7

Além disso, foi possível observar que aparentemente nenhuma dessas variáveis parece ter um efeito significativo no rating, com exceção da restrição de idade. Foi possível notar que, à medida que a restrição de idade diminui, o rating parece subir (por exemplo, 18+ tem um rating mediano maior do que 15+), apesar da grande diferença de N.

    GRAFICO 8

## Sugestões para os Produtores

Antes de falarmos sobre os produtores, é importante mencionar que, como apenas as análises bivariadas com o rating não foram suficientes, decidi olhar as relações com a restrição de idade para tomar algumas decisões, já que aparentemente ela estava relacionada com o rating.

Produtor "Money"

Para atingir seu objetivo de criar um kdrama que venda bem, o produtor "Money" pode utilizar kdramas de referência com as seguintes características:

    Rating: Pelo menos 8.3;
    Restrição de idade: 15+;
    Número de episódios: Até 16 ou entre 16 e 20 episódios;
    Duração do episódio: Entre 60 e 65 minutos ou mais que 70 minutos;
    Número de Dias: 2 vezes por semana;
    Dias: Sábado e domingo;
    Gênero: Escolher algo do top 5 (Drama, Romance, Mistério, Suspense ou Comédia).

Alguns exemplos de kdramas com essas características são "Flower of Evil" (#2), "My Mister" (#5) e "Prison Playbook" (#8).

Para atingir seu objetivo de criar um dos melhores kdramas já vistos, o produtor "Hardcore" deve buscar produzir um kdrama 18+, que permite mais liberdade de conteúdo, e que possua as seguintes características:

    Rating: Pelo menos acima 8.5, preferencialmente 8.7;
    Restrição de idade: 18+;
    Número de episódios: Até 16 episódios;
    Duração do episódio: Até 60 minutos;
    Número de dias: 1 vez por semana;
    Dias: Sexta-feira;
    Gênero: Drama e suspense são ótimas escolhas.
    
Alguns exemplos de kdramas com essas características: **Move to Heaven(#1), Weak Hero Class 1 (#7), Kingdom: Season 2 (#20)**
