# Projeto-Integrador
Este repositório visa o cronograma do projeto integrador, utilizando o Gráfico de Gannt.


  ```mermaid
    gantt
    title Cronograma de atividades do projeto
    dateFormat  YYYY-MM-DD
    section Documentação
    Pré-projeto     :a1, 2022-10-10, 10d
    Escrita da parte teórica  :a2, 2022-11-01, 10d
    section Prototipação
    Criação de diagramas     :       c2,  2022-11-20, 30d
    Criação do protótipo - Front/Back-end      :c3,     after c2, 30d
    section Defesa
    Preparação dos slides :p1, after c3, 10d
    Ensaio da apresentação :p2, after c3, 7d
    Apresentação e entrega  :milestone, 2023-02-01, 5d
``` 
