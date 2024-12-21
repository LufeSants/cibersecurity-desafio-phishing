# Simulação de Phishing: Captura de Credenciais do Facebook
Usaremos o Kali Linux e o Social-Engineer Toolkit (SEToolkit), uma poderosa ferramenta de código aberto projetada para testes de segurança e engenharia social. Vamos simular um ataque de phishing para capturar credenciais do Facebook.

### Requisitos
* Kali Linux
* SEToolkit

### Configurando o Phishing no Kali Linux
* Acesso root: `sudo su`
* Iniciando o SEToolkit: `setoolkit`
* Tipo de ataque: `1` `Social-Engineering Attacks`
* Vetor de ataque: `2` `Website Attack Vectors`
* Método de ataque: `3` `Credential Harvester Attack Method`
* Importação personalizada: `3` `Custom Import`
* Para simular o ataque, sua máquina virtual deve estar configurada no modo Bridge. Por exemplo: `192.168.1.6`
* Arquivo de teste contendo um clone do Facebook: [index.html](https://github.com/LufeSants/cibersecurity-desafio-phishing/blob/main/index.html)
* Indique o caminho onde você salvou o arquivo index.html. Por exemplo: `/home/kali/Downloads/index.html`
* URL do site que você importou: http://www.facebook.com
 
### Resultado da captura de credenciais
![Texto alternativo](https://github.com/LufeSants/cibersecurity-desafio-phishing/blob/main/credentials.png?raw=true)
