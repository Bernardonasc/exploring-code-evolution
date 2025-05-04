# Gráfico selecionado: LOC / TypeScript files

## O que o gráfico mostra?
O gráfico mostra o aumento do número médio de linhas de código por arquivo TypeScript entre 2020 e 2025. Em 2020, o valor é 0 (indicando que não havia arquivos TypeScript), e esse número começa a crescer a partir de 2021, com uma subida mais acentuada entre 2022 e 2025.

## Padrão e Implicações:
O aumento de linhas de código por arquivo pode ser interpretado de várias formas, mas o mais importante é que isso provavelmente indica que os arquivos estão ficando mais complexos com o tempo, ou seja, os desenvolvedores estão escrevendo mais código dentro de um único arquivo. Isso pode acontecer por vários motivos:

Aumento da complexidade do projeto: O projeto pode estar se tornando mais complexo, exigindo mais código dentro de cada arquivo. Isso não é necessariamente uma "boa" ou "má" prática, mas um reflexo de como o desenvolvimento do software está evoluindo.

Refatoração ou adição de novas funcionalidades: O aumento pode indicar que, à medida que o projeto cresce, mais funcionalidades estão sendo adicionadas aos arquivos existentes, ou novos recursos estão sendo desenvolvidos diretamente em arquivos maiores.

Possível sinal de código mais difícil de manter: Embora aumentar o número de linhas de código por arquivo não seja uma prática intrinsecamente ruim, pode ser um sinal de que os arquivos estão ficando mais difíceis de manter, o que é um ponto que você trouxe corretamente. Se os arquivos se tornarem muito grandes e complexos, isso pode dificultar a manutenção, a leitura e a extensão do código no futuro. Idealmente, cada arquivo deve ser modularizado para garantir que ele seja compreensível e de fácil manutenção.

O aumento das linhas de código pode ser negativo se não for gerenciado adequadamente. Grandes arquivos com muitas linhas de código podem tornar o código mais difícil de entender e de modificar, o que pode impactar negativamente a produtividade e a qualidade do código. Em projetos grandes, pode ser uma boa prática dividir funcionalidades em módulos menores, funções bem definidas e arquivos mais enxutos.

## Boas práticas:
Em projetos de grande escala, arquivos pequenos e modulares são geralmente mais fáceis de entender e manter. Se os arquivos começarem a crescer muito em número de linhas, pode ser um indicativo de que o código está se tornando difícil de gerenciar.

A refatoração é uma prática importante para evitar que arquivos se tornem muito grandes e complexos. Isso inclui a divisão de arquivos e a organização do código de maneira que ele continue sustentável ao longo do tempo.