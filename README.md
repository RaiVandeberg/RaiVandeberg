<div align="center">

# Raí Vandenberg

**Desenvolvedor Full Stack · Backend & Arquitetura de Software**

Construo sistemas do domínio à interface, com foco em previsibilidade, manutenibilidade e operação em produção.

<a href="https://www.linkedin.com/in/rai-vandenberg/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://github.com/RaiVandeberg" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="mailto:raibraz67@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</div>

---

## Sobre

Desenvolvedor full stack com foco em **backend e arquitetura de aplicações**. Atuo no ciclo completo: modelagem de domínio, design de APIs, integrações entre serviços, persistência e a interface (web e mobile) que consome tudo isso.

Levo decisões técnicas até a produção — não paro no código. Já assumi desde a estruturação de uma base relacional até deploy self-hosted, configuração de proxy reverso, SSL e autenticação centralizada. Priorizo soluções legíveis e fáceis de manter, e gosto de entender o *porquê* de cada escolha de arquitetura antes de adotá-la.

Atualmente sou **fundador e responsável técnico do Rolefy**, onde tomo as decisões de arquitetura e infraestrutura de ponta a ponta.

---

## Competências

- **Design de APIs** — modelagem de contratos REST claros, versionáveis e consistentes
- **Integrações** — sistemas externos (ERP, gateways de pagamento, serviços terceiros) com tratamento de falhas e idempotência
- **Processamento assíncrono** — filas e workers para desacoplar e dar resiliência ao fluxo
- **Modelagem de dados** — relacional e NoSQL, pensando em consistência e evolução de schema
- **Autenticação e identidade** — SSO/IdP com Keycloak, JWT, fluxos OAuth2/OIDC
- **Infraestrutura e deploy** — containerização, proxy reverso, TLS e operação de ambientes em VPS
- **Estabilização** — refatoração e recuperação de sistemas legados em produção

---

## Stack

**Backend**
`Node.js` · `TypeScript` · `NestJS` · `PostgreSQL` · `DynamoDB (Dynamoose)` · `CouchDB` · `Supabase` · `Redis` · `BullMQ` · `S3 / Spaces` · `JWT / Keycloak (OIDC)`

**Frontend**
`React` · `Next.js` · `TailwindCSS` · `React Hook Form` · `Zustand` · `SWR`

**Mobile**
`React Native / Expo` · `MobX State Tree`

**Infra & DevOps**
`Docker / Docker Compose` · `Nginx (reverse proxy)` · `Certbot / Let's Encrypt` · `Railway` · `VPS (Ubuntu)` · `Git` · `AWS (aprofundando)`

---

## Experiência

### GTEEX · Desenvolvedor Full Stack
Desenvolvimento e manutenção de sistemas internos de ponta a ponta — frontend, backend, banco e produção.

- **CRM comercial** — fluxo de leads, cotações e geração de vendas, com **integração ao ERP Protheus/Winthor** para consultar e relacionar pedidos, produtos e cotações dentro do sistema interno
- **Internacionalização** — configuração de idioma e moeda por concessionária, conversão de câmbio e geração de PDF traduzido mantendo compatibilidade com templates legados
- **Gestão de contratos** — cadastro com histórico/versionamento (CouchDB), upload em S3/Spaces, compartilhamento e status automático por vigência
- **Programa de premiações (GTEEX+)** — ranking mensal, atribuição automática de vencedores via filas (BullMQ) e escolha ordenada de prêmios com controle de expiração por janela de tempo
- **App mobile** — telas de ranking, escolha de prêmio e perfil em React Native / Expo, com redução de requisições, cache local e correção de bugs de renderização
- **Produção & dados** — deploys no Railway, diagnóstico de erros em produção, análise de custos na AWS e correções em PostgreSQL/Supabase

---

## Projetos

### Rolefy — *fundador & tech lead*
Plataforma de descoberta de locais e eventos com sistema de ranking e recompensas, voltada para estabelecimentos (bares, restaurantes, casas de evento) e seu público.

- **Backend:** API em NestJS + PostgreSQL, com regras de escolha ordenada de prêmios, expiração e sincronização entre app e servidor
- **Auth:** Keycloak como provedor de identidade centralizado (realm próprio, OIDC), migrado de PaaS para infraestrutura própria
- **Pagamentos:** integração com gateway em modelo *marketplace* com split de valores entre recebedores
- **Mobile:** aplicativo em React Native / Expo como front-end principal do produto
- **Infra:** stack auto-hospedada com Docker Compose em VPS, Nginx como proxy reverso, certificados TLS via Certbot e DNS segmentado por subdomínio (auth/api)

---

## Aprofundando

- Design Patterns aplicados a problemas reais
- Domain-Driven Design (DDD) e modelagem orientada ao domínio
- Consistência de dados em sistemas distribuídos
- Estratégias de escalabilidade e observabilidade em Node.js

---

## Contato

📧 **Email:** raibraz67@gmail.com
💼 **LinkedIn:** [in/rai-vandenberg](https://www.linkedin.com/in/rai-vandenberg/)
