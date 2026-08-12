# Olá, eu sou Lucas 👋

### Python Developer | Automação • APIs • Integrações

👨‍💻 Sobre mim

Sou desenvolvedor Python e venho construindo minha experiência principalmente através de projetos práticos.

No meu dia a dia, trabalho com problemas que envolvem automação, integração entre sistemas, APIs, bancos de dados e infraestrutura. Ao longo desses projetos, tive a oportunidade de desenvolver desde pequenos scripts de automação até aplicações que fazem parte de processos utilizados em ambientes reais.

Gosto especialmente de entender como um sistema funciona, encontrar uma forma de integrá-lo ou automatizar uma tarefa e transformar isso em uma solução que realmente facilite o trabalho de quem vai utilizá-la.

Atualmente estou aprofundando meus conhecimentos em Python, principalmente em Programação Orientada a Objetos, boas práticas de desenvolvimento e Git.

---

## 🚀 Projetos

### 💰 Tarifador — Automação de Faturamento

Aplicação desenvolvida em Python para automatizar o processo de faturamento de clientes utilizando dados do Magnus Billing.

A aplicação consulta o banco de dados do sistema, processa informações das ligações utilizando Pandas e gera planilhas detalhadas em Excel. Posteriormente, integra-se à API do ASAAS para criação das cobranças e emissão das notas fiscais.

O processo também possui uma rotina automatizada através do Cron para execução no último dia de cada mês.

**Tecnologias:**

`Python` `MySQL` `Pandas` `OpenPyXL` `REST API` `ASAAS` `Linux` `Cron`

🔒 **Projeto privado** — envolve sistemas e infraestrutura de ambiente real.

---

### 💳 Gateway de Recargas — Magnus Billing + ASAAS

Integração desenvolvida para permitir recargas de linhas VoIP pré-pagas através do ASAAS em um ambiente onde o Magnus Billing não disponibilizava integração nativa com a plataforma.

A solução foi desenvolvida a partir da análise do funcionamento das integrações de pagamento existentes no Magnus Billing. Através da identificação do formato das requisições enviadas pelo sistema, foi desenvolvida uma API capaz de atuar como gateway intermediário.

A aplicação utiliza Flask para receber e processar as solicitações, armazena os dados em MySQL e integra-se à API do ASAAS para geração das cobranças.

Um endpoint de Webhook recebe as confirmações de pagamento do ASAAS e, após a confirmação, o sistema processa a recarga do cliente.

**Tecnologias:**

`Python` `Flask` `MySQL` `REST API` `Webhooks` `ASAAS` `HTML` `CSS` `JavaScript`

🔒 **Projeto privado** — envolve integração com sistema proprietário e ambiente real.

---

### 🔎 Localizador de ONU — FiberHome

Aplicação cliente/servidor desenvolvida em Python para auxiliar equipes de infraestrutura na localização de ONUs em OLTs FiberHome através do endereço MAC da WAN do cliente.

O cliente estabelece uma conexão TCP/IP com o servidor, que realiza uma validação do endereço IP de origem antes de aceitar a conexão.

Após a validação, o servidor recebe e valida o MAC informado e inicia a pesquisa simultânea nas OLTs utilizando múltiplas threads.

As conexões com as OLTs são realizadas pelo servidor, mantendo o acesso à infraestrutura centralizado. Quando uma ONU é encontrada, o sistema retorna informações como OLT, VLAN, placa, PON e ONU.

A aplicação também permite realizar consultas adicionais, como verificação de sinal e alteração de VLAN.

O cliente foi posteriormente convertido em executável Windows para facilitar sua distribuição e utilização pelas equipes internas.

**Tecnologias:**

`Python` `TCP/IP` `Sockets` `Multithreading` `Telnet` `Pexpect` `FiberHome`

🔒 **Projeto privado** — envolve infraestrutura e ambiente de produção.

---

### 🚗 OLX Images Downloader — Automação Web

Ferramenta de automação web desenvolvida em Python para solucionar uma necessidade operacional de uma empresa do setor automotivo.

A aplicação recebe a URL de um anúncio, utiliza Selenium WebDriver em modo headless para acessar a página e localizar as imagens disponíveis e posteriormente utiliza Requests para realizar o download dos arquivos.

O projeto possui tratamento de entrada, espera explícita de elementos, interação com elementos através de JavaScript e criação automática do diretório de destino.

**Tecnologias:**

`Python` `Selenium` `Requests` `WebDriver` `Pathlib`

🔓 **[Repositório público](https://github.com/LucasBMH/olx-image-downloader)**

---

## 🛠️ Tecnologias e conhecimentos

### 🐍 Python

* Desenvolvimento de scripts e aplicações
* Programação Orientada a Objetos
* Automação de tarefas
* Integração com APIs
* Manipulação e processamento de dados
* Automação web
* Comunicação cliente/servidor
* Multithreading

### 📚 Bibliotecas e frameworks

`Flask` `Pandas` `Selenium` `Requests` `OpenPyXL` `MySQL Connector` `Pexpect`

### 🌐 APIs e Web

`REST APIs` `Webhooks` `HTML` `CSS` `JavaScript`

### 🗄️ Banco de dados

`MySQL` `MariaDB` `SQL`

Experiência com consultas, manipulação e migração de dados.

### 🐧 Sistemas

`Linux` `Windows`

Experiência com Linux principalmente em ambientes de infraestrutura e diagnóstico de problemas de rede.

### 🌐 Redes e Telecom

`TCP/IP` `Sockets` `SIP` `PABX` `Asterisk` `OLT FiberHome`

---

## 📚 Atualmente estudando

* Aperfeiçoamento em Python
* Programação Orientada a Objetos
* Boas práticas de desenvolvimento
* Git e versionamento de código
* Desenvolvimento de aplicações e APIs

---

## Objetivo profissional

Estou buscando minha primeira oportunidade profissional como Desenvolvedor Júnior.

Quero trabalhar em um ambiente onde possa continuar evoluindo como desenvolvedor, aprender com pessoas mais experientes e, ao mesmo tempo, colocar em prática o conhecimento que venho adquirindo através dos meus projetos.

Tenho interesse principalmente em desenvolvimento Python, backend, automação, APIs e integração de sistemas

---

## 📫 Contato

📧 **Email:** [lucasbmhumberto@gmail.com](mailto:lucasbmhumberto@gmail.com)

💼 **LinkedIn:** [Meu LinkedIn](https://www.linkedin.com/in/lucas-buss-160397265/)

🐙 **GitHub:** [Lucas](https://github.com/SEU_USUARIO](https://github.com/LucasBMH))

---

> 🔒 Alguns projetos apresentados neste perfil são privados por envolverem sistemas proprietários, integrações com terceiros e infraestrutura de ambientes reais. As descrições apresentam as tecnologias utilizadas e os problemas solucionados sem expor informações sensíveis.
