<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Jo%C3%A3o%20Victor%20Soares&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Sistemas%20Embarcados%20%C2%B7%20APIs%20%C2%B7%20Backend%20%C2%B7%20DevOps&descSize=16&descAlignY=60" alt="Banner João Victor Soares" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1200&color=4FC3F7&center=true&vCenter=true&width=640&lines=Desenvolvedor+J%C3%BAnior+em+S%C3%A3o+Carlos%2C+SP;Firmware+em+C+e+C%2B%2B+para+ESP32;APIs+REST+com+Flask+e+Spring+Boot;Docker+e+Kubernetes+na+pr%C3%A1tica;Do+ch%C3%A3o+de+f%C3%A1brica+ao+c%C3%B3digo" alt="Digitando: Desenvolvedor Júnior, firmware, APIs, Docker e Kubernetes" />
</a>

<br>

<img src="https://img.shields.io/badge/ADS-SENAI%20(cursando)-0e75b6?style=for-the-badge" alt="ADS no SENAI, cursando" />
<img src="https://img.shields.io/badge/T%C3%A9cnico%20em-Mecatr%C3%B4nica-2c5364?style=for-the-badge" alt="Técnico em Mecatrônica" />
<img src="https://img.shields.io/badge/Ingl%C3%AAs-intermedi%C3%A1rio-4c9a2a?style=for-the-badge" alt="Inglês intermediário" />

<br><br>

<a href="mailto:jvtrgmlcmsoares@gmail.com"><img src="https://img.shields.io/badge/E--mail-jvtrgmlcmsoares%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="E-mail" /></a>
<img src="https://komarev.com/ghpvc/?username=joaoVictor-Soares&label=Visitas&color=0e75b6&style=flat-square" alt="Contador de visitas" />

</div>

---

## 👋 Sobre mim

Sou **desenvolvedor júnior** e estudante de **Análise e Desenvolvimento de Sistemas no SENAI** (2025–2026), com formação técnica em **Mecatrônica**. Minha trajetória começou no chão de fábrica, em manutenção industrial e validação de hardware, e foi migrando para o software. Isso me deu um jeito de trabalhar em que **hardware, firmware, backend e infraestrutura conversam entre si**.

- 🔧 Construo **firmware em C/C++** (ESP32, PlatformIO) com máquinas de estado, interrupções e I2C.
- 🌐 Crio e integro **APIs REST** com **Flask** e **Spring Boot**.
- 🐳 Containerizo com **Docker** e subo serviços em **Kubernetes**.
- 📱 Já entreguei interfaces **web (React)** e **mobile (React Native)** em projetos de equipe.
- 🤖 Tenho experiência com **visão computacional e IA na borda** (TensorFlow Lite / PyTorch em Raspberry Pi).

---

## 🚀 Projetos em destaque

### 🏭 Inspeção Automatizada de Peças com IA e IoT
[![Repositório](https://img.shields.io/badge/ver%20reposit%C3%B3rio-projeto--integrador--4termo-181717?style=flat-square&logo=github)](https://github.com/joaoVictor-Soares/projeto-integrador-4termo)

Projeto integrador do 4º termo: uma solução ponta a ponta para **inspecionar peças em uma esteira pneumática em tempo real** e **desviar automaticamente as reprovadas**.

- **CLP Siemens S7-1500** faz o controle determinístico dos sensores e atuadores (sensores ópticos, indutivo, capacitivo e de cor, cilindros e motor).
- **Raspberry Pi (edge)** roda uma API em **Spring Boot**, conversa com o CLP via **OPC-UA**, aciona a câmera e classifica a peça com um modelo de ML.
- **App React Native** mostra ao operador a foto, o status da peça e o histórico da produção.
- Resultados e fotos das peças reprovadas ficam registrados em banco de dados, com o modelo de dados documentado (DER).

`Java` `Spring Boot` `Raspberry Pi` `OPC-UA` `TensorFlow Lite` `PyTorch` `React Native` `Docker`

### 🎓 Plataforma de Gestão de Capacitação Corporativa
[![Repositório](https://img.shields.io/badge/ver%20reposit%C3%B3rio-projetoIntegrador--3Semestre-181717?style=flat-square&logo=github)](https://github.com/joaoVictor-Soares/projetoIntegrador-3Semestre)

Plataforma **web e mobile** que centraliza trilhas de aprendizado, com acesso separado para **funcionário** e **RH**.

- **API em Flask** com login, cadastro, busca de cursos, inscrições e acompanhamento de cursos realizados.
- **Upload, listagem e download de certificados** (imagens e PDFs).
- **Painel do RH** para gestão de colaboradores e dashboards de desempenho.
- Front-end **React** (web) e **React Native** (mobile), banco **MySQL** e ambiente inteiro orquestrado com **Docker Compose**, incluindo healthcheck do banco.

`Python` `Flask` `React` `React Native` `MySQL` `Docker Compose`

### 🔌 Portfólio de Firmware
[![Repositório](https://img.shields.io/badge/ver%20reposit%C3%B3rio-PORTIFOLIO--FIRMWARE-181717?style=flat-square&logo=github)](https://github.com/joaoVictor-Soares/PORTIFOLIO-FIRMWARE)

Coleção de projetos de firmware que mostram os fundamentos de sistemas embarcados:

| Projeto | O que demonstra |
|---|---|
| **RFID Industrial** | ESP32 + leitor **MFRC522** + display OLED + servo. Envia as leituras por Wi-Fi/HTTP para uma API Flask que guarda o histórico de acessos. |
| **Semáforo com interrupção** | Botão de pedestre tratado por **interrupção** (`IRAM_ATTR`), com *debounce* e temporização sem bloquear o loop. |
| **Termômetro com I2C** | Sensor **DHT22** exibido em um display **SSD1306** pelo barramento **I2C**. |
| **Máquinas de estado** | Três implementações de FSM em C: `switch/case`, **ponteiro de função** e **tabela de transição** com `enum`. |

`C` `C++` `ESP32` `PlatformIO` `I2C` `RFID` `FSM` `Flask`

### ☸️ Infraestrutura e Microsserviços

| Projeto | Descrição | Stack |
|---|---|---|
| [**microservicos-kubernetes**](https://github.com/joaoVictor-Soares/microservicos-kubernetes) | Sistema de produtos e pedidos dividido em **três serviços** (frontend, produto e pedido), cada um com seu Dockerfile e manifestos Kubernetes. | `Flask` `PostgreSQL` `Docker` `Kubernetes` |
| [**sistemaMonitoramentoIndustrialEmContainers**](https://github.com/joaoVictor-Soares/sistemaMonitoramentoIndustrialEmContainers) | Monitoramento industrial em containers: um serviço de **sensor**, um de **coleta** com histórico em banco e um **dashboard**. Tem manifestos K8s com Namespace, ConfigMap, Secret e PVC. | `Flask` `PostgreSQL` `Docker` `Kubernetes` |

### 💼 Outros projetos

- 🛒 [**sistema-vendas**](https://github.com/joaoVictor-Soares/sistema-vendas) — Sistema de vendas em **Spring Boot** (JPA, Thymeleaf, Spring Security com perfis de usuário, PostgreSQL e Docker), com cadastro de clientes e produtos e controle de pedidos.
- 🏥 [**proj-clinica-springmed**](https://github.com/joaoVictor-Soares/proj-clinica-springmed) — App mobile de agendamento para clínica médica, em **React Native + Expo**, com login por **biometria**, câmera/galeria e consulta de CEP. Desenvolvido em dupla e ainda em evolução.
- 📡 [**MQTT-PYTHON-Csharp**](https://github.com/joaoVictor-Soares/MQTT-PYTHON-Csharp) — Comunicação via **MQTT** entre Python e uma aplicação **C# (Windows Forms)**.

---

## 🛠️ Stack

**Sistemas embarcados**

![C](https://skillicons.dev/icons?i=c,cpp,arduino,raspberrypi,platformio&theme=dark)

**Backend e APIs**

![Backend](https://skillicons.dev/icons?i=py,flask,fastapi,java,spring,cs,dotnet&theme=dark)

**Front-end e mobile**

![Front](https://skillicons.dev/icons?i=js,react,html,css&theme=dark)

**Banco de dados**

![DB](https://skillicons.dev/icons?i=postgres,mysql,sqlite&theme=dark)

**Infraestrutura e DevOps**

![DevOps](https://skillicons.dev/icons?i=docker,kubernetes,aws,linux,git,github&theme=dark)

**Dados e IA**

![Dados](https://skillicons.dev/icons?i=tensorflow,pytorch,powerbi&theme=dark)

---

## 💼 Experiência

| Período | Papel | O que fiz |
|---|---|---|
| **Jul–Ago/2025** | Ajustador Mecânico de Bancada (Hardware & P&D) — **Eyetec** | Validação de sistemas embarcados e diagnóstico de falhas lógicas e estruturais, na interface entre hardware e software. Trabalho direto com as equipes de Hardware, Software e P&D, com relatórios técnicos e documentação. |
| **Abr–Out/2024** | Auxiliar de Manutenção Industrial — **Wama Diagnóstica** | Sustentação técnica de sistemas automatizados, gestão de chamados e SLAs via GLPI e documentação operacional. |

---

## 📊 GitHub

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=joaoVictor-Soares&show_icons=true&theme=tokyonight&hide_border=true&locale=pt-br" alt="Estatísticas do GitHub" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=joaoVictor-Soares&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Linguagens mais usadas" />

</div>

---

<div align="center">

💬 **Aberto a oportunidades de estágio e vaga júnior** em desenvolvimento de software, backend e sistemas embarcados.
<br>
Vamos conversar: [jvtrgmlcmsoares@gmail.com](mailto:jvtrgmlcmsoares@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=100&section=footer" alt="Rodapé" />

</div>
