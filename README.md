<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:2C5364,100:2F80ED&height=220&section=header&text=João%20Carlos&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Java%20Developer&descAlignY=55&descSize=20" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=2F80ED&center=true&vCenter=true&width=750&lines=Java+Developer+em+especializa%C3%A7%C3%A3o+com+Spring;Base+s%C3%B3lida+em+arquitetura%2C+banco+de+dados+e+deploy;An%C3%A1lise+de+dados+com+SQL+e+Python;Constru%C3%A7%C3%A3o+de+sistemas+web+completos" />

<br/>

<img src="https://img.shields.io/badge/Status-Disponível_para_oportunidades-2F80ED?style=for-the-badge&labelColor=0F2027" />
<img src="https://komarev.com/ghpvc/?username=joao4692&style=for-the-badge&color=2F80ED&label=Visualizações" />

</div>

<br/>

## Sobre mim

Comecei minha jornada como desenvolvedor Full Stack com **Node.js, TypeScript e React**, construindo aplicações reais para clientes e desenvolvendo uma base sólida em arquitetura de software, banco de dados, Git, Docker e deploy de aplicações.

Ao aprofundar meus estudos em **Java**, percebi que essa base de arquitetura e boas práticas — já consolidada — me permitiu evoluir rápido na linguagem. Isso me fez decidir seguir carreira como **Desenvolvedor Java**, hoje minha especialidade principal com o ecossistema **Spring**.

Estou me especializando para ser um desenvolvedor completo: além de programar sistemas em Java/Spring, busco domínio em **análise de dados** (SQL avançado, Python, dashboards) e em fazer um **deploy de aplicações bem feito** (Docker, CI/CD, hardening de servidores).

Busco oportunidades como **Desenvolvedor Java Júnior**, com foco em evolução contínua e participação em produtos reais.

<br/>

## Especialidade

<div align="center">

<img src="https://skillicons.dev/icons?i=java,spring,postgres,git,docker&theme=dark" />

</div>

<div align="center">

**Programação de sistemas em Java + Spring**

</div>

<br/>

## Pilares Complementares

<table>
<tr>
<td valign="top" width="33%">

**Análise de Dados**

<img src="https://skillicons.dev/icons?i=python,postgres&theme=dark" height="35"/>

SQL avançado, bancos relacionais, dashboards, Python (pandas, OpenCV)

</td>
<td valign="top" width="33%">

**DevOps & Deploy**

<img src="https://skillicons.dev/icons?i=docker,linux,git,github&theme=dark" height="35"/>

Docker, CI/CD, VPS Linux (Hostinger), hardening de servidores

</td>
<td valign="top" width="33%">

**Full Stack (base)**

<img src="https://skillicons.dev/icons?i=nodejs,express,react,angular,ts&theme=dark" height="35"/>

Node.js, TypeScript, React, Angular — stack anterior, domínio de arquitetura mantido

</td>
</tr>
</table>

<br/>

## Projetos Relevantes

### Sistema de Estacionamento Inteligente

Sistema de monitoramento de vagas em tempo real usando visão computacional para detectar entrada e saída de veículos, integrado a um backend event-driven e um painel Angular com atualização ao vivo.

**Repositório:** [github.com/joao4692/camera-monitoramento](https://github.com/joao4692/camera-monitoramento)

**Descrição técnica:**
Serviço em Python com YOLO + OpenCV processa o stream de vídeo (câmera via RTSP na versão de produção; câmera de celular na fase de testes) e detecta eventos de entrada/saída, enviados via WebSocket para um backend Node.js. O backend valida, aplica as regras de negócio e persiste os eventos no Postgres via Prisma, atualizando o frontend Angular em tempo real.

**Stack utilizada:**

<img src="https://skillicons.dev/icons?i=python,opencv,nodejs,express,ts,angular,postgres,prisma&theme=dark" height="40" />

**Responsabilidades técnicas:**
- Arquitetura MVC + Repositories no backend
- Comunicação em tempo real Python → Node.js → Angular via WebSocket
- Modelagem de dados (Estacionamento, Evento, Usuário) com Prisma
- Autenticação JWT para área administrativa e tela pública sem login
- Validação de payloads com Zod e tratamento global de erros
- Otimização para hardware sem GPU (processamento em CPU)

**Destaques:**
- Arquitetura desacoplada: câmera física pode ser trocada sem impactar backend/frontend
- Fluxo de dados em tempo real ponta a ponta (visão computacional → banco → UI)
- Documentação técnica própria guiando escopo e decisões do projeto

<br/>

### Sistema de Gestão para Clínica de Terapia

Monorepo completo para gestão de clínica de terapia, com acompanhamento de evolução de pacientes.

**Descrição técnica:**
Aplicação com três perfis de usuário (Admin, Terapeuta, Responsável) e um motor de pontuação (scoring engine) para acompanhamento de habilidades dos pacientes ao longo do tratamento.

**Stack utilizada:**

<img src="https://skillicons.dev/icons?i=nextjs,express,postgres,prisma,docker&theme=dark" height="40" />

**Responsabilidades técnicas:**
- Modelagem de dados e regras de negócio por perfil de acesso (ADMIN / THERAPIST / PARENT)
- Motor de pontuação para acompanhamento de evolução dos pacientes
- Deploy completo em VPS (Hostinger) via Docker

<br/>

### Esportefull — Plataforma de Gestão Esportiva

Sistema completo para gerenciamento de competições, times e instituições esportivas.

**Repositório:** [github.com/joao4692/Esportefull](https://github.com/joao4692/Esportefull)

**Responsabilidades técnicas:**
- Estruturação de backend
- Modelagem de dados e entidades
- Regras de negócio para competições
- Organização de fluxo de informações

**Destaques:**
- Sistema escalável e modular
- Foco em backend e lógica de aplicação

<br/>

### Em evolução

- Sistemas em Java + Spring
- Análise de dados com SQL avançado e dashboards
- Automação e visão computacional com Python (OpenCV, pandas)
- Deploy de aplicações com Docker, CI/CD e hardening de servidores (VPS Linux, Render, Hostinger)

<br/>

## Arquitetura & Princípios

| Princípio | Descrição |
|---|---|
| Código limpo | Organização e legibilidade em primeiro lugar |
| Separação de responsabilidades | Camadas bem definidas (controller/service/repository) |
| Estrutura escalável | Backend pensado para crescer sem retrabalho |
| Segurança | Hardening de servidores como prática padrão em todo deploy |
| Performance | Atenção a queries, cache e boas práticas de API |

<br/>

## GitHub Stats

<div align="center">

<img src="https://skillicons.dev/icons?i=java,spring,nodejs,ts,react,angular,postgres,docker,python,git&theme=dark" height="60"/>

<br/><br/>

<img src="https://img.shields.io/github/stars/joao4692?style=for-the-badge&color=2F80ED&labelColor=0F2027" />
<img src="https://img.shields.io/github/followers/joao4692?style=for-the-badge&color=2F80ED&labelColor=0F2027" />

</div>

<br/>

## Contato Profissional

<div align="center">

<a href="https://www.linkedin.com/in/joao-carlos-leite-da-silva-452319333">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://wa.me/5581987033735">
  <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
</a>
<a href="https://github.com/joao4692">
  <img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="https://joaocarlosdev.com">
  <img src="https://img.shields.io/badge/Portfólio-2F80ED?style=for-the-badge&logo=googlechrome&logoColor=white"/>
</a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1500&color=2F80ED&center=true&vCenter=true&width=500&lines=Dispon%C3%ADvel+para+oportunidades;Java+Developer+em+especializa%C3%A7%C3%A3o" />

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2F80ED,100:0F2027&height=100&section=footer" />
