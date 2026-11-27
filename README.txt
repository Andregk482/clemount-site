CLEMOUNT — ENGINEERING HUB (BETA)
================================

COMO EXECUTAR
1. Extraia a pasta clemount-site.zip.
2. Abra index.html em um navegador atualizado (Chrome, Edge ou Firefox).
3. Navegue pelo menu lateral. Não é necessário instalar dependências para a demonstração local.

ESTRUTURA
- index.html: estrutura principal e navegação.
- css/style.css: identidade visual, componentes e responsividade.
- js/app.js: navegação, formulários, cálculos, validações simples, exportações e persistência local.
- assets/clemount-logo.jpg: logo fornecida pelo usuário.
- assets/server-rack-hero.png e assets/datacenter.png: recortes de imagens da referência visual gerada anteriormente.

MÓDULOS INCLUÍDOS
Visão geral; Sobre & equipe; Serviços e projetos; Rack Builder 2D; Power & Energy; Thermal Analysis; Hardware Analyzer; Network Designer; Automation Lab; AI Lab demonstrativo; Olimpo Cloud; Virtualization Lab; Monitoring Center demonstrativo; Security Center; Backup & Recovery; CFTV; IT Architecture; Business Intelligence; Project Management; Documentation Center; Contato.

FUNCIONALIDADES BETA
- Rack Builder: adicionar por clique ou arrastar e soltar, remover, ocupação e exportar JSON.
- Energia: cadastrar cargas, somar potência, estimar kWh/mês e custo estimado.
- Térmica: registrar medições fornecidas pelo usuário.
- Hardware: inventário de componentes e especificações.
- Redes: inventário, validação de formato IPv4 e detecção de duplicidade; não valida roteamento/sub-redes completo.
- Automação: cadastro documental de fluxos (não executa integrações externas).
- IA: roteiro de diagnóstico local baseado em regras (não é uma IA conectada).
- Cloud: planejamento conceitual de distribuição de serviços.
- Virtualização: inventário de VMs.
- Monitoramento: dados fictícios para demonstrar dashboard.
- Segurança, backup e CFTV: cadastros e planejamento documental.
- Gestão de tarefas, documentação e exportação geral em JSON.
- Dados persistidos no localStorage do navegador utilizado.

LIMITAÇÕES E SEGURANÇA
Este é um protótipo front-end acadêmico. Não existe backend, autenticação, banco de dados central, integração com sensores, câmeras, SNMP, Prometheus, n8n, APIs de nuvem ou equipamentos reais.
Os dados ficam somente no navegador e podem ser apagados ao limpar os dados do site. Exporte cópias JSON regularmente.
Os valores de monitoramento são simulados. As estimativas de energia são simplificadas e não substituem projeto elétrico, avaliação de proteção, condutores, circuitos, aterramento ou dimensionamento profissional de UPS. A análise térmica registra dados informados, não executa simulação CFD. Compatibilidade de hardware precisa ser verificada nas especificações oficiais dos fabricantes.
Antes de publicar na internet, implemente backend, autenticação, autorização por função, validação no servidor, HTTPS, política de privacidade, proteção contra abuso e armazenamento seguro de dados. Não coloque senhas ou segredos no JavaScript.

PERSONALIZAÇÃO RECOMENDADA
- Substituir contato@clemount.com pelo e-mail real em js/app.js.
- Atualizar integrantes, funções e dados institucionais na página Sobre.
- Cadastrar modelos, dimensões, consumo e especificações reais dos quatro computadores e demais equipamentos.
- Ajustar quantidade de U e dimensões do Rack Builder ao rack físico adquirido.
- Definir critérios de alerta térmico e elétrico com base nos manuais, medições e orientação do professor/profissional habilitado.
- Configurar um backend (por exemplo, API REST) e banco de dados quando a equipe precisar compartilhar informações entre dispositivos.
