# Análise orientada a objeto
> [!NOTE]
> A **análise** orientada a objeto consiste na descrição do problema a ser tratado, duas primeiras etapas da tabela abaixo, a definição de casos de uso e a definição do domínio do problema.

## Descrição Geral do domínio do problema

Descrever de forma geral o domínio do problema.

Possíveis requisitos funcionais e não-funcionais podem ser elencados aqui.

Neste jogos iremos precisar de duas classes principais, o jogador e o monstro controlado pelo programa. O jogador possuí três principais ações: Atacar, defender e usar habilidade, o monstro não possuí um padrão de habilidades, ele fara uma ação aleatória ou a mais benéfica para ele, dependendo da dificuldade do monstro

https://lucid.app/lucidchart/cb8c3d66-942a-4497-951f-4c9c2d486d5e/edit?viewport_loc=-480%2C-29%2C2917%2C1537%2C.Q4MUjXso07N&invitationId=inv_43168cd0-2087-4610-950e-78e86dc5ab32

## Diagrama de Casos de Uso

Apresentar o diagram de casos de uso, identificando as funcionalidades do sistema assim como os atores envolvidos

Aqui vemos que a parte principal é o turno do jogador, onde ele pode escolher qual ação ele fará. O jogo dispõe para o jogador a próxima ação do inimigo, assim ele pode escolher melhor o que ele fará a seguir (alguns inimigos não mostram a próxima ação). Após isto, esta ação é executada, em seguida o monstro executa sua ação, e então entram os eventos secundários, que acontecem fora de turno, como dano por sangramento/veneno, buffs, etc

https://lucid.app/lucidchart/81e3cc0d-e947-4c7a-ba49-b82ed9dc2960/edit?viewport_loc=-114%2C-13%2C2307%2C1215%2CHWEp-vi-RSFO&invitationId=inv_8308c1fc-e300-4a62-8afd-6eb4926ba6ff
 
## Diagrama de Domínio do problema

Elaborar um diagrama conceitual do domínio do problema.


<div align="center">

[Retroceder](README.md) | [Avançar](projeto.md)

</div>
