<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:0F2A44,100:00B4D8&height=230&section=header&text=João%20Carlos&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Analista%20Desenvolvedor&descAlignY=56&descSize=19" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&pause=1000&color=00B4D8&center=true&vCenter=true&width=760&lines=%3E+Interfaces+com+React+%2B+TypeScript;%3E+APIs+REST+com+Node.js+e+Express;%3E+IA+em+produ%C3%A7%C3%A3o+com+seguran%C3%A7a+em+camadas;%3E+Backend+em+Java+%2B+Spring;%3E+Python+e+SQL+para+an%C3%A1lise+de+dados" />

</div>

<br/>

```ts
const joao = {
  faz:        "aplicações web completas, da interface ao deploy",
  frontend:   ["React", "TypeScript"],
  backend:    ["Node.js", "Express", "APIs REST"],
  evoluindo:  ["Java", "Spring", "RabbitMQ"],
  dados:      ["Python", "SQL"],
  principio:  "a ferramenta certa para cada problema, com segurança desde o início",
};
```

## Sobre mim

Sou o João, desenvolvedor de Recife. Gosto de construir aplicações que saem do papel e vão para o ar: desenho a interface, escrevo a API, configuro o servidor e acompanho o sistema depois que ele está rodando.

Meu ponto forte hoje é o ecossistema **JavaScript**: interfaces com **React e TypeScript** e APIs com **Node.js e Express**. Em paralelo, estou me aprofundando em **Java com Spring**, já aplicado em um projeto com mensageria e tempo real, e usando **Python e SQL para análise de dados**. Estudo arquitetura de software porque acredito que escolher bem a ferramenta vale tanto quanto saber usá-la.

Uma coisa que levo para todo projeto é **segurança**. O que coloco em produção tem controle de acesso, limite de requisições e validação de dados desde a primeira versão, não como remendo depois.

Desde 2025 trabalho com clientes reais como freelancer, e isso me ensinou que entregar é só metade do trabalho: a outra metade é manter o sistema de pé.

<br/>

## Tecnologias

<div align="center">

**Front-end**

<img src="https://skillicons.dev/icons?i=react,ts,js,html,css,vite&theme=dark" height="48" />

<br/><br/>

**Back-end & Dados**

<img src="https://skillicons.dev/icons?i=nodejs,express,postgres,prisma&theme=dark" height="48" />

<br/><br/>

**DevOps & Deploy**

<img src="https://skillicons.dev/icons?i=git,github,githubactions,docker,linux,vercel&theme=dark" height="48" />

<br/><br/>

**Em evolução**

<img src="https://skillicons.dev/icons?i=java,spring,maven,rabbitmq&theme=dark" height="48" />

<br/><br/>

**Análise de Dados**

<img src="https://skillicons.dev/icons?i=python,postgres&theme=dark" height="48" />

</div>

<br/>

## Projetos

### Estacionamento Inteligente — Backend Java

<img src="https://skillicons.dev/icons?i=java,spring,maven,postgres,rabbitmq,docker&theme=dark" height="32" />

Um sistema que monitora vagas de estacionamento em tempo real usando visão computacional. Uma câmera com OpenCV detecta a entrada e a saída de veículos, o backend aplica as regras de negócio e um painel em Angular mostra a ocupação ao vivo.

Este é o backend, uma nova versão em **Java + Spring Boot** de um projeto que eu tinha escrito em Node.js. O sistema foi pensado desacoplado desde o início: o serviço de detecção em Python, o backend e o frontend vivem em repositórios separados e evoluem de forma independente.

```
câmera (Python + OpenCV) ──► RabbitMQ ──► API Spring ──► PostgreSQL
                                              │
                                              └──► WebSocket ──► painel Angular
```

A API REST é protegida com Spring Security e JWT, persiste dados com Spring Data JPA no PostgreSQL 16 e valida a entrada com Bean Validation. O banco roda em Docker Compose, com credenciais fora do código. Autenticação e gestão de estacionamentos e vagas já estão prontas. Agora estou construindo o recebimento dos eventos pela fila e o envio em tempo real por WebSocket, seguindo um plano de desenvolvimento por etapas documentado no repositório.

Java 17 · Spring Boot 3.3 · Maven · PostgreSQL 16 · RabbitMQ · Docker Compose · `em desenvolvimento`

[`github.com/joao4692/CameraMonitoramento_backend`](https://github.com/joao4692/CameraMonitoramento_backend)

<br/>

### API de Atendimento com IA

<img src="https://skillicons.dev/icons?i=nodejs,express&theme=dark" height="32" />

Um assistente virtual que roda **em produção** no site de uma empresa de segurança eletrônica. Ele tira as dúvidas dos clientes e encaminha quem está realmente interessado, então a equipe de vendas recebe contatos mais qualificados. A IA é o Llama 3.1, servido pela Groq por causa da baixa latência.

Como é uma API pública conectada a um modelo pago, a segurança foi o centro do projeto. Cada requisição passa por camadas que funcionam de forma independente, para que uma continue protegendo mesmo se outra falhar:

```
requisição ──► CORS ──► rate limit ──► validação de origem ──► sanitização ──► IA
```

CORS restrito ao domínio da empresa, limite de 30 requisições por IP a cada 15 minutos, bloqueio de chamadas diretas, validação de origem em middleware próprio e sanitização contra XSS. O histórico e o tamanho das mensagens também são limitados, o que controla o custo e impede manipulação de contexto. A estrutura em rotas, controllers e configuração permite trocar o modelo de IA sem reescrever a API.

[`github.com/joao4692/apiChatBot`](https://github.com/joao4692/apiChatBot)

<br/>

### Portfólio Dev — Template Open Source

<img src="https://skillicons.dev/icons?i=react,ts,vite&theme=dark" height="32" />

Começou como meu portfólio pessoal, com um código que tinha crescido sem organização. Em vez de só arrumar, transformei em um **template open source** (licença MIT) para que outros desenvolvedores possam usar.

A arquitetura foi refeita em componentes reutilizáveis, e todo o conteúdo ficou centralizado em arquivos de dados: quem usa personaliza o site inteiro sem tocar nos componentes. A tipagem com TypeScript faz o build apontar erros nos dados antes de ir para o ar. Tem suporte a português e inglês, tema de cores centralizado e documentação completa.

[`github.com/joao4692/portfolio-template-react`](https://github.com/joao4692/portfolio-template-react)

<br/>

## Atualmente

Cursando **Análise e Desenvolvimento de Sistemas** na Estácio, evoluindo em Java e Spring, Python e SQL para análise de dados, arquitetura hexagonal, testes e CI/CD. Também atuo como voluntário ensinando lógica de programação e informática, o que me obriga a explicar com clareza o que eu mesmo aprendi.

<br/>

<div align="center">

<img src="https://img.shields.io/github/followers/joao4692?style=for-the-badge&color=00B4D8&labelColor=0D1117" />
<img src="https://img.shields.io/github/stars/joao4692?style=for-the-badge&color=00B4D8&labelColor=0D1117" />
<img src="https://komarev.com/ghpvc/?username=joao4692&style=for-the-badge&color=00B4D8&label=VISUALIZAÇÕES" />

</div>

<br/>

## Contato

<div align="center">

<a href="https://www.linkedin.com/in/joao-carlos-silva-452319333">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:contato@joaocarlosdev.com">
  <img src="https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://wa.me/5581987033735">
  <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
</a>
<a href="https://joaocarlosdev.com">
  <img src="https://img.shields.io/badge/Portfólio-00B4D8?style=for-the-badge&logo=googlechrome&logoColor=white"/>
</a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00B4D8,50:0F2A44,100:0D1117&height=110&section=footer" />

</div>
