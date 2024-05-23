# Ficha 3 - Resolução
### 1\. Qual dos seguintes endereços IP não é da mesma sub‐rede do endereço 191.5.80.80/20?

A máscara /20 equivale a 255.255.240.0.

A rede é 191.5.80.0/20, o intervalo é de 191.5.80.0 a 191.5.95.255.

a) 191.5.79.254 - Fora da sub-rede b) 191.5.80.50 - Na sub-rede c) 191.5.83.100 - Na sub-rede d) 191.5.85.200 - Na sub-rede e) 191.5.95.1 - Na sub-rede f) 191.5.96.1 - Fora da sub-rede

Resposta: a) 191.5.79.254, f) 191.5.96.1

### 2\. Verificação de sub‐rede

#### a) 172.16.10.1 e 172.16.10.126, Máscara: 255.255.255.192

-   Endereço de rede: 172.16.10.0

-   Endereço de broadcast: 172.16.10.63

-   Endereço de rede: 172.16.10.64

-   Endereço de broadcast: 172.16.10.127

Resposta: Não estão na mesma sub-rede.

#### b) 192.168.0.180/27 e 192.168.0.192/27

-   Endereço de rede: 192.168.0.160

-   Endereço de broadcast: 192.168.0.191

-   Endereço de rede: 192.168.0.192

-   Endereço de broadcast: 192.168.0.223

Resposta: Não estão na mesma sub-rede.

#### c) 172.16.100.234 e 172.16.98.234, Máscara: 255.255.240.0

-   Endereço de rede: 172.16.96.0
-   Endereço de broadcast: 172.16.111.255

Resposta: Estão na mesma sub-rede.

#### d) 192.168.9.31/27 e 192.168.9.32/27

-   Endereço de rede: 192.168.9.0

-   Endereço de broadcast: 192.168.9.31

-   Endereço de rede: 192.168.9.32

-   Endereço de broadcast: 192.168.9.63

Resposta: Não estão na mesma sub-rede.

#### e) 10.25.0.1/23 e 10.25.1.1/23

-   Endereço de rede: 10.25.0.0
-   Endereço de broadcast: 10.25.1.255

Resposta: Estão na mesma sub-rede.

### 3\. Verdadeiro ou Falso

a) 127.0.0.1 é um endereço IP público;

-   Falso, é um endereço de loopback (local).

b) O endereço 203.127.12.15 é de classe D;

-   Falso, é um endereço de classe C.

c) O endereço 118.15.1.1 é de classe A;

-   Falso, é um endereço de classe B.

d) Um endereço IPv4 é constituído por 32 bits;

-   Verdadeiro.

e) Um endereço IPv4 é constituído por uma parte de host e uma parte de broadcast;

-   Falso, é constituído por uma parte de rede e uma parte de host.

f) Endereços IPv4 válidos são, por exemplo, 12.5.8.1/8, 175.16.12.8/16, 196.84.256.118/24;

-   Falso, 196.84.256.118/24 é inválido (256 é fora do intervalo válido 0-255).

### 4\. Máscara 255.255.255.224 para a rede 172.20.0.0

#### a) O host 172.20.0.250 pertence à sub‐rede 172.20.0.224;

-   Verdadeiro.

#### b) Cada sub‐rede suporta 16 hosts;

-   Falso, suporta 30 hosts (32 - 2).

#### c) Há um total de 256 sub‐redes com um máximo de 254 hosts em cada uma;

-   Falso, a máscara /27 cria sub-redes com 30 hosts.

#### d) O endereço 172.20.248.191 é um endereço de sub‐rede;

-   Falso, é um endereço de broadcast.

#### e) O endereço 172.20.248.191 é um endereço de broadcast;

-   Verdadeiro.

#### f) O endereço 172.20.248.191 é um endereço de host;

-   Falso, é um endereço de broadcast.

#### g) O host 172.20.255.97 pertence à sub‐rede 172.20.255.64;

-   Verdadeiro.

#### h) O endereço 172.20.255.34 é um endereço de sub‐rede;

-   Falso, é um endereço de host.

#### i) O endereço 172.20.255.34 é um endereço de broadcast;

-   Falso, é um endereço de host.

#### j) O endereço 172.20.255.34 é um endereço de host;

-   Verdadeiro.

### 5\. Preencher a tabela

| Endereço/Sub-rede | Classe | End. de Rede | End. Broadcast | End. p/máquinas |
| --- | --- | --- | --- | --- |
| 110.24.34.3/24 | A | 110.24.34.0 | 110.24.34.255 | 254 |
| 192.168.10.65/26 | C | 192.168.10.64 | 192.168.10.127 | 62 |
| 45.145.67.33/13 | A | 45.144.0.0 | 45.151.255.255 | 524286 |
| 10.5.6.32/16 | A | 10.5.0.0 | 10.5.255.255 | 65534 |
| 172.16.25.52/25 | B | 172.16.25.0 | 172.16.25.127 | 126 |

### 6\. Identificar endereço de rede

#### a. 158.6.15.36 - 255.255.0.0

-   Endereço de rede: 158.6.0.0
-   Bits de rede: 16, Bits de host: 16

#### b. 100.150.220.129 - 255.255.255.128

-   Endereço de rede: 100.150.220.128
-   Bits de rede: 25, Bits de host: 7

#### c. 10.10.20.20/8

-   Endereço de rede: 10.0.0.0
-   Bits de rede: 8, Bits de host: 24

#### d. 180.20.155.48/24

-   Endereço de rede: 180.20.155.0
-   Bits de rede: 24, Bits de host: 8

#### e. 15.25.35.30/20

-   Endereço de rede: 15.25.32.0
-   Bits de rede: 20, Bits de host: 12

#### f. 172.16.129.36/17

-   Endereço de rede: 172.16.0.0
-   Bits de rede: 17, Bits de host: 15

### 7\. Criar 4 sub‐redes com 50 hosts cada (172.16.20.0/24)

-   Precisamos de 6 bits para 50 hosts (2^6 - 2 = 62 hosts).
-   Novo prefixo: /26 (255.255.255.192)

Sub-redes:

1.  172.16.20.0/26

    -   Endereço de rede: 172.16.20.0
    -   Endereço de broadcast: 172.16.20.63
    -   Máscara: 255.255.255.192
2.  172.16.20.64/26

    -   Endereço de rede: 172.16.20.64
    -   Endereço de broadcast: 172.16.20.127
    -   Máscara: 255.255.255.192
3.  172.16.20.128/26

    -   Endereço de rede: 172.16.20.128
    -   Endereço de broadcast: 172.16.20.191
    -   Máscara: 255.255.255.192
4.  172.16.20.192/26

    -   Endereço de rede: 172.16.20.192
    -   Endereço de broadcast: 172.16.20.255
    -   Máscara: 255.255.255.192

### 8\. Criar 2 sub‐redes com 10 hosts cada (192.168.127.0/25)

-   Precisamos de 4 bits para 10 hosts (2^4 - 2 = 14 hosts).
-   Novo prefixo: /28 (255.255.255.240)

Sub-redes:

1.  192.168.127.0/28

    -   Endereço de rede: 192.168.127.0
    -   Endereço de broadcast: 192.168.127.15
    -   Máscara: 255.255.255.240
2.  192.168.127.16/28

    -   Endereço de rede: 192.168.127.16
    -   Endereço de broadcast: 192.168.127.31
    -   Máscara: 255.255.255.240

### 9\. Esquema de sub‐redes (172.16.15.0/24)

-   Rede A: 50 hosts

    -   Prefixo: /26
    -   Rede: 172.16.15.0
    -   Broadcast: 172.16.15.63
    -   Máscara: 255.255.255.192
-   Rede B: 30 hosts

    -   Prefixo: /27
    -   Rede: 172.16.15.64
    -   Broadcast: 172.16.15.95
    -   Máscara: 255.255.255.224
-   Rede C: 25 hosts

    -   Prefixo: /27
    -   Rede: 172.16.15.96
    -   Broadcast: 172.16.15.127
    -   Máscara: 255.255.255.224
-   Rede D: 6 hosts

    -   Prefixo: /29
    -   Rede: 172.16.15.128
    -   Broadcast: 172.16.15.135
    -   Máscara: 255.255.255.248
-   Rede E: 2 hosts

    -   Prefixo: /30
    -   Rede: 172.16.15.136
    -   Broadcast: 172.16.15.139
    -   Máscara: 255.255.255.252

### 10\. Esquema de endereçamento (10.10.0.0/16)

-   Rede A: 500 hosts

    -   Prefixo: /23
    -   Rede: 10.10.0.0
    -   Broadcast: 10.10.1.255
    -   Máscara: 255.255.254.0
-   Rede B: 250 hosts

    -   Prefixo: /24
    -   Rede: 10.10.2.0
    -   Broadcast: 10.10.2.255
    -   Máscara: 255.255.255.0
-   Rede C: 100 hosts

    -   Prefixo: /25
    -   Rede: 10.10.3.0
    -   Broadcast: 10.10.3.127
    -   Máscara: 255.255.255.128
-   Rede E: 64 hosts

    -   Prefixo: /26
    -   Rede: 10.10.3.128
    -   Broadcast: 10.10.3.191
    -   Máscara: 255.255.255.192
-   Rede D: 60 hosts

    -   Prefixo: /26
    -   Rede: 10.10.3.192
    -   Broadcast: 10.10.3.255
    -   Máscara: 255.255.255.192

### 11\. Diagrama da rede da empresa XPTO

Para a rede de classe C 192.168.150.0:

-   Rede A (60 hosts)

    -   Prefixo: /26
    -   Rede: 192.168.150.0
    -   Broadcast: 192.168.150.63
    -   Máscara: 255.255.255.192
-   Rede B (30 hosts)

    -   Prefixo: /27
    -   Rede: 192.168.150.64
    -   Broadcast: 192.168.150.95
    -   Máscara: 255.255.255.224
-   Rede C (20 hosts)

    -   Prefixo: /27
    -   Rede: 192.168.150.96
    -   Broadcast: 192.168.150.127
    -   Máscara: 255.255.255.224
-   Rede D (14 hosts)

    -   Prefixo: /28
    -   Rede: 192.168.150.128
    -   Broadcast: 192.168.150.143
    -   Máscara: 255.255.255.240
-   Rede de Interligação (2 hosts)

    -   Prefixo: /30
    -   Rede: 192.168.150.144
    -   Broadcast: 192.168.150.147
    -   Máscara: 255.255.255.252

### 12\. Atribuição de IPs a interfaces

| Equipamento | Interface | Endereço IP | Máscara | Gateway |
| --- | --- | --- | --- | --- |
| R1 | E0 | 192.168.150.1 | 255.255.255.192 | 192.168.150.62 |
| R1 | E1 | 192.168.150.145 | 255.255.255.252 |  |
| R2 | E0 | 192.168.150.146 | 255.255.255.252 | 192.168.150.145 |
| R2 | E1 | 192.168.150.65 | 255.255.255.224 |  |
| R2 | E2 | 192.168.150.97 | 255.255.255.224 |  |
| R2 | E3 | 192.168.150.129 | 255.255.255.240 |  |
| PC A |  | 192.168.150.2 | 255.255.255.192 | 192.168.150.1 |
| PC B |  | 192.168.150.66 | 255.255.255.224 | 192.168.150.65 |
| PC C |  | 192.168.150.98 | 255.255.255.224 | 192.168.150.97 |
| PC D |  | 192.168.150.130 | 255.255.255.240 | 192.168.150.129 |

Estas soluções cobrem as diversas questões relacionadas a endereçamento IP, sub-redes e roteamento solicitadas.
