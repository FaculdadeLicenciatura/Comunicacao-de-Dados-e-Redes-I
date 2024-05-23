# Ficha 2 - Resolução
### 1\. Identificação de endereço de rede, parte de rede e parte de host:

#### a. 150.203.23.19 - 255.255.0.0

-   Máscara: 255.255.0.0 (16 bits para a rede)
-   Endereço de rede: 150.203.0.0
-   Parte da rede: 150.203
-   Parte do host: 23.19

#### b. 200.120.135.15 - 255.255.255.128

-   Máscara: 255.255.255.128 (25 bits para a rede)
-   Endereço de rede: 200.120.135.0
-   Parte da rede: 200.120.135
-   Parte do host: 15

#### c. 10.10.10.10/8

-   Máscara: /8 (8 bits para a rede)
-   Endereço de rede: 10.0.0.0
-   Parte da rede: 10
-   Parte do host: 10.10.10

#### d. 199.20.150.35/24

-   Máscara: /24 (24 bits para a rede)
-   Endereço de rede: 199.20.150.0
-   Parte da rede: 199.20.150
-   Parte do host: 35

#### e. 5.5.5.5/20

-   Máscara: /20 (20 bits para a rede)
-   Endereço de rede: 5.5.0.0
-   Parte da rede: 5.5
-   Parte do host: 5.5

#### f. 172.16.29.1/17

-   Máscara: /17 (17 bits para a rede)
-   Endereço de rede: 172.16.0.0
-   Parte da rede: 172.16
-   Parte do host: 29.1

### 2\. Parâmetros para endereços IP:

#### a. 223.23.223.109/26

-   Classe: C (Público)
-   Endereço de rede: 223.23.223.64
-   Endereço de broadcast: 223.23.223.127
-   Número de bits para host: 6
-   Número total de endereços IP por rede: 64
-   Número total de hosts por rede: 62

#### b. 10.10.250.1/16

-   Classe: A (Privado)
-   Endereço de rede: 10.10.0.0
-   Endereço de broadcast: 10.10.255.255
-   Número de bits para host: 16
-   Número total de endereços IP por rede: 65,536
-   Número total de hosts por rede: 65,534

#### c. 192.168.156.3/18

-   Classe: C (Privado)
-   Endereço de rede: 192.168.128.0
-   Endereço de broadcast: 192.168.191.255
-   Número de bits para host: 14
-   Número total de endereços IP por rede: 16,384
-   Número total de hosts por rede: 16,382

#### d. 172.16.28.150/26

-   Classe: B (Privado)
-   Endereço de rede: 172.16.28.128
-   Endereço de broadcast: 172.16.28.191
-   Número de bits para host: 6
-   Número total de endereços IP por rede: 64
-   Número total de hosts por rede: 62

### 3\. Verificação de rede:

#### a. 192.168.1.1 e 192.168.1.126, Máscara: 255.255.255.0

-   Endereço de rede: 192.168.1.0 (para ambos)
-   Estão na mesma rede: Sim

#### b. 192.168.25.50 e 192.168.25.129, Máscara: 255.255.255.128

-   Endereço de rede: 192.168.25.0 (para 192.168.25.50)
-   Endereço de rede: 192.168.25.128 (para 192.168.25.129)
-   Estão na mesma rede: Não

#### c. 10.0.0.1/23 e 10.0.1.1/23

-   Endereço de rede: 10.0.0.0 (para ambos)
-   Estão na mesma rede: Sim

#### d. 10.11.8.100/21 e 10.11.7.100/21

-   Endereço de rede: 10.11.8.0 (para 10.11.8.100)
-   Endereço de rede: 10.11.0.0 (para 10.11.7.100)
-   Estão na mesma rede: Não

### 4\. Quantas classes de endereçamento IP existem? Quais?

Existem 5 classes principais de endereçamento IP:

-   Classe A (1.0.0.0 a 126.0.0.0)
-   Classe B (128.0.0.0 a 191.255.0.0)
-   Classe C (192.0.0.0 a 223.255.255.0)
-   Classe D (224.0.0.0 a 239.255.255.255, usado para multicast)
-   Classe E (240.0.0.0 a 255.255.255.255, reservado para uso futuro ou experimental)

### 5\. Gamas de endereçamento privado:

-   Classe A: 10.0.0.0 a 10.255.255.255
-   Classe B: 172.16.0.0 a 172.31.255.255
-   Classe C: 192.168.0.0 a 192.168.255.255

### 6\. Definição de máscara de rede:

Uma máscara de rede é um valor usado para identificar a parte da rede de um endereço IP e a parte do host. Ela é usada em conjunto com o endereço IP para determinar a sub-rede à qual o endereço IP pertence.

### 7\. Identificação de erros:

#### a. Máscara de rede: 11111111.11101111.11111111.00000000

-   Máscara inválida. A máscara de rede deve ter todos os bits de rede contíguos, não pode haver bits 1 após bits 0.

#### b. Endereço de Rede: 172.16.25.1/24

-   O endereço de rede deveria ser 172.16.25.0/24, 172.16.25.1 é um endereço de host, não um endereço de rede.

#### c. Endereço de Rede: 192.168.25.3/33

-   Máscara inválida. A máscara de rede para IPv4 deve ter no máximo 32 bits. /33 não é uma máscara válida.

#### d. Endereço de Broadcast: 192.168.200.62/26

-   O endereço de broadcast para a rede 192.168.200.0/26 é 192.168.200.63, não 192.168.200.62.

#### e. Máscara de rede: 255.256.255.0

-   Máscara inválida. Valores de máscara de rede devem estar no intervalo de 0 a 255. 256 não é um valor válido para um octeto de máscara.
