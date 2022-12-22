# Mapeando Objeto para Objeto com ModelMapper
## Simples testes usando object-to-object mapper: 

> 1) [ModelMapper](http://modelmapper.org/)

> 2) [Dozer](http://dozer.sourceforge.net/)

> 3) [Orika](https://github.com/orika-mapper/orika/)

## Fontes:
> [Steppat Github](https://github.com/steppat/modelmapper)
>
> [Steppat artigo](https://www.alura.com.br/artigos/mapeando-objeto-para-objeto-com-modelmapper?gclid=CjwKCAiAnZCdBhBmEiwA8nDQxbqAOL01A3f7VIlq4gDFKSfPZ68Mhhnq7AT2WNJjnZnV6TO6Kp8ZkBoC1KoQAvD_BwE)

## Usando o DTO:
> É muito comum que aplicações mapeiem o modelo de negócio (domínio) para outras estrutura de dados. Por exemplo, se quisermos expor uma parte do domínio como serviço web é preciso mapear os dados para JSON ou XML. Há bibliotecas para esta tarefa como, por exemplo, XStream ou JAX-B. Com elas podemos usar anotações para configurar o mapeamento de JSON/XML. O problema é que essas configurações começam a poluir as classes de domínio e nem sempre são flexíveis o suficiente. Uma forma de resolver isso é criar classes dedicadas que só existem para definir o modelo do serviço web. São classes que não possuem nenhuma regra de negócio. Podemos enxerga-las seguindo o padrão DTO (Data Transfer Object, muitas vezes chamado de Value Object). São objetos que só existem para serem transferidos entre camadas físicas. As anotações de mapeamento ficariam então nessas classes e o domínio estaria livre dessas configurações.
