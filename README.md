<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:2C5364,100:2F80ED&height=220&section=header&text=João%20Carlos&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Desenvolvedor%20Backend%20%7C%20Analista%20de%20Sistemas&descAlignY=55&descSize=20" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=2F80ED&center=true&vCenter=true&width=750&lines=Desenvolvedor+Backend+Java+%2B+Spring;Analista+de+Sistemas+com+foco+em+solu%C3%A7%C3%B5es+e+arquitetura;Testes%2C+infraestrutura+e+entrega+automatizada;Seguran%C3%A7a+de+ponta+a+ponta" />

<br/>

<img src="https://img.shields.io/badge/Status-Disponível_para_oportunidades-2F80ED?style=for-the-badge&labelColor=0F2027" />
<img src="https://komarev.com/ghpvc/?username=joao4692&style=for-the-badge&color=2F80ED&label=Visualizações" />

</div>

<br/>

```java
public class JoaoCarlos {

    String   titulo = "Desenvolvedor Backend | Analista de Sistemas";
    String   foco   = "Soluções e arquitetura";
    String[] base   = { "Java", "Spring", "Padrões de arquitetura" };
    String[] alem   = { "Infraestrutura", "Testes", "Entrega automatizada", "Segurança" };

}
```

## Sobre mim

Sou **desenvolvedor backend Java**, com base em **Spring** e em **padrões de arquitetura**. Além de desenvolver, acompanho o sistema por inteiro: como ele é desenhado, testado, colocado em produção e protegido.

Por isso me aprofundo no que sustenta uma aplicação além do código: **arquitetura de soluções**, **infraestrutura**, **testes** e a automação do caminho entre o commit e a produção. Somo a isso noções de **cibersegurança**, aplicadas de ponta a ponta, da validação de dados na API ao hardening do servidor.

No dia a dia, estou sempre testando, analisando sistemas e buscando a solução mais adequada para cada problema. É o olhar de **analista de sistemas** somado ao de desenvolvedor.

Comecei no Full Stack com **Node.js, TypeScript e React**, entregando aplicações reais para clientes. Essa experiência me deu visão do sistema completo e facilitou minha evolução no ecossistema Java.

Estou aberto a oportunidades como **Desenvolvedor Backend Java**, com foco em evolução contínua e participação em produtos reais.

<br/>

## Especialidade

<div align="center">

<img src="https://skillicons.dev/icons?i=java,spring,postgres,git,docker&theme=dark" />

</div>

<div align="center">

**Desenvolvimento backend em Java + Spring**

</div>

<br/>

## Além do código

<table>
<tr>
<td valign="top" width="33%">

**Arquitetura & Soluções**

Padrões de arquitetura, separação em camadas, modelagem de dados e análise de sistemas para chegar à solução certa antes de escrever código

</td>
<td valign="top" width="33%">

**Testes & Qualidade**

Testes como parte do desenvolvimento, validação de regras de negócio e análise constante do comportamento do sistema

</td>
<td valign="top" width="33%">

**Infraestrutura & Segurança**

Docker, VPS Linux, entrega automatizada do commit à produção e hardening de servidores, com noções de cibersegurança

</td>
</tr>
</table>

<br/>

<div align="center">

**Base complementar**

<img src="https://skillicons.dev/icons?i=nodejs,express,ts,react,angular,python,linux,github&theme=dark" height="35"/>

Node.js, TypeScript, React, Angular e Python: stack anterior, com domínio de arquitetura mantido

</div>

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

- Sistemas backend em Java + Spring
- Padrões de arquitetura e desenho de soluções
- Testes automatizados e análise de sistemas
- Entrega automatizada com Docker e hardening de servidores (VPS Linux, Render, Hostinger)
- Segurança aplicada ao ciclo completo da aplicação

<br/>

## Arquitetura & Princípios

| Princípio | Descrição |
|---|---|
| Código limpo | Organização e legibilidade em primeiro lugar |
| Separação de responsabilidades | Camadas bem definidas (controller/service/repository) |
| Estrutura escalável | Backend pensado para crescer sem retrabalho |
| Testes | Comportamento validado antes de chegar à produção |
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

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1500&color=2F80ED&center=true&vCenter=true&width=500&lines=Dispon%C3%ADvel+para+oportunidades;Desenvolvedor+Backend+%7C+Analista+de+Sistemas" />

</div>
