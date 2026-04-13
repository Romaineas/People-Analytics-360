# People-Analytics-360

Visão Geral

O People Analytics 360 é um dashboard executivo de alta fidelidade projetado para transformar dados de capital humano em decisões estratégicas. Desenvolvido com uma estética Dark Mode Premium, o projeto foca na redução da carga cognitiva para gestores, utilizando visualizações dinâmicas e uma arquitetura de dados multidimensional.

# Visualizar Projeto Online: 

 Desafios de Negócio Endereçados
Em grandes organizações, os dados de RH costumam estar isolados. Este dashboard resolve a fragmentação ao centralizar 6 KPIs críticos e permitir o drill-down (detalhamento) por unidade de negócio, ano e localidade.

Retenção Estratégica: Monitoramento de turnover e risco de saída.

Saúde Organizacional: Acompanhamento de eNPS e Absenteísmo.

Desenvolvimento de Talentos: Visão de investimento em treinamento e evolução de PDIs.

# Funcionalidades Técnicas & BI
Filtragem Multidimensional: Lógica avançada em JavaScript que permite o cruzamento de filtros (Departamento + Ano + Hub), alterando instantaneamente todo o modelo de dados.

UI/UX High-End: * Fundo: Slate 950 (#020617) para máximo contraste.

Tipografia: Plus Jakarta Sans para uma estética moderna e limpa.

Reatividade: Efeitos de transição e hover nos cards para feedback tátil ao usuário.

# Data Storytelling:

Gráfico de Radar: Análise de competências por setor.

Gráfico de Evolução: Comparativo direto entre entradas e saídas (Admissão vs Desligamento).

Insights Automatizados: Geração de planos de ação baseados no contexto dos filtros selecionados.

# Arquitetura do Modelo (The Data Engine)
Diferente de dashboards estáticos, este projeto utiliza um Data Repository estruturado via objetos literais em JS, simulando uma consulta a um Data Warehouse. A chave de busca é composta pela concatenação dos seletores (UN-Ano-Local), garantindo que o stakeholder veja exatamente o recorte que solicitou.

 Instalação e Uso
Clone o repositório.

Certifique-se de ter acesso à internet (para carregar o Tailwind e o Chart.js via CDN).

Abra o arquivo index.html em qualquer navegador moderno.

# Próximas Implementações (Roadmap)

[ ] Integração real com API de ERP (ex: SAP, Totvs ou Workday).

[ ] Exportação automática de relatórios em PDF/Excel.

[ ] Implementação de Modelos Preditivos (Machine Learning) para previsão de Turnover.

Desenvolvido por Romaine Santos Data Analyst com foco em soluções de Business Intelligence e Performance.
