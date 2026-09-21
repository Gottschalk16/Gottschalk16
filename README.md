<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1694ff,100:53c866&height=160&section=header&text=Raianne%20Gottschalk&fontColor=fff&fontAlignY=35&fontSize=40&desc=Analista%20e%20Programadora%20Full%20Stack&descAlignY=55&descSize=18"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/raianne-gottschalk-408062191" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?lines=Full+Stack+%7C+NextJS+%2B+HeroUI+%2B+NestJS;6+anos+de+experi%C3%AAncia%2C+5+em+Delphi;J%C3%A1+liderei+o+desenvolvimento+de+um+PDV+mobile;font=Fira+Code&center=true&width=560&height=40&color=1694FF&vCenter=true&pause=1500"/>
</p>

---

## 👩‍💻 Sobre mim

Trabalho na área de tecnologia há 6 anos, sendo 5 deles com **Delphi**, e sou apaixonada por programação desde os 15 anos. Hoje atuo do backend ao frontend, participando desde a arquitetura até a entrega das aplicações — já liderei o desenvolvimento de um **produto PDV mobile** do zero para o comércio.

No dia a dia, uso `NextJS` + `HeroUI` (ou `Ant Design`) no frontend e `EggJS` / `NestJS` no backend para os projetos web, além de `Delphi` para sistemas e integrações legadas.

> Atualmente utilizo o **Claude Code** para me auxiliar no desenvolvimento dos meus projetos.

---

## 🚀 Projetos

Sistemas que arquitetei e desenvolvi, sozinha ou liderando o time, em empresas onde trabalhei. São projetos privados/corporativos, por isso sem link público — descritos aqui pelo problema que resolvem.

### 01 · E-commerce próprio
`NextJS` `HeroUI`

Uma empresa de sistemas não possuía módulo de e-commerce para vender aos seus clientes — desenvolvi essa solução do zero. Para reduzir a latência entre o servidor do cliente e o site, dados como empresa, produto, grupo, subgrupo e horário de atendimento são cacheados em arquivos JSON, atualizados automaticamente a cada 1 hora.

### 02 · Integração ERP ↔ IMendes
`Delphi`

Os clientes do ERP (voltada ao varejo de pequenas empresas) tinham dificuldade em manter a tributação de seus produtos atualizada. Conduzi a integração com a IMendes de ponta a ponta — da arquitetura ao desenvolvimento — automatizando essa atualização.

### 03 · Integração TMS ↔ CIOT (eFrete)
`Delphi`

Automatizei a emissão do CIOT dentro do TMS da empresa: antes o código era apenas um campo `varchar` preenchido manualmente após gerar o documento em outro site (gov ou terceiros). Fui responsável por todo o processo — contato com a eFrete, arquitetura e implementação da integração.

### 04 · Sistema de gerenciamento de tickets
`NextJS` `HeroUI`

Criado enquanto eu liderava um time de desenvolvimento: a ferramenta usada era limitada e não dava visibilidade sobre quantas horas cada programador gastava em cada demanda. O sistema centraliza o que cada desenvolvedor está fazendo, tempo investido, reprovações e atrasos.

### 05 · Dashboards de performance e operação
`NextJS` `HeroUI` `Recharts`

Dois dashboards de BI: um para acompanhar o desempenho dos programadores e gerar insights de melhoria individual; outro voltado ao aplicativo de bipagem, com prazos de entrega, clientes atendidos, prazos de coleta, percentual de atrasos e ranking de clientes por volume transportado.

### 06 · Aplicação de bipagem de volumes
`NextJS` `HeroUI` `NestJS` `PostgreSQL`

Uma transportadora precisava rastrear com precisão onde cada volume era bipado, para localizar rapidamente sobras (volumes parados em alguma filial). A aplicação se conecta ao TMS via API e também extrai relatórios via automação com Chromium (login/senha), alimentando um banco PostgreSQL.

### 07 · Gestão de trocas de gelo
`NextJS` `HeroUI` `NestJS`

Substituiu um processo baseado em PDF, sem controle real de execução ou cobrança correta ao cliente. Cada troca de gelo (usada no transporte de medicamentos) passou a ser registrada pelo usuário logado e vinculada ao número da minuta do TMS via `@Cron` horário, permitindo apurar exatamente quanto cobrar de cada cliente por período.

### 08 · Gestão de frota de veículos
`NextJS` `HeroUI`

A demanda original era simples: saber quem estava com cada veículo no momento, para direcionar corretamente eventuais multas. Evoluiu para um controle completo via QR Code — o motorista lê o código, informa o hodômetro, faz o checklist e inicia a viagem; ao final, repete a leitura e informa o hodômetro final. A aplicação também controla troca de óleo por período/quilometragem e checklists do veículo.

### 09 · Monitoramento de documentos e alvarás
`NextJS` `HeroUI`

Antes, o vencimento de documentos e alvarás da empresa dependia de uma única pessoa acompanhar manualmente — e frequentemente vencia. Com a aplicação, cada gestor de filial acessa apenas seus próprios documentos (por permissão), enquanto matriz/diretoria tem visão geral, e alertas de vencimento são enviados por e-mail.

### 10 · Plataforma multizonas (monorepo)
`NextJS` `HeroUI` `Turborepo` `Vercel`

Projetei um monorepo com Turborepo usando Multi-Zones do Vercel para uma transportadora, centralizando várias aplicações sob um único domínio enquanto mantém cada app independente — facilitando desenvolvimento e escalabilidade isolados por time.

### 11 · Documentação de API
`Ant Design`

Projeto de estudo do Ant Design: lê uma collection exportada do Postman e renderiza a documentação da API diretamente na aplicação.

### 12 · PDV mobile
`Delphi FMX` `Aurelius` `SQLite`

Produto de PDV mobile liderado por mim do zero, para suprir a falta desse tipo de solução no portfólio de uma empresa de sistemas.

---

## 🛠️ Stack

### Linguagens & Frameworks

<table align="center">
  <tr>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40"/><br/>JavaScript</td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40"/><br/>TypeScript</td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40"/><br/>React</td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="40"/><br/>Next.js</td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40"/><br/>Node.js</td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nestjs/nestjs-plain.svg" height="40"/><br/>NestJS</td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.svg" height="40"/><br/>Tailwind</td>
    <td align="center" width="80"><img src="https://img.shields.io/badge/-Delphi-E9573F?style=flat-square&logo=delphi&logoColor=white" height="24"/><br/>Delphi</td>
  </tr>
</table>

### Bancos de Dados

<table align="center">
  <tr>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebird/firebird-original.svg" height="40"/><br/>FireBird</td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40"/><br/>MySQL</td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="40"/><br/>PostgreSQL</td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" height="40"/><br/>SQLite</td>
  </tr>
</table>

### Ferramentas

<table align="center">
  <tr>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40"/><br/>Git</td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="40"/><br/>GitHub</td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" height="40"/><br/>Figma</td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postman/postman-original.svg" height="40"/><br/>Postman</td>
    <td align="center" width="80"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="40"/><br/>VS Code</td>
    <td align="center" width="80"><img src="https://img.shields.io/badge/-Embarcadero-E9573F?style=flat-square&logo=embarcadero&logoColor=white" height="24"/><br/>Embarcadero</td>
    <td align="center" width="80"><img src="https://img.shields.io/badge/-IBExpert-00AF2C?style=flat-square&logo=ibexpert&logoColor=white" height="24"/><br/>IBExpert</td>
  </tr>
</table>

---

## 💬 Frase que eu levo para a minha vida

> _"O amor ao trabalho torna mais leve a carga de dissabores que o trabalho possa trazer."_

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1694ff,100:53c866&height=100&section=footer"/>
</p>
