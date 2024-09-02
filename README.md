# [Formação_Alura_Data_Science](https://cursos.alura.com.br/formacao-data-science)

# [Curso_Alura_Data_Visualization_criando_gr-ficos_com_bibliotecas_Python](https://cursos.alura.com.br/course/data-visualization-graficos-bibliotecas-python)

Este repositório tem como objetivo fazer parte da minha trajetória em busca de conhecimento em Ciência de Dados, onde escolhi a [Alura](https://www.alura.com.br/) como uma das minhas fontes de aprendizado.

## 1. Conhecendo a biblioteca Matplotlib
Nessa aula, aprendi a:
- Extrair uma série de dados de um DataFrame;
- Importar o módulo pyplot da biblioteca Matplotlib;
- Plotar um gráfico com a biblioteca Matplotlib;
- Alterar os ticks dos eixos X e Y;
- Exibir o gráfico com a função plt.show();
- Modificar o tamanho do gráfico;
- Adicionar um título ao gráfico;
- Adicionar rótulos aos eixos X e Y.

Clique [aqui](./Modulos/01_Conhecendo_a_biblioteca_Matplotlib.ipynb) para acessar o Módulo 1.

## 1.1. Desafio 01 - Comparando tendências de imigração
Criar um gráfico de linhas comparando os números de imigrantes do Brasil e Argentina para o Canadá, que são os maiores países da América do Sul.

Nessa missão, a elaboração desse gráfico pode ser útil para a compreensão das tendências migratórias desses países para o Canadá ao longo do tempo e como elas se comparam entre si. Ao analisar esses fatores, podemos obter uma visão mais abrangente do cenário migratório na América do Sul.

Essa nova tarefa é mais desafiadora, pois exige uma análise comparativa entre dois países. No entanto, ela também permitirá com que você obtenha uma aprendizagem enriquecedora. Por isso, explore as diversas possibilidades e lembre-se dos elementos essenciais de um gráfico: título, rótulos nos eixos x e y e os ticks do eixo x, que devem ser definidos de 5 em 5 anos.

Além disso, você precisará descobrir como adicionar uma legenda para que seja possível identificar a linha de cada país. Ao seguir essas orientações, você terá construído um gráfico robusto que te permitirá uma análise significativa e aprofundada.

Após criar o gráfico analise o resultado obtido e reflita nas seguintes questões:

Há alguma tendência ou padrão comum nos dados dos dois países?
Quais são os períodos com maior número de imigrantes nos dois países?

Clique [aqui](./Modulos/Desafio_1_Desafio_comparando_tendências_de_imigração.ipynb) para acessar o Desafio 01.

## 2. Criando figuras com Matplotlib
Nessa aula, aprendi a:
- Criar uma figura;
- Modificar a frequência dos ticks do eixo X em uma figura;
- Adicionar título e os rótulos dos eixos em uma figura;
- Criar uma figura contendo subplots em uma direção;
- Criar uma figura contendo subplots em duas direções;
- Modificar o espaçamento entre subplots;
- Compreender como diferentes escalas no eixo Y podem causar distorções na interpretação dos resultados;
- Aplicar a mesma escala no eixo Y em uma figura contendo subplots;
- Criar um título geral em uma figura contendo subplots.

Clique [aqui](./Modulos/02_Criando_figuras_com_Matplotlib.ipynb) para acessar o Módulo 2.

## 2.2. Desafio 02 - Visualizando dados de vendas de diferentes lojas
Você trabalha como Analista de Dados em uma empresa de varejo e recebeu a tarefa de criar uma figura com subplots que apresente a variação no número de vendas em quatro diferentes lojas ao longo de um ano. A gerência da empresa precisa visualizar de forma clara as tendências de vendas em cada loja, para que possam tomar decisões estratégicas sobre os estoques e ações de marketing. Para isso, você deve criar quatro subplots dispostos em duas linhas e duas colunas, onde cada subplot representa uma loja diferente. Nesse desafio, cada subplot deve apresentar um gráfico de linhas que mostre a variação do número de vendas ao longo dos meses do ano.

Agora, chegou a hora de mostrar suas habilidades em análise de dados e visualização! Para criar o DataFrame com o número de vendas das lojas e criar a figura, utilize as informações abaixo:

```
lojas = ['A', 'B', 'C', 'D']

vendas_2022 = {'Jan': [100, 80, 150, 50],
    'Fev': [120, 90, 170, 60],
    'Mar': [150, 100, 200, 80],
    'Abr': [180, 110, 230, 90],
    'Mai': [220, 190, 350, 200],
    'Jun': [230, 150, 280, 120],
    'Jul': [250, 170, 300, 140],
    'Ago': [260, 180, 310, 150],
    'Set': [240, 160, 290, 130],
    'Out': [220, 140, 270, 110],
    'Nov': [400, 220, 350, 190],
    'Dez': [300, 350, 400, 250]
}
```
Clique [aqui](./Modulos/Desafio_2_Desafio_visualizando_dados_de_vendas_de_diferentes_lojas.ipynb) para acessar o Desafio 02.

## 3. Customizando com Matplotlib
Nessa aula, aprendi a:
- Modificar o tamanho das fontes do título e rótulos dos eixos;
- Modificar a posição do título;
- Alterar a espessura da linha;
- Adicionar marcadores à linha do gráfico;
- Adicionar grades ao fundo do gráfico;
- Alterar a cor de apenas uma variável;
- Alterar as cores quando temos várias categorias;
- Criar um gráfico de barras horizontal;
- Destacar informações em um gráfico;
- Adicionar anotações em texto;
- Retirar o quadro envolta do gráfico e deixá-lo mais limpo;
- Salvar as figuras.

Clique [aqui](./Modulos/03_Customizando_com_Matplotlib.ipynb) para acessar o Módulo 3.

## 3.3. Desafio 03 - Customizando os subplots com dados de vendas de diferentes lojas
Nesta segunda parte do desafio, você deve explorar as opções de customização dos subplots para deixar a figura mais clara e atraente para a gerência da empresa.

Algumas ideias de customização que você pode explorar são:

Alterar a posição dos títulos dos subplots para esquerda.
Aumentar o tamanho da fonte do título geral da figura para destacá-lo.
Aumentar o tamanho dos títulos e rótulos dos eixos dos subplots.
Deixar as linhas com a espessura maior.
Alterar a cor das linhas de cada loja para diferenciá-las ainda mais.
Fique à vontade para testar mais customizações!

E mais uma dica: você pode reduzir o tamanho do código utilizando o comando for i, ax in enumerate(axs.flat): que permite um loop iterando sobre todos os subplots da figura. Dentro desse loop você pode passar as funções plot, set_title, set_xlabel, set_ylabel e etc…

Lembrando que os dados são os seguintes:

```
lojas = ['A', 'B', 'C', 'D']

vendas_2022 = {'Jan': [100, 80, 150, 50],
    'Fev': [120, 90, 170, 60],
    'Mar': [150, 100, 200, 80],
    'Abr': [180, 110, 230, 90],
    'Mai': [220, 190, 350, 200],
    'Jun': [230, 150, 280, 120],
    'Jul': [250, 170, 300, 140],
    'Ago': [260, 180, 310, 150],
    'Set': [240, 160, 290, 130],
    'Out': [220, 140, 270, 110],
    'Nov': [400, 220, 350, 190],
    'Dez': [300, 350, 400, 250]
}

# Criando DataFrame
df = pd.DataFrame(vendas_2022, index=lojas)
```
Clique [aqui](./Modulos/Desafio_3_Desafio_customizando_os_subplots_com_dados_de_vendas_de_diferentes_lojas.ipynb) para acessar o Desafio 03.

## 4. Conhecendo a biblioteca Seaborn
Nessa aula, aprendi a:
- Importar a biblioteca Seaborn;
- Definir o tema padrão da biblioteca Seaborn;
- Criar um gráfico de barras na vertical e horizontal;
- Adicionar título e rótulos nos eixos;
- Utilizar as bibliotecas Seaborn e Matplotlib em conjunto;
- Alterar as cores utilizando paletas;
- Explorar diferentes temas;
- Remover as bordas de um gráfico com a função sns.despine().

Clique [aqui](./Modulos/04_Conhecendo_a_biblioteca_Seaborn.ipynb) para acessar o Módulo 4.

## 4.4. Desafio 04 - Criando um gráfico de linhas com a biblioteca Seaborn
Nesta etapa, seu desafio é criar uma figura contendo as tendências de imigração dos 4 maiores países da América latina: Brasil, Argentina, Peru e Colômbia. Através dessa criação você pode explorar diversas possibilidades e reconhecer de forma atrativa o seu processo de desenvolvimento.E não nos esqueçamos das orientações! Essa figura precisa ter uma linha para cada país, título, rótulos nos eixos, cores apropriadas, um tema da biblioteca Seaborn e legenda. Por isso, pense nas questões de acessibilidade, como tamanho das fontes e espessura das linhas. É importante escolher cores adequadas que não causem cansaço visual ou dificultem a leitura das informações. Além disso, o tamanho das fontes deve ser legível o suficiente para que as pessoas possam interpretar os dados com facilidade.

Dica: para escolher a paleta de cores, você também pode consultar a documentação da biblioteca Matploltib. A Seaborn utiliza as colormaps do Matplotlib por padrão, além de oferecer suas próprias paletas de cores. Para aplicar uma paleta de cores a todas as linhas da figura você pode usar a função sns.set_palette() e passar a ela o nome da paleta escolhida.

Clique [aqui](./Modulos/Desafio_4_Desafio_criando_um_gráfico_de_linhas_com_a_biblioteca_Seaborn.ipynb) para acessar o Desafio 04.

## 5. Gráficos interativos com Plotly
Nessa aula, aprendi a:
- Importar o módulo express da biblioteca Plotly;
- Criar um gráfico de linhas interativo;
- Explorar as funcionalidades da biblioteca Plotly;
- Modificar o tamanho de um gráfico interativo;
- Rotacionar os ticks do eixo X;
- Adicionar título e rótulos nos eixos;
- Personalizar os gráficos;
- Alterar cores;
- Adicionar marcadores;
- Salvar gráficos interativos no formato HTML.

Clique [aqui](./Modulos/05_Gráficos_interativos_com_Plotly.ipynb) para acessar o Módulo 5.

## Desafio 05 - Criando uma animação para comparar diferentes dados
Lembra que nós criamos uma figura estática contendo os dados de imigração do Brasil e Argentina? Sua tarefa é criar um gráfico animado com o Plotly que mostre esses dados. O gráfico deve ter as seguintes características:

Duas linhas: uma para o Brasil e outra para a Argentina.
Um botão "Play" para iniciar a animação, mostrando o aumento ou diminuição do número de imigrantes ao longo dos anos.
As configurações de animação devem fazer com que as duas linhas sejam exibidas e animadas ao mesmo tempo.
Dicas:

Crie um DataFrame com os dados da Argentina e não se esqueça de deixar a coluna de anos no tipo int(inteiro).
Use o código fornecido para o Brasil como base e adapte-o para incluir os dados da Argentina.
Para configurar as animações você pode fazer um Loop for para percorrer o DataFrame dados_brasil e para cada iteração, criar uma nova lista contendo dois objetos do tipo go.Scatter, um para cada país. Em seguida, cada lista pode ser usada para criar um objeto go.Frame, que é adicionado à lista de frames. Por fim, a lista de frames pode ser atribuída ao objeto fig, que é a figura do gráfico a ser animado. Com isso, quando a animação for iniciada, o gráfico exibirá as duas linhas em movimento, uma para o Brasil e outra para a Argentina.

Clique [aqui](./Modulos/Desafio_5_Desafio_criando_uma_animação_para_comparar_diferentes_dados.ipynb) para acessar o Desafio 05.