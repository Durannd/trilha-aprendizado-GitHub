# Plano: GitHub Student Pack — 8 semanas (detalhado) + Checklist diário

Este arquivo reúne tudo que conversamos: explicação rápida do GitHub Student Developer Pack, links úteis em português e o plano diário de 8 semanas (56 dias) com objetivos, recursos e tarefas práticas. Use este checklist no seu repositório para acompanhar o progresso — marque as caixas conforme for completando.

---

## Sumário rápido
- O GitHub Student Developer Pack (Student Pack) oferece licenças, créditos e descontos para estudantes (IDEs, hospedagem, domínios, segurança, etc.).
- Priorize aprender: Git/GitHub flow, deploys reais, CI/CD, testes, containers/Docker e contribuição open source.
- Se for menor de idade: use sandboxes do Microsoft Learn para experimentar serviços de cloud; para créditos persistentes, verifique elegibilidade local ou peça um responsável.

---

## Observações práticas antes de começar
- Reserve 1–3 horas por dia (ajuste conforme necessidade).
- Faça commits pequenos e frequentes; mantenha repositórios públicos para portfólio.
- Use Microsoft Learn sandboxes se não puder criar conta em provedores de cloud.
- Combine ofertas do Student Pack (ex.: domínio + GitHub Pages).
- Documente tudo: README, vídeo curto (1–2 min), screenshots.

---

## Plano detalhado — 8 semanas (56 dias)

Cada dia tem uma tarefa clara. Recomendação: crie issues/daily checklist no seu repositório e marque conforme concluir.

### Semana 1 — Fundamentos de Git e GitHub (Dias 1–7)
Objetivo: dominar commits, branches, PRs e fluxo GitHub.

Recursos:
- Livro Pro Git (PT‑BR): https://git-scm.com/book/pt-br/v2
- GitHub Docs (pt): https://docs.github.com/pt
- GitHub Learning Lab: https://lab.github.com/

Dias / Tarefas:
- Dia 1: Instalar Git; configurar user.name e user.email; criar repositório "portfolio-meu-nome". Tarefa: 3 commits (README, .gitignore, descrição).
- Dia 2: Criar branch feature/teste e fazer commits. Abrir PR via interface do GitHub.
- Dia 3: Praticar merges: merge, squash e rebase. Testar cada um num repo de teste.
- Dia 4: Simular conflito entre branches e resolver localmente.
- Dia 5: Criar tag v0.1 e publicar Release com changelog.
- Dia 6: Explorar Issues e Projects (kanban). Criar 3 issues (bug, melhoria, task).
- Dia 7: Criar PR com template e fazer revisão. Entregável: repo público com histórico de branches/PRs.

---

### Semana 2 — README, documentação e portfólio (Dias 8–14)
Objetivo: README profissional e página do portfólio.

Recursos:
- Como escrever READMEs (pt): https://docs.github.com/pt/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes

Dias / Tarefas:
- Dia 8: Estrutura do README (objetivo, tecnologias, instalação, uso, screenshots). Criar esqueleto.
- Dia 9: Adicionar badges (build, license, linguagem) e instruções de execução.
- Dia 10: Seção "Como testar" com comandos.
- Dia 11: Criar pastas docs/ e assets/ com screenshots.
- Dia 12: Gravar vídeo demo (1–2 min) e hospedar (YouTube privado/unlisted ou link).
- Dia 13: Adicionar "Sobre mim" com LinkedIn/GitHub.
- Dia 14: Revisão final e cleanup. Entregável: README completo + vídeo linkado.

---

### Semana 3 — Frontend básico + publicar site (Dias 15–21)
Objetivo: site estático do portfólio e deploy.

Recursos:
- GitHub Pages: https://docs.github.com/pt/pages
- Azure Static Web Apps: https://learn.microsoft.com/pt-br/azure/static-web-apps/
- MDN Web Docs: https://developer.mozilla.org/pt-BR/

Dias / Tarefas:
- Dia 15: Criar site estático (HTML/CSS) ou com framework (React/Vite).
- Dia 16: Publicar no GitHub Pages (gh-pages) e validar URL.
- Dia 17: Alternativa: configurar Vercel/Netlify e conectar repo.
- Dia 18: Apontar domínio (se tiver cupom do Student Pack).
- Dia 19: Formulário de contato (Formspree/Netlify Forms).
- Dia 20: Inserir screenshots e vídeo do projeto no site.
- Dia 21: Testes de responsividade e acessibilidade. Entregável: site público do portfólio.

---

### Semana 4 — App fullstack simples (CRUD) (Dias 22–28)
Objetivo: app fullstack (Node/Express + PostgreSQL + React recomendado).

Recursos:
- Docker: https://docs.docker.com/get-started/
- Tutoriais Node/Express e PostgreSQL.

Dias / Tarefas:
- Dia 22: Definir stack; criar repositório (ex.: MovieFlix).
- Dia 23: Backend: endpoints CRUD (/movies).
- Dia 24: Rodar PostgreSQL via Docker; conectar backend.
- Dia 25: Frontend: listar, criar, editar, deletar.
- Dia 26: Autenticação simples (opcional) — JWT ou mock.
- Dia 27: Testes unitários básicos (Jest/Mocha, testing-library).
- Dia 28: Documentar endpoints e preparar para deploy. Entregável: app funcionando localmente com testes.

---

### Semana 5 — Deploy na cloud (Dias 29–35)
Objetivo: colocar app no ar (frontend + backend).

Recursos:
- Azure for Students: https://azure.microsoft.com/pt-br/free/students/
- Azure Static Web Apps: https://learn.microsoft.com/pt-br/azure/static-web-apps/
- Vercel / Netlify / Render / Railway

Dias / Tarefas:
- Dia 29: Escolher destino do deploy (Azure se possível; senão Vercel+Railway).
- Dia 30: Deploy do frontend (Static Web Apps / Vercel).
- Dia 31: Deploy do backend (App Service, Functions ou Railway/Render).
- Dia 32: Banco em cloud (Azure DB for PostgreSQL ou Railway DB).
- Dia 33: Testar integração em produção (fluxo CRUD).
- Dia 34: Configurar HTTPS e domínio (se aplicável).
- Dia 35: Documentar processo de deploy no README. Entregável: app com URL público.

---

### Semana 6 — CI/CD e testes automatizados (Dias 36–42)
Objetivo: pipeline que roda testes e faz deploy automático.

Recursos:
- GitHub Actions: https://docs.github.com/pt/actions

Dias / Tarefas:
- Dia 36: Aprender YAML de Actions; estrutura de workflow.
- Dia 37: Job CI: instalar deps e rodar testes (backend).
- Dia 38: Job CI para frontend (build + testes).
- Dia 39: Build Docker e publicação (opcional).
- Dia 40: Workflow CD: deploy para staging ao merge em main.
- Dia 41: Deploy preview para PRs.
- Dia 42: Adicionar badge de status do CI no README. Entregável: CI em PRs e deploy automático.

---

### Semana 7 — Observabilidade, segurança e Dependabot (Dias 43–49)
Objetivo: rastreamento de erros, logs e atualização de dependências.

Recursos:
- Sentry: https://sentry.io/
- Dependabot: https://docs.github.com/pt/code-security/supply-chain-security/keeping-your-dependencies-updated-automatically
- Snyk: https://snyk.io/ (ver se aparece no Student Pack)

Dias / Tarefas:
- Dia 43: Logging (Winston ou similar) no backend.
- Dia 44: Integrar Sentry/Application Insights; disparar erro de teste.
- Dia 45: Habilitar Dependabot (configurar schedule).
- Dia 46: Rodar scanner de vulnerabilidades (Snyk) e abrir issue para fix.
- Dia 47: Mover segredos para GitHub Secrets.
- Dia 48: Healthcheck endpoint + uptime monitor (UptimeRobot).
- Dia 49: Teste de carga leve (ab ou locust). Entregável: monitoramento e segurança ativos.

---

### Semana 8 — Contribuição OSS e preparação para entrevistas (Dias 50–56)
Objetivo: fazer 1 PR em OSS e preparar materiais de entrevista.

Recursos:
- Good first issue / first-timers: https://goodfirstissue.dev/
- Como contribuir: https://docs.github.com/pt/get-started/quickstart/contributing-to-projects

Dias / Tarefas:
- Dia 50: Encontrar 2 projetos OSS com issues fáceis; escolher 1.
- Dia 51: Clonar e rodar local; seguir CONTRIBUTING.md.
- Dia 52: Implementar correção/melhoria e abrir PR.
- Dia 53: Criar 3 slides: problema, solução, stack.
- Dia 54: Gravar vídeo demo (1–2 min) do projeto e PR.
- Dia 55: Preparar roteiro de entrevista (5 perguntas + respostas).
- Dia 56: Revisão final do portfólio (links, badges, vídeos, PRs). Entregável final: portfólio pronto, app em produção, CI ativo, PR em OSS, material para entrevistas.

---

## Checklist diário (exemplo rápido)
- [ ] Dia 1 — Git instalado e repositório criado
- [ ] Dia 2 — Branch e PR criados
- [ ] ...
- (Copiar e colar o plano diário acima como checklist no seu repo e marcar conforme concluir)

---

## Recursos extras (resumido)
- Git (PT): https://git-scm.com/book/pt-br/v2
- GitHub Learning Lab: https://lab.github.com/
- Microsoft Learn (pt‑BR): https://learn.microsoft.com/pt-br/training/
- Azure for Students: https://azure.microsoft.com/pt-br/free/students/
- Azure Static Web Apps: https://learn.microsoft.com/pt-br/azure/static-web-apps/
- MDN Web Docs (pt‑BR): https://developer.mozilla.org/pt-BR/
- Docker (get started): https://docs.docker.com/get-started/
- Vercel / Netlify / Railway / Render (homepages)

---

## Próximos passos que eu posso executar para você
- Gerar o arquivo checklist pronto (este arquivo já está pronto para download/copiar para o repositório).
- Se preferir, eu posso:
  - Gerar um workflow GitHub Actions para CI básico do MovieFlix (arquivo YAML).
  - Montar um passo-a-passo para deploy do MovieFlix no Azure Static Web Apps usando o Microsoft Learn sandbox.

---

## Informações da sua sessão
- Data atual (UTC): 2025-09-26 13:11:03
- Login do usuário: Durannd

Repositórios recentes:
- https://github.com/Durannd/demo-dao-jdbc
- https://github.com/Durannd/workshop-javafx-jdbc
- https://github.com/Durannd/MovieFlix
- https://github.com/Durannd/CadastrodeNinjas
- https://github.com/Durannd/AuraBank

---

Obrigado — a seção FAQ sobre Azure foi removida e o documento está pronto para ser copiado para o seu repositório.