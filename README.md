# Timer em Assembly para PIC16F628A

Este é um projeto de timer em Assembly desenvolvido para o microcontrolador PIC16F628A. Ele consiste em um timer que conta segundos e exibe o tempo decorrido em um display de 8 segmentos.

## Funcionalidades

- Contagem de tempo em segundos.
- Botão de início para iniciar e parar o timer.
- Utilização de interrupção para controlar o tempo.

## Componentes Utilizados

- Microcontrolador PIC16F628A.
- Display de 8 segmentos.
- Botão de início.

## Instruções de Uso

1. Conecte o microcontrolador PIC16F628A ao circuito.
2. Carregue o código Assembly no microcontrolador.
3. Pressione o botão de início para iniciar o timer.
4. Pressione novamente o botão de início para parar o timer.

## Descrição do Código

O código é dividido em várias seções:

- **Configurações Iniciais**: Inclui os registradores do processador e define as configurações necessárias.
- **Variáveis e Constantes**: Define as variáveis e constantes utilizadas no programa.
- **Rotina de Delay**: Implementa uma rotina de delay para controlar o tempo.
- **Início do Programa**: Configura os pinos de entrada e saída, inicializa as variáveis e inicia o programa.
- **Rotina Principal**: Controla a exibição do tempo e inicia o timer quando o botão é pressionado.
- **Rotina de Timer**: Inicia o timer e atualiza o tempo decorrido.

## Autor

Este projeto foi desenvolvido por Mateus Felipe Rauber.

