# Configurar Router

## Configuração Base
Parte 1: Definir configurações básicas
a. Configure o nome do dispositivo conforme mostrado na topologia.
```
enable
config t
```
b. Configure o endereço IP conforme listado na Tabela de Endereçamento.
```
hostname
```
```
interface g0/0
ip address 10.10.10.2 255.255.255.0
no shut
```
```
line con 0
password cisco
login
```
c. Atribua cisco como password do console e vty.
```
line vty 0 4
password cisco
login
```
d. Atribuir classe como senha EXEC privilegiada<by>
senha do router normalmente é sempre class
```
enable secret class
```
![image](https://github.com/FaculdadeLicenciatura/Seguranca-de-Redes-e-Sistemas/assets/50460047/e173a8f8-9ddf-4bd5-8dc8-de3f55855404)

# Secure Passwords
Part 2: Secure Passwords
a. Usar o prompt de comando no PC0, faça Telnet para o router01.
![Captura de ecrã 2024-02-21 153814](https://github.com/FaculdadeLicenciatura/Seguranca-de-Redes-e-Sistemas/assets/50460047/ecb6c204-d0a4-4644-8c95-8415bbb5241c)
![image](https://github.com/FaculdadeLicenciatura/Seguranca-de-Redes-e-Sistemas/assets/50460047/0311acb0-23ff-45e4-b11e-194a75500ea9)
![Captura de ecrã 2024-02-21 153843](https://github.com/FaculdadeLicenciatura/Seguranca-de-Redes-e-Sistemas/assets/50460047/2fc42f23-bebf-4ed3-af17-be334703ef96)
<br> b. Guardar a configuração atual para que quaisquer erros que você possa cometer possam ser revertidos alternando o
energia para o router1.
sniffer
![image](https://github.com/FaculdadeLicenciatura/Seguranca-de-Redes-e-Sistemas/assets/50460047/ee0ecf8d-3ca2-49f8-8965-f31b045e5f35)

c. Mostrar a configuração atual e observa que as passwords estão em texto simples.
```
enable class
Router1(config)# service password-encryption
```
