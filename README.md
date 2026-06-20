~/jm_sec - Hub de Conhecimento: SecOps & GRC

Bem-vindo ao repositório oficial do Hub de Conhecimento de Jeferson Machado, focado em Arquitetura SAP, Defesa e Governança.

Este projeto foi desenhado para atuar como um repositório centralizado de artigos técnicos, análises de engenharia de acessos e estratégias de blindagem (Zero Trust) em ambientes corporativos complexos.

🏗️ Arquitetura da Solução (Secure by Design)

O site foi construído sob o paradigma Jamstack (JavaScript, APIs e Markup), eliminando vetores de ataque comuns em CMS tradicionais.

Static Site (Zero Database): Sem banco de dados relacional e sem processamento backend exposto (como PHP ou Node.js). A superfície de ataque para SQL Injection ou Remote Code Execution (RCE) é nula.
 
Tailwind CSS (Utility-First): Estilização de alta performance renderizada via CDN, garantindo um carregamento ultrarrápido e interface responsiva (Mobile-First).

Privacy by Design: O "Dark Mode" (Modo Escuro) utiliza localStorage estritamente local, sem cookies de rastreamento, em total conformidade com a LGPD.

Hospedagem: Projetado para deploy contínuo (CI/CD) via GitHub Pages.