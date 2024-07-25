# Analise_de_gel_SDS-Page_Python
Script codado em python que utiliza processamento de imagem para analisar imagens de géis de corrida de proteínas (SDS-Page) e quantificar, por meio da intensidade da luz, a quantidade de proteínas em cada colunas do gel.

programadores: andre.araujocaetano.profissional@gmail.com / beatrizborgesribeiro2@gmail.com

No geral, apesar de as funções serem grandes, o pipeline do script é bem simples.

1. Rode as bibliotecas de funções
2. Você terá duas opções de exemplos, mostrando o processo (que é indicado caso não esteja familiarizado) e sem mostrar o processo.
3. Substituia o nome da variável ``imagem_original`` pela imagem que você quer analisar, a linha ``imagem_rgb`` é utilizada para transformar em 3 dimensões caso sua imagem de RGB esteja em 4 dimensões.
4. Utilize a função ``processamento_imagem`` para colocar a imagem em tons de cinza, o que torna mais fácil o processamento.
5. Set as variáveis ``x`` e ``y`` para recotar as colunas que deseja com a função ``recortar_imagem``, lembrando que essa função recebe, além da imagem, uma lista para o eixo x e uma lista para o eixo y sendo: o primeiro valor o ponto da esquerda e o segundo o ponto da direita e o recorte ocorrerá nesse range.
6. Por fim, coloque todos os recortes dentro de uma lista e utilize a função ``plotar_resultados`` para comparar a intensidade de proteína em uma ou ``n`` colunas que queira analisar.
7. Qualquer dúvida entre em contato.


“Eu quero ser forte o suficiente para que ninguém se preocupe comigo. Para sempre vencer… Para sempre salvar a todos. Eu quero ser… o maior herói.” - Izuku, Midoriya.
