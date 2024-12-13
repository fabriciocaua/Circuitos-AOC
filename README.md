# Circuitos Digitais - Repositório de Componentes

Este repositório contém uma coleção de circuitos digitais implementados e documentados. Abaixo está a lista dos componentes com seus detalhes de construção, funcionalidades e aplicações.

## Componentes

### 1. **Registrador Flip-Flop do Tipo D e do Tipo JK**
#### 1.1 **Flip-Flop do Tipo D**
   - **1.1.1. Construção**: O Flip-Flop do tipo D armazena um bit de informação. Ele possui uma entrada de dados (D), uma entrada de clock (CLK) e uma saída (Q). A saída é atualizada com o valor de D na borda de subida do clock.
   - **1.1.2. Características**: 
     - Armazena um bit de informação.
     - A saída Q é igual ao valor de D durante a borda de subida do clock.

#### 1.2 **Flip-Flop do Tipo JK**
   - **1.2.1. Funcionalidades**: O Flip-Flop JK é mais versátil. Ele pode ser configurado para funções de set, reset, toggle ou memória simples, dependendo das entradas J e K.
   
### 2. **Multiplexador de Quatro Opções de Entrada**
#### 2.1 **Construção de um Multiplexador de 4 Entradas**: 
   - Utiliza uma combinação de portas lógicas (AND, OR, NOT) para selecionar uma das 4 entradas com base em duas linhas de controle.
   
#### 2.2 **Aplicações com os Multiplexadores**: 
   - Usados em sistemas de comunicação e processamento de dados para reduzir o número de linhas de comunicação.

### 3. **Porta Lógica XOR Usando AND, NOT e OR**
#### 3.1 **Construção da Porta XOR**: 
   - A porta XOR pode ser construída combinando portas AND, OR e NOT.
   
#### 3.2 **Funcionalidade e Aplicações**: 
   - Realiza a operação de exclusão OR, onde a saída é 1 se as entradas forem diferentes e 0 se forem iguais.
   - Usada em circuitos de comparação e paridade.

### 4. **Somador de 8 Bits que Recebe um Valor Inteiro e Soma com o Valor 4**
#### 4.1 **Por que os Somadores São Importantes?**
   - Somadores são fundamentais em processadores e outros circuitos digitais para realizar operações aritméticas.

#### 4.2 **Tipos de Somadores**
   - **4.2.1. Somador de 8 Bits**: Circuito que soma dois números de 8 bits.
   - **4.2.2. Somador de 8 Bits que Soma com o Valor 4**: Adiciona 4 a um valor de 8 bits.

### 5. **Memória ROM de 8 Bits**
#### 5.1 **Funções da Memória ROM**
   - **5.1.1. Como Funciona a Memória ROM Programada pelo Usuário?**
     - A memória ROM armazena dados permanentemente. O conteúdo é definido durante a fabricação ou pode ser programado por um usuário, conforme necessário.

#### 5.2 **Construindo uma Memória ROM de 8 Bits**
   - Circuito de 8 bits que armazena dados fixos e que não podem ser modificados durante a operação.

### 6. **Memória RAM**
   - **Não Implementado**

### 7. **Banco de Registradores de 8 Bits**
#### 7.1 **Construção**
   - Um conjunto de registradores de 8 bits usados para armazenar dados temporários em um sistema digital.
   
#### 7.2 **Características de Construção**
   - Cada registrador pode armazenar 1 byte de informação. Os bancos de registradores são fundamentais em processadores e unidades de controle.

### 8. **Detector de Sequência de Bit "101"**
   - Detector que identifica se a sequência binária "101" aparece em um fluxo de entrada.

### 9. **ULA de 8 Bits com Operações Lógicas e Aritméticas**
   - **Não Implementado**

### 10. **Extensor de Sinal de 4 Bits para 8 Bits**
#### 10.1 **Funcionamento do Extensor de 4 para 8 Bits**
   - O extensor aumenta a largura do sinal de 4 para 8 bits, mantendo o valor original.

### 11. **Máquina de Estados Utilizando Portas Lógicas**
   - **Não Implementado**

### 12. **Contador Síncrono**
   - **Não Implementado**

### 13. **Detector de Paridade Ímpar Usando Portas Lógicas AND, OR e NOT**
   - **Não Implementado**

### 14. **Otimização Lógica Usando Mapas de Karnaugh**
   - **Não Implementado**

### 15. **Decodificador de 7 Segmentos**
#### 15.1 **Estrutura do Circuito**
   - Um decodificador de 7 segmentos converte um número binário de 4 bits para um formato adequado para controlar um display de 7 segmentos.

#### 15.2 **Funcionamento do Circuito**
   - O circuito converte a entrada binária para sinais que acendem os segmentos específicos de um display de 7 segmentos.

#### 15.3 **Construção do Circuito**
   - Utiliza portas lógicas para controlar os segmentos do display conforme a entrada binária.

### 16. **Detector de Número Primo**
#### 16.1 **Funcionamento do Circuito**
   - O circuito detecta se um número binário de 4 bits é primo, utilizando portas lógicas e Mapas de Karnaugh para simplificar a implementação.

## Como Usar

1. **Baixe ou clone o repositório:**

   ```bash
   git clone https://github.com/fabriciocaua/Circuitos-AOC.git
