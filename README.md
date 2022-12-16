# SistemaOO_Python
Sistema Orientado a Objetos em Python

ESCOPO DO DESENVOLVIMENTO

  Em um campeonato de MMA, lutadores realizam lutas em que no final é determinado um vencedor. Os lutadores possuem vários atributos que podem ou não ser vantajosos contra determinado adversário(envergadura, altura, peso etc). 
  O número de lutas de um campeonato é variável, a depender da vontade do patrocinador. Cada luta tem seu card específico, que representa uma noite de lutas. As lutas são narradas por narradores especializados, não havendo narradores fixos, ou seja, cada luta pode ser narrada por qualquer narrador.
  Cada narrador tem tem um ID, idade, nome e temperamento. Cada lutador tem nome, idade, ID, peso, altura e envergadura, sendo o peso um fator determinante para a listagem de lutadores para uma certa categoria. Já as lutas tem ID, primeiro lutador, segundo lutador, narradores, vencedor, local, card e data. E por último, o campeonato que tem ID, nome e dono.
  O Sistema foi modelado em MVC (Model Controller View). Nesse tipo de modelo uma classe Entidade (model) so pode se comunicar com uma classe Controlador (Controller) e não pode se comunicar com classes do tipo Tela (View). Do mesmo jeito, a classe Tela pode se comunicar somente com Controladores.

Regras de negócio:

  Cada luta possui apenas 2 lutadores;
  Cada luta pode ser narrada por um ou mais narradores;
  Um lutador pode competir apenas em um campeonato por vez


RESTRIÇÕES DE ESCOPO

Para simplificar este trabalho, o sistema contempla somente características básicas de um campeonato de MMA, não abordando as questões de classificação em rankings, divisao de lutas em feminino e masculino, detentores de cinturão, entre outros.
