# PROJETO: FONTE RETIFICADORA (3V-12V)
Trabalho desenvolvido no curso de Eletrônica para ciências de computação do professor Eduardo do Valle Simões.
Objetivos: Projeto de uma Fonte de Tensão entre 3V a 12V com capacidade de 100mA. Diagrama da Fonte com os valores dos componentes escolhidos e uma lista de componentes, contendo valores e preço.Link para o circuito no Falstad ou outro simulador. Projeto do Esquemático e do PCB no EAGLE. Se montou o circuito, incluir fotos da placa/protoboard. E um VIDEO mostrando o Projeto funcionando ou simulando, e explicando porque escolheu os valores dos componentes (Upa no Youtube e poe um link no teu Github).

## SCC0180 - Eletrônica para a Computação

## Vídeo Explicativo
[![Watch the video](https://www.youtube.com/watch?v=H6kj-XDnSmQ&feature=youtu.be)]
## Desenvolvimento
Trabalho desenvolvido pelos alunos:
* Pedro Henrique Conrado Ferreira de Oliveira - 11819091
* Leonardo Chieppe - 9368730

## O Circuito 
Esquema do circuito, seguido de PBC. Os arquivos para o circuito estão disponíveis nesse mesmo repositório.
!
![alt text](https://github.com/PedroConrado/Fonte-eletronica/blob/master/2020-06-27_14-59.png)
![alt text](https://github.com/PedroConrado/Fonte-eletronica/blob/master/2020-06-27_15-15.png)

## Circuito Falstad
http://tinyurl.com/yd2tqbon
![alt text](https://github.com/PedroConrado/Fonte-eletronica/blob/master/2020-06-27_09-10.png)

## Componentes
|Componente | Especificação | Justificativa |
|-----------|---------------|---------------|
|Transformador | 15v e 500mA | Responsável por transformar a corrente alternada de 220V para 17V|
|Transistor NPN | 15v e 500mA | Permite controlar a passagem da corrente |
|Resistores x4 | 2Kohm, 1Kohm, 390ohm, 120ohm | Limitam a corrente de acordo com os demais componentes |
|Potenciômetro | 5Kohm | Regula a tensão da fonte entre 12V - 3V |
|Ponte retificadora | 1000V e 2A | Transforma a corrente alternada em corrente contínua |
|Capacitor | 470uF | Armazena corrente e libera quando a tensão interna é maior que a externa |
|Diodo de Zener | 0,5W | Opera mantendo a tensão máxima do circuito em 13V |

### Custo Unidade:
Transformador: [26,99](https://produto.mercadolivre.com.br/MLB-989866927-transformador-trafo-1515v-500ma-bivolt-eletronica-eletrica-_JM?quantity=1#position=1&type=item&tracking_id=b3b43099-b6d3-4246-a532-7356d0c044b9)
Transistor NPN: [0,17](https://www.baudaeletronica.com.br/transistor-npn-bc548.html)
Resistores: [0,13](https://produto.mercadolivre.com.br/MLB-1345217069-resistor-10k-ohms-100-unidades-_JM?quantity=1#position=2&type=item&tracking_id=ebb01ab1-c319-4e04-83d3-0f995a12885d)
Potenciômetro: [19,29](https://produto.mercadolivre.com.br/MLB-1441845757-potencimetro-multivoltas-baoter-3590s-2-502l-5k-_JM?quantity=1#position=2&type=item&tracking_id=554c0e8a-de74-48d3-8653-993a6cdda8ac)
Ponte retificadora: [4,78](https://www.usinainfo.com.br/pontes-retificadoras/ponte-retificadora-2w10-3938.html)
Capacitor: [0,57](https://www.baudaeletronica.com.br/capacitor-eletrolitico-470uf-35v.html)
Diodo de Zener: [0,13](https://www.baudaeletronica.com.br/diodo-zener-1n5231-5v1-0-5w.html)
##### Total: R$52,28
