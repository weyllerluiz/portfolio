🚀 Portfólio Interativo com IA | Weyller Luiz

Da Indústria Offshore para a Engenharia de Computação.
Um portfólio web interativo que utiliza Inteligência Artificial (Google Gemini) para demonstrar minhas competências em Infraestrutura, Automação e Resolução de Problemas.

🌐 Acesse o Portfólio Online Aqui

📖 Sobre o Projeto

Este não é apenas um currículo estático. Como profissional em transição de carreira vindo de ambientes críticos (Siderurgia e Offshore), desenvolvi esta aplicação para demonstrar na prática os meus estudos em Engenharia de Software e Computação.

O projeto adota uma estética "Cyber-Industrial", unindo a robustez da minha experiência em manutenção de equipamentos pesados com a modernidade do código e da infraestrutura de TI.

✨ Funcionalidades Principais

Slides Interativos: Navegação fluida simulando um carrossel de apresentação mobile-first.

🤖 Weyller Virtual (Chatbot): Um assistente de IA treinado com o meu currículo. Ele responde a perguntas dos recrutadores sobre minha experiência, skills e objetivos, agindo como meu "representante digital".

⚡ Análise de Código Inteligente: Nos slides de projetos técnicos (Linux/Docker/Python), integrei um botão que usa a IA para explicar a lógica do script para visitantes não-técnicos.

Fallback de Segurança: O sistema possui um modo de "Simulação" que garante que o portfólio continue funcional mesmo se a API estiver indisponível.

🛠️ Tecnologias Utilizadas

Frontend: HTML5 Semântico, CSS3 (Grid, Flexbox, Animações, Glassmorphism) e JavaScript (ES6+).

Inteligência Artificial: Integração com Google Gemini 1.5 Flash via SDK JavaScript (@google/generative-ai).

Segurança: Implementação de restrições de API Key via HTTP Referrers (Google Cloud Console).

Hospedagem/CI: GitHub Pages.

🔒 Segurança e Arquitetura

Um dos desafios deste projeto foi implementar uma API Key pública de forma segura num site estático (Client-side).

Para mitigar riscos, adotei as seguintes práticas de Engenharia de Segurança:

Restrição de Domínio: A chave de API configurada no Google Cloud Platform só aceita requisições vindas estritamente de https://weyllerluiz.github.io/*. Qualquer tentativa de uso externo é bloqueada.

Tratamento de Erros: O código JavaScript possui blocos try/catch robustos. Se a chave falhar ou a cota exceder, o sistema ativa automaticamente um Modo de Simulação com respostas pré-programadas (MOCK_DATA), garantindo a experiência do usuário (UX).

🚀 Como Executar Localmente

Se desejar estudar o código ou testar na sua máquina:

Clone o repositório:

git clone [https://github.com/weyllerluiz/portfolio.git](https://github.com/weyllerluiz/portfolio.git)


Abra o arquivo index.html no seu navegador.

Nota: As funcionalidades de IA não funcionarão localmente (localhost) devido às restrições de segurança de domínio da API Key. Para testar a IA, você precisará gerar sua própria chave no Google AI Studio e configurar no código.

📬 Contato

Estou aberto a oportunidades em Suporte Técnico, Infraestrutura, NOC e DevOps.

LinkedIn: linkedin.com/in/weyller-luiz

Email: weyller.duarte@gmail.com

Desenvolvido por Weyller Luiz © 2025
