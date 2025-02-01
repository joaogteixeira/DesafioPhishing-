# Desafio de Phishing para Captura de Senhas do Facebook

Este repositório contém um guia prático para simular um ataque de phishing com o objetivo de capturar senhas do Facebook. O projeto é voltado para fins educacionais e de conscientização sobre segurança cibernética.

## Ferramentas Utilizadas
- **Kali Linux**: Distribuição Linux focada em segurança e testes de penetração.
- **setoolkit** (Social-Engineer Toolkit): Ferramenta para simular ataques de engenharia social.

## Configurando o Phishing no Kali Linux

### Passo a Passo

1. **Acesso root**:
   Abra o terminal e execute o comando abaixo para acessar como superusuário:
   ```bash
   sudo su
Iniciando o setoolkit:
No terminal, execute o seguinte comando para iniciar a ferramenta:

bash
Copy
setoolkit
Selecionando o tipo de ataque:
Escolha a opção 1) Social-Engineering Attacks.

Escolhendo o vetor de ataque:
Selecione 2) Web Site Attack Vectors.

Definindo o método de ataque:
Escolha 3) Credential Harvester Attack Method.
Em seguida, selecione 2) Site Cloner.

Obtendo o endereço da máquina:
No terminal, execute o comando abaixo para obter o endereço IP da sua máquina:

**ifconfig**
Anote o endereço IP exibido (ex: 192.168.1.100).

Clonando o site do Facebook:
Insira o endereço IP da sua máquina quando solicitado.
Informe a URL do site a ser clonado: http://www.facebook.com.

Pronto!:
O setoolkit criará um clone do Facebook no seu endereço IP.
Quando alguém acessar o endereço IP da sua máquina e inserir suas credenciais, elas serão capturadas.

Como Funciona
O setoolkit clona a página de login do Facebook e hospeda localmente na sua máquina. Quando a vítima insere seu e-mail e senha, os dados são capturados e exibidos no terminal.

Aviso Importante
Este projeto é apenas para fins educacionais. O uso indevido dessa técnica para capturar informações sem consentimento é ilegal e antiético. Utilize esse conhecimento de forma responsável e sempre com permissão explícita.

