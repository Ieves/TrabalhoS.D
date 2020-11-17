# TrabalhoS.D
Contador de veiculos

Pensei em fazer sobre esse tema devido a crescente necessidade de locomoção e transporte de pessoas e objetos a partir de veículos motorizados têm implicado na necessidade de construção e modernização de vias e elementos de controle de tráfego cada vez mais sofisticados. A interação entre os elementos de um sistema de transito possui uma dinâmica complexa e imprevisível, pois seu funcionamento depende essencialmente do comportamento humano. Essa característica reforça a necessidade de construção e modernização de vias e elementos de controle de tráfego. Tais necessidades e características inerentes ao transito tornam justificáveis o constante estudo sobre os mecanismos de transporte e o transito de veículos existentes dentro destes contextos, além do desenvolvimento de novas soluções para melhoria do fluxo e da segurança de passageiros, pedestres e bens materiais.
	Saber o volume de veículos é importante, pois, permite o planejamento e melhoramento das vias, bem como a implantação de sinalização adequada. Diversos trabalhos foram e vêm sendo desenvolvidos com estes objetivos. 
Esse trabalho tem três elementos: Sistema de medição, Sistema embarcado, Interface.
Material de Medição: É formado por um sensor de infravermelho que fica posto em cima da pista permitindo detecção de veículos que se aproximam ou se afastam do sensor ele fica responsável por detectar a presença de veículos e emitir um sinal elétrico a ser interpretado no sistema embarcado. Porta de conexão 888.
Sistema Embarcado: O sistema embarcado além de interpretar esse sinal também processa e armazena informações. A frequência do sinal é recalculada a cada interrupção, foi programada então, uma rotina para avaliar constantemente o valor dessa variável. Caso haja uma grande variação neste valor, o micro controlador emite um sinal elétrico por um de seus pinos, sinalizando a detecção de um objeto metálico, esse pino é conectado diretamente no sistema embarcado. Porta de conexão 999.
Interface: Pode ser conectada ao sistema embarcado para configurá-lo e recuperar dados referentes ao fluxo de veículos à interação com o sistema vai ser via Terminal. Porta de conexão 998.




