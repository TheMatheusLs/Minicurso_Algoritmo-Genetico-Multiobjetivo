# Minicurso de Algoritmo Genético

Minicurso de Algoritmo Genético ministrado na pelo professor [Matheus Lôbo dos Santos](http://matheuslobo.com) no evento [bsiconnects](https://www.instagram.com/bsiconnects/).

Licença: Fique a vontade para utilizar o material para fins acadêmicos. Caso utilize o material, por favor, referencie esse repositório.

## Apresentação

A apresentação do minicurso em formato PDF pode ser encontrada na pasta `Apresentação`. Realize a leitura do arquivo para entender o funcionamento do algoritmo genético. O material foi preparado para ser apresentado em 1 hora, portanto, não é um material completo sobre o assunto. Ele aborda apenas o básico para que você possa entender o funcionamento do algoritmo genético aplicado ao problema do caixeiro viajante.

### Resolução do problema do caixeiro viajante

O problema do caixeiro viajante é um problema clássico da computação. Ele consiste em encontrar o menor caminho que um caixeiro viajante deve percorrer para visitar todas as cidades de um conjunto de cidades e retornar ao ponto de partida. O problema é NP-Completo, ou seja, não existe um algoritmo que resolva o problema em tempo polinomial. Portanto, a solução exata do problema é inviável para um número grande de cidades. Uma solução aproximada pode ser obtida através de um algoritmo genético.

Na figura abaixo é possível observar uma solução inicial aleatória para o problema do caixeiro viajante. A solução é representada por um conjunto de cidades (pontos) e um caminho que o caixeiro viajante deve percorrer (linha). A solução inicial não é a melhor solução, pois o caminho percorrido pelo caixeiro viajante é muito longo.

<h13 align="center">
  <p align="center">Solução Aleatória</p>
  <a><img src="https://github.com/TheMatheusLs/Minicurso_Matheus/blob/main/Apresenta%C3%A7%C3%A3o/img/Solu%C3%A7%C3%A3o1.png" alt="Solução 1"></a>
</h3>

Através de um algoritmo genético é possível encontrar uma solução melhor para o problema. A solução encontrada pelo algoritmo genético é representada na figura abaixo. É possível observar que o caminho percorrido pelo caixeiro viajante é menor do que o caminho percorrido na solução inicial.

<h3 align="center">
  <p align="center">Solução Final</p>
  <a><img src="https://github.com/TheMatheusLs/Minicurso_Matheus/blob/main/Apresenta%C3%A7%C3%A3o/img/Solu%C3%A7%C3%A3oFinal.png" alt="Solução Final"></a>
</h3>

## Código

O código do algoritmo genético pode ser encontrado na pasta `Códigos`. O código foi escrito em Python 3.11.5. Para executar o código é necessário instalar as bibliotecas `matplotlib`. Para instalar as bibliotecas execute os seguintes comandos:

```bash
pip install matplotlib
```

Proponho o seguinte exercício: acesse o código do Jupyter Notebook na versão `Aluno` e preencha os campos que estão faltando. O código está todo comentado, portanto, você não terá dificuldades para preencher os campos. O código do Jupyter Notebook na versão `Completo` funcional e pode ser utilizado como referência.

### Desafio

Escreva um código para resolver o problema do caixeiro viajante para 10 cidades utilizando força bruta, ou seja, testando todas as opções (Pode manter a velocidade mínima e máxima iguais). Compare o tempo de execução do algoritmo genético com o tempo de execução do algoritmo de força bruta e tire suas conclusões.

### Agradecimentos

[Tutorials with Gary](https://www.youtube.com/@TutorialsWithGary/videos)  pelas imagens e ideia do problema para a aplicação.

# Redes Sociais

<p align="left">
<a href="https://twitter.com/thematheusls" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="thematheusls" height="30" width="40" /></a>
<a href="https://telegram.me/thematheusls" target="blank"><img align="center" src="https://upload.wikimedia.org/wikipedia/commons/8/83/Telegram_2019_Logo.svg" alt="thematheusls" height="30" width="40" /></a>
<a href="https://linkedin.com/in/matheus-lobo-dos-santos" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="matheus-lobo-dos-santos" height="30" width="40" /></a>
<a href="https://instagram.com/thematheusls" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="thematheusls" height="30" width="40" /></a>
<a href="https://www.youtube.com/c/thematheusls" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="thematheusls" height="30" width="40" /></a>
</p>

