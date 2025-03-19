# Cobot-6DOF

Este projeto envolve o desenvolvimento e implementação de um braço robótico com 6 graus de liberdade (DOF), projetado para realizar uma série de movimentos automatizados, como pressionar, pegar, virar e retornar à posição inicial de forma contínua e coordenada. O código foi desenvolvido em XML utilizando o padrão URDF (Unified Robot Description Format), amplamente utilizado em simulações de robótica, especialmente no ROS (Robot Operating System).

Descrição do Projeto
Este projeto foi implementado em várias etapas, com o braço robótico sendo programado para realizar tarefas específicas em um ambiente industrial simulado. Cada movimento do braço foi projetado com base em posições específicas no espaço, alinhando-se com os requisitos de um local determinado onde o robô operaria. O braço robótico executa as seguintes operações:

Posicionamento Inicial: O braço inicia o movimento na posição acima de um objeto.
Pressionamento: O braço pressiona um objeto para baixo com precisão.
Pega do Objeto: Após pressionar o objeto, o braço o levanta.
Virada do Objeto: O braço vira o objeto para uma nova posição.
Retorno à Posição Inicial: O braço retorna à sua posição original após completar o movimento.
Funcionalidade
Movimento Cíclico: O ciclo de movimento (pressionar, pegar, virar e voltar) é repetido infinitamente, permitindo ao braço realizar essas operações continuamente.
Posicionamento e Controle: O código foi elaborado para garantir a precisão das posições do braço em cada etapa. As juntas do braço são controladas para realizar os movimentos com precisão, de acordo com as coordenadas e a sequência de movimentos.
Aplicações em Indústria: Este projeto pode ser adaptado para automação industrial, onde o braço robótico seria usado para manipular peças e realizar tarefas repetitivas de forma eficiente.
Tecnologias Utilizadas
XML/URDF: Definição do modelo do braço robótico utilizando o formato URDF, amplamente utilizado para descrever robôs no ROS.
Simulação de Movimentos: As movimentações são definidas para se ajustarem ao ambiente simulado ou real, dependendo da aplicação.
Ciclo Infinito de Movimentos: O código permite que os movimentos sejam repetidos infinitamente, garantindo automação contínua para o processo de manipulação.
Objetivos do Projeto
Desenvolver um braço robótico controlado por código em XML.
Implementar movimentos coordenados e cíclicos para automação.
Validar o controle de movimento em um ambiente industrial (simulado ou real).
Garantir precisão e repetibilidade dos movimentos nas diferentes etapas (pressionar, pegar, virar, voltar).
Como Usar
Clone o repositório para o seu ambiente local.
Integre o código com um simulador de robótica (como o Gazebo ou ROS) que suporte arquivos URDF.
Personalize o código de acordo com as posições específicas do seu ambiente.
Inicie a simulação para ver o braço robótico realizar os movimentos automáticos.
Próximos Passos
Integrar sensores para feedback do ambiente (como câmeras ou sensores de toque).
Implementar controle por joystick ou interfaces manuais.
Expandir o modelo para incluir mais funcionalidades de manipulação de objetos.
