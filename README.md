# Postura Inteligente com IA

Sistema inteligente para análise de postura corporal em tempo real, utilizando visão computacional e Inteligência Artificial para auxiliar no monitoramento ergonômico do usuário.

Este projeto foi desenvolvido por **Guilherme Basilio Faria**, **Arthur** e **Denys** como parte do **Projeto Integrador da Universidade de Sorocaba - UNISO**.

<img width="772" height="866" alt="image" src="https://github.com/user-attachments/assets/02506324-78bb-44b1-8124-456293efd14a" />


## Sobre o Projeto

O **Postura Inteligente com IA** é uma aplicação web que utiliza a câmera do computador para identificar pontos do corpo humano e analisar a postura do usuário em tempo real.

A aplicação monitora principalmente a posição do pescoço, ombros e tronco, classificando a postura como:

- ✅ **Boa**
- ❌ **Ruim**

Quando o sistema identifica que o usuário permanece por muito tempo em uma postura inadequada, um alarme sonoro é ativado para alertá-lo.

O objetivo do projeto é contribuir para a melhoria da ergonomia, prevenção de dores posturais e conscientização sobre hábitos saudáveis durante o uso do computador.

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript
- MediaPipe Pose
- OpenPose como referência conceitual para estimativa de pose
- Canvas API
- LocalStorage
- Webcam via navegador

## Funcionalidades

- Detecção de postura em tempo real pela webcam
- Identificação de pontos corporais usando IA
- Cálculo dos ângulos do pescoço e do tronco
- Classificação automática da postura
- Exibição visual dos pontos do corpo na tela
- Contador de tempo em postura boa e ruim
- Alarme sonoro após permanência prolongada em postura incorreta
- Cadastro de usuários por nome
- Histórico local de medições por usuário
- Gerenciamento de pastas de históricos
- Exclusão de históricos salvos

## Como Funciona

O sistema utiliza a câmera do dispositivo para capturar a imagem do usuário. Em seguida, a biblioteca MediaPipe Pose identifica pontos importantes do corpo, como orelha, ombro e quadril.

A partir desses pontos, o sistema calcula os ângulos do pescoço e do tronco. Com base nesses valores, a postura é classificada como adequada ou inadequada.

Caso a postura ruim seja mantida por determinado período, o sistema emite um alerta sonoro para chamar a atenção do usuário.

## Como Executar

1. Clone este repositório:

```bash
git clone https://github.com/SEU-USUARIO/postura-inteligente-ia.git
