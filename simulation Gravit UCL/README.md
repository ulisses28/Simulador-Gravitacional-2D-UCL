# Simulador Gravitacional 2D

Este projeto implementa um simulador gravitacional 2D que calcula a interação gravitacional entre corpos distribuídos aleatoriamente em uma tela. O simulador permite gravar e recarregar a configuração do universo em arquivos de texto.

## Funcionalidades

- Distribuição aleatória de corpos na tela.
- Cálculo da interação gravitacional entre os corpos.
- Gravação da configuração atual do universo em um arquivo texto.
- Recarregamento da configuração inicial e atual do universo.
- Tratamento de colisões entre corpos.
- Utilização de computação paralela para otimização dos cálculos.

## Estrutura do Projeto

### Classes

- **Corpo**
  - Atributos:
    - Nome
    - Massa
    - Raio
    - Densidade
    - PosX
    - PosY
    - VelX
    - VelY
    - ForcaX
    - ForcaY

- **Universo**
  - Utiliza a classe `Corpo` para realizar os cálculos necessários para a simulação.
  - Métodos para calcular a posição dos corpos e tratar colisões.

### Prints
![image](https://github.com/user-attachments/assets/85832b5d-92c2-44df-be01-ae86ebe8bd2e)

![image](https://github.com/user-attachments/assets/6caf7b14-c54b-41bf-a234-d4832ccc69c9)


Clique em um corpo para ver seus respectivos atributos
