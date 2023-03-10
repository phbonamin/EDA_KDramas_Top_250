# EDA  dos Top 250 Kdramas no MyDramaList 🎬

## ❔ Sobre o projeto

O objetivo deste projeto foi analisar um dataset contendo informações sobre os 250 melhores kdramas ,segundo a <a href = "https://mydramalist.com"> MyDramaList </a> , a fim de identificar as características mais comuns desses dramas e utilizar essas informações para ajudar dois produtores de kdramas com objetivos diferentes: um que busca criar um dos melhores kdramas já vistos (Hardcore), e outro que busca criar um kdrama que venda bem(Money).

Para a mesma foi utilizado o dataset disponível no Kaggle.

Clique <a href  = "https://www.kaggle.com/datasets/ahbab911/top-250-korean-dramas-kdrama-dataset" >aqui</a> caso queira acessá-lo. 

Vamos então ver quais foram os principais destaques e as conclusões dessa análise!

![Couple Kdrama Gif](https://media.giphy.com/media/ZdAOatkOA7Q13ENNWz/giphy.gif)

## 📊 Análise do Dataset 

Considerando **maioria = >50%.**

Vamos destacar as **caracteristicas mais comums** dos **top 250 kdramas**:

 **O rating mediano  é de 8.5** ⭐
 <table>
 
 <tr>
 <td rowspan="9"><img src="imagens/Grafico1.png" alt="Grafico1"/></td>
 <td> <b>Count</b> : 250.000000 </td>


 </tr>
 <tr>

 <td><b>Mean</b> : 8.534000</td>


</tr>
<tr>

<td><b>STD</b> : 0.221359</td>

</tr>

 <tr>

<td><b>Min</b> : 8.300000</td>

</tr>

 <tr>

<td><b>25%</b> : 8.300000</td>

</tr>

 <tr>

<td><b>50%</b> : 8.500000</td>

</tr>

 <tr>

<td><b>75%</b> : 8.700000</td>

</tr>
 <tr>

<td><b>Max</b> : 9.200000</td>

</tr>

</table>



 **A restrição de idade mais comum é 15+** 📛

<img src="imagens/Grafico2.png" alt="Grafico2">

 **A maioria desses kdramas possui entre 16 e 20 episódios** 📺
 
<table>
 
 <tr>
 <td rowspan="9"><img src="imagens/Grafico3.png" alt="Grafico3"/></td>
 <td> <b>Count</b> : 250.000000 </td>


 </tr>
 <tr>

 <td><b>Mean</b> : 19.064000</td>


</tr>
<tr>

<td><b>STD</b> : 13.245743</td>

</tr>

 <tr>

<td><b>Min</b> : 1.000000</td>

</tr>

 <tr>

<td><b>25%</b> : 16.000000</td>

</tr>

 <tr>

<td><b>50%</b> : 16.000000</td>

</tr>

 <tr>

<td><b>75%</b> : 20.000000</td>

</tr>
 <tr>

<td><b>Max</b> : 133.000000</td>

</tr>

</table>


**A maior parte desses kdramas possui uma duração de episódio de 60 a 70 minutos** ⏱️ 

<table>
 
 <tr>
 <td rowspan="9"><img src="imagens/Grafico4.png" alt="Grafico4"/></td>
 <td> <b>Count</b> : 250.000000 </td>
 </tr>
 <tr>
 <td><b>Mean</b> : 62.408000</td>
</tr>
<tr>
<td><b>STD</b> : 14.957018</td>
</tr>
 <tr>
<td><b>Min</b> : 15.000000</td>
</tr>
 <tr>
<td><b>25%</b> : 60.000000</td>
</tr>
 <tr>
<td><b>50%</b> : 65.000000</td>
</tr>
 <tr>
<td><b>75%</b> : 70.000000</td>
</tr>
 <tr>
<td><b>Max</b> : 100.000000</td>
</tr>
</table>

**A maioria desses kdramas vai ao ar 2 vezes por semana.** 📅 

<img src="imagens/Grafico5.png" alt="Grafico5">

 **Os dias mais comuns para que os kdramas vão ao ar é de Sábado e Quarta(Não combinados).** 📅

<img src="imagens/Grafico6.png" alt="Grafico6">

 **Os top 5 generos mais comuns entre os kdramas são: Romance, Drama, Comédia, Mistério e Suspense ( Do mais comum para o menos)** 🎭
 
<img src="imagens/Grafico7.png" alt="Grafico7">

Além disso, foi possível observar que aparentemente nenhuma dessas variáveis parece  ter um efeito significativo no rating, com exceção da restrição de idade. Foi possível notar que, **à medida que a restrição de idade aumenta, o rating parece subir (por exemplo, 18+ tem um rating mediano maior do que 15+)**, apesar da grande diferença de N. (Futuramente um teste de hipóteses pode ser feito para confirmar essa tendência)

<img src="imagens/Grafico8.png" alt="Grafico8">

Antes de falarmos sobre os produtores, é importante mencionar que, como apenas as análises bivariadas com o rating não foram suficientes, decidi olhar as relações com a restrição de idade para tomar algumas decisões, já que aparentemente ela estava relacionada com o rating. 

Primeiro analisei como **quantos dias que os kdramas vão ao ar influenciam na restrição de idade e no rating.**

<img src="imagens/Grafico9.png" alt="Grafico9">

<img src="imagens/Grafico10.png" alt="Grafico10">

Depois tranformei a variaveis de duração e número de episódios em variávies categóricas para que pudesse compara-las com a restrição de idade junto com o rating.

**Numero de episódios**
<table>
<tr>
<td><img src="imagens/Grafico11.png" alt="Grafico11"></td> <td><img src="imagens/Grafico12.png" alt="Grafico12"></td>  
 </tr>
</table>
<img src="imagens/Grafico13.png" alt="Grafico13">

**Duração**

<table>
<tr>
<td><img src="imagens/Grafico14.png" alt="Grafico14"></td> <td><img src="imagens/Grafico15.png" alt="Grafico15"></td>  
 </tr>
</table>
<img src="imagens/Grafico16.png" alt="Grafico16">


Além disso, com essas características já definidas, defini também os dias da semana e os generos dos kdramas que eles poderiam se basear.

**Money**

**Dias**

<img src="imagens/Grafico17.png" alt="Grafico17">

**Genero**

<img src="imagens/Grafico19.png" alt="Grafico19">

**Hardcore**

**Dias**

<img src="imagens/Grafico18.png" alt="Grafico18">

**Genero**

<img src="imagens/Grafico20.png" alt="Grafico20">

Ao termino dessas analises, filtrei as características que achei desejável para cada produtor segundo seus requerimentos e os resultados foram os abaixo.

## 💡 Sugestões para os Produtores

### 💰 Produtor "Money"

Para atingir seu objetivo de criar um kdrama que venda bem, o produtor "Money" pode utilizar kdramas de referência com as seguintes características:

    Rating: Pelo menos 8.3; ⭐
    Restrição de idade: 15+; 📛
    Número de episódios: Até 16 ou entre 16 e 20 episódios;📺
    Duração do episódio: Entre 60 e 65 minutos ou mais que 70 minutos; ⏱️ 
    Número de Dias: 2 vezes por semana; 📅
    Dias: Sábado e domingo; 📅
    Gênero: Escolher algo do top 5 (Drama, Romance, Mistério, Suspense ou Comédia). 🎭

Alguns exemplos de kdramas com essas características são **"Flower of Evil" (#2)**, **"My Mister" (#5)** e **"Prison Playbook" (#8)**.

### 💪 Produtor "Hardcore"

Para atingir seu objetivo de criar um dos melhores kdramas já vistos, o produtor "Hardcore" assumi que ele deve utilizar uma restrição de idade de 18+, que permite mais liberdade de conteúdo, e que possua as seguintes características:

    Rating: Pelo menos acima 8.5, preferencialmente 8.7; ⭐
    Restrição de idade: 18+; 📛
    Número de episódios: Até 16 episódios; 📺
    Duração do episódio: Até 60 minutos;  ⏱️ 
    Número de dias: 1 vez por semana; 📅
    Dias: Sexta-feira; 📅
    Gênero: Drama e suspense são ótimas escolhas. 🎭
    
Alguns exemplos de kdramas com essas características: **Move to Heaven(#1), Weak Hero Class 1 (#7), Kingdom: Season 2 (#20)**
