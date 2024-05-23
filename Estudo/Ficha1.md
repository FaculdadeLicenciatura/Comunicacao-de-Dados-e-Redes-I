# Ficha 01 - Resolução
## 1\. Conversão de binário para decimal:

a. 11001101

-   1*2^7 + 1*2^6 + 0*2^5 + 0*2^4 + 1*2^3 + 1*2^2 + 0*2^1 + 1*2^0
-   128 + 64 + 8 + 4 + 1 = 205

b. 01000111

-   0*2^7 + 1*2^6 + 0*2^5 + 0*2^4 + 0*2^3 + 1*2^2 + 1*2^1 + 1*2^0
-   64 + 4 + 2 + 1 = 71

c. 01110110

-   0*2^7 + 1*2^6 + 1*2^5 + 1*2^4 + 0*2^3 + 1*2^2 + 1*2^1 + 0*2^0
-   64 + 32 + 16 + 4 + 2 = 118

d. 01010101

-   0*2^7 + 1*2^6 + 0*2^5 + 1*2^4 + 0*2^3 + 1*2^2 + 0*2^1 + 1*2^0
-   64 + 16 + 4 + 1 = 85

e. 10101010

-   1*2^7 + 0*2^6 + 1*2^5 + 0*2^4 + 1*2^3 + 0*2^2 + 1*2^1 + 0*2^0
-   128 + 32 + 8 + 2 = 170

## 2\. Conversão de decimal para binário:

a. 74

-   01001010

b. 468

-   111010100

c. 752

-   1011110000

d. 63

-   00111111

e. 159

-   10011111

f. 1759

-   11011011111

g. 3148

-   110001001100

h. 4852

-   1001011110100

i. 36745

-   1000111101001001

j. 59823

-   1110100110101111

## 3\. Converta os seguintes endereços IP para binário:

a. 10.50.60.75

-   00001010.00110010.00111100.01001011

b. 92.63.15.33

-   01011100.00111111.00001111.00100001

c. 192.17.45.189

-   11000000.00010001.00101101.10111101

d. 185.0.165.3

-   10111001.00000000.10100101.00000011

e. 158.159.78.96

-   10011110.10011111.01001110.01100000

### 4\. Identificação da classe e tipo:

a. 10.250.1.1

-   Classe A, privado

b. 150.10.15.5

-   Classe B, público

c. 192.168.2.50

-   Classe C, privado

d. 220.200.23.15

-   Classe C, público

e. 177.100.18.47

-   Classe B, público

f. 172.20.1.2

-   Classe B, privado

g. 48.2.85.63

-   Classe A, público

h. 117.89.56.45

-   Classe A, público

i. 169.254.3.2

-   Classe B, privado (Link-local)

## 5\. Cabeçalho IP e seus campos:

-   Version: Versão do protocolo IP (IPv4 ou IPv6).
-   Header Length: Comprimento do cabeçalho IP.
-   Type of Service (ToS): Define a prioridade do pacote.
-   Total Length: Comprimento total do pacote IP.
-   Identification: Identifica fragmentos de pacotes.
-   Flags: Controla fragmentação (DF, MF).
-   Fragment Offset: Posição do fragmento no pacote original.
-   Time to Live (TTL): Tempo de vida do pacote.
-   Protocol: Protocolo da camada superior (TCP, UDP, etc.).
-   Header Checksum: Verifica erros no cabeçalho.
-   Source Address: Endereço IP de origem.
-   Destination Address: Endereço IP de destino.
-   Options: Opções extras para controle e roteamento.
-   Padding: Preenchimento para alinhar o cabeçalho a um múltiplo de 4 bytes.

## 6\. Tipos de endereçamento:

-   Unicast Address: Endereço único que identifica um único receptor.
-   Broadcast Address: Endereço que permite enviar dados para todos os dispositivos em uma rede.
-   Multicast Address: Endereço usado para enviar dados para um grupo específico de dispositivos.
-   Anycast Address: Endereço atribuído a múltiplos dispositivos onde o pacote é entregue ao dispositivo mais próximo ou eficiente em termos de roteamento.
