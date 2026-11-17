Markdown · README.md
Olá, eu sou o Bruno Nathan 👋
QA Engineer | SDET
LinkedIn João Pessoa, PB Aberto a oportunidades

Sou QA Engineer / SDET. Construo suítes de teste automatizadas que a equipe consegue usar de verdade: rápidas, estáveis e com relatórios que mostram o que quebrou e por quê.

Minha regra de trabalho é medir antes de afirmar. Antes de escrever um teste, exploro a tela, olho a rede e anoto o que o produto faz de fato. Quando algo falha, vou atrás da causa raiz em vez de colocar um retry e seguir em frente.

const bruno = {
  cargo: "QA Engineer | SDET",
  agora: "Engenheiro QA @ Media4all",
  stack: ["Playwright", "TypeScript", "Java", "Cypress", "Selenium"],
  foco: ["E2E", "API", "observabilidade de testes", "IA aplicada a QA"],
  estudando: "Ciência da Computação, 6º período @ UNIPÊ",
  lema: "medir antes de afirmar",
};
💼 O que estou construindo agora
Engenheiro QA na Media4all: suíte E2E de UI e API de um portal corporativo do setor de telecom, feita em Playwright + TypeScript.

🧪 Cobertura	152 casos automatizados para 26 requisitos funcionais em 5 serviços, além da integração com o portal
⚡ Desempenho	Massa de teste criada via API: de ~240s para ~91s em um requisito (-62%)
🛡️ Estabilidade	Encontrei a causa raiz de crashes do Chromium (falta de memória no renderer) e resolvi isolando o navegador por spec
🔐 Autenticação	Login com 2FA (TOTP) automatizado e sessão reaproveitada (cerca de 2s quando a sessão ainda vale)
📊 Observabilidade	Relatórios HTML + Allure com falhas classificadas (ambiente, crash, timeout, autenticação, defeito conhecido)
🔒 Segurança	Senhas e tokens JWT apagados automaticamente dos relatórios; a entrega é bloqueada se algum segredo escapar
🧭 Rastreabilidade	Testes organizados por requisito e critério de aceite; 13 bugs documentados com trace e 6 ADRs de decisões técnicas
🔎 Investigação	Mostrei com traces de rede que ~13 MB de miniaturas atrasavam a entrada no módulo em até 36s
🤖 IA aplicada	Agentes e skills de Claude Code com Playwright MCP para explorar telas, medir e gerar testes no padrão da suíte
🛠️ Stack
Automação e testes

Playwright Cypress Selenium Rest Assured JUnit Cucumber

Linguagens

TypeScript JavaScript Java

API, mocks e relatórios

Postman Newman OpenAPI WireMock Allure

CI/CD e build

GitHub Actions Bitbucket Maven

IA aplicada a QA

Claude MCP n8n

♿ Em destaque: Rampa
Auditor de acessibilidade web com IA, em português do Brasil. Você informa o endereço de um site, o Rampa percorre as páginas, roda o axe-core em cada uma e usa IA para avaliar o que a automação não pega sozinha: texto alternativo, propósito dos links, ordem de foco e hierarquia de títulos. Cada problema é ligado aos critérios da WCAG 2.2 e do eMAG.

Status Elixir Phoenix React TypeScript Playwright PostgreSQL Docker License

React ──HTTP/WS──▶ Phoenix ──Oban job──▶ scanner (Playwright + axe) ──▶ site auditado
                      ├──▶ API de IA (Claude)
                      └──▶ PostgreSQL
🧪 Qualidade desde o primeiro commit: mais de 100 arquivos de teste (ExUnit, Vitest e Playwright) e critérios de aceite em Dado/Quando/Então
♿ Acessível por exigência: o CI roda o axe nas telas do próprio Rampa e falha com qualquer violação (WCAG 2.2 AA)
🚦 CI/CD de verdade: 6 checks obrigatórios para merge, CodeQL, actions fixadas por SHA e deploy em staging com rollback automático
🔒 Segurança: proteção contra SSRF em duas camadas (backend e scanner) e limite de uso por requisição
🤖 IA com responsabilidade: achados de IA são sugestões, nunca veredito. Toda resposta é validada contra schema, e cada achado guarda confiança, modelo e versão do prompt
🚀 Outros projetos
Projeto	O que mostra
🔗 Automação de API com Rest Assured	Status code, contratos, cenários positivos e negativos
🔗 Automação Web com Selenium + Java (POM)	Page Object Model e organização de suíte
🔗 Pipeline de testes com GitHub Actions	Testes rodando a cada push e pull request
🔗 Mocks de API com WireMock	Testes independentes de serviços externos
🔗 Testes de performance com Postman	Carga básica, tempo de resposta e estabilidade
💡 Fora do QA, também desenvolvo projetos full stack com Next.js, TypeScript e Supabase.

🌱 Explorando agora
📈 Performance e observabilidade: k6, Grafana e Prometheus
🐳 DevOps: Docker e pipelines de regressão (primeiro informativos, depois bloqueantes)
🤖 Agentes de IA para QA: planner, generator e healer com Playwright Agents
🤝 Vamos conversar?
Topo trocar ideia sobre automação E2E, testes de API, testes instáveis (flaky) ou IA aplicada a QA. 📩 Me chama no LinkedIn.

visitas
