Projeto: Adivinhe o Número

Este é um jogo de adivinhação de números interativo, construído com HTML, CSS e JavaScript puro. O jogo utiliza um algoritmo de lógica binária para adivinhar qualquer número que o usuário pensar entre 1 e 63, fazendo apenas 6 perguntas de "sim" ou "não".

🚀 Como Funciona o Jogo
O jogo é baseado em um truque de matemática binária. Cada um dos seis conjuntos de números representa uma potência de 2 (1, 2, 4, 8, 16, 32). Ao responder "Sim" a uma pergunta (indicando que seu número está no conjunto), o valor correspondente (o valor da potência de 2) é adicionado a uma soma.

No final, a soma de todos os valores correspondentes às respostas "Sim" resulta no número original que o usuário pensou.

Por exemplo:

Se você pensar no número 25:

16 está no conjunto? Sim. (Soma = 16)

8 está no conjunto? Sim. (Soma = 16 + 8 = 24)

4 está no conjunto? Não.

2 está no conjunto? Não.

1 está no conjunto? Sim. (Soma = 24 + 1 = 25)

A soma final é 25, o número adivinhado!

✨ Funcionalidades
Lógica de Adivinhação de 1-63: Adivinha qualquer número entre 1 e 63 em 6 perguntas.

Interface Interativa: Feedback visual instantâneo para as respostas.

Multi-idioma: Suporte para mais de 10 idiomas (Português, Inglês, Espanhol, Francês, Italiano, Alemão, Indonésio, Russo, Chinês, Japonês, Coreano, Árabe, Hindi, Bengali, Urdú, Marata).

Modo Escuro e Claro: Alterna entre temas claro e escuro, com opção de seguir o tema do sistema operacional.

Controle de Brilho: Permite ajustar o brilho da tela do jogo.

Barra de Progresso: Mostra o progresso do usuário durante o jogo.

Atalhos de Teclado: Atalhos para respostas (S para Sim, N para Não) e controle da interface.

Confetti: Uma pequena celebração visual quando o número é adivinhado com sucesso.

🛠️ Tecnologias Utilizadas
HTML5: Estrutura e marcação da página.

CSS3: Estilização, animações e layout responsivo.

JavaScript (ES6+): Toda a lógica do jogo, manipulação do DOM e eventos.

📁 Estrutura do Projeto
/
├── index.html          # O arquivo principal da página web
├── style.css           # Folha de estilos para o layout e tema
├── script.js           # Lógica do jogo e funcionalidades
└── img/                # Pasta de imagens (botões, ícones, etc.)
⚙️ Como Executar o Projeto
Clone o repositório para sua máquina local:

Bash

git clone [URL_DO_REPOSITORIO]
Abra o arquivo index.html em seu navegador web preferido (Google Chrome, Firefox, etc.).

Não é necessário um servidor web para rodar este projeto, pois todos os arquivos são locais.

🤝 Contribuições
Contribuições são bem-vindas! Se você tiver sugestões de melhorias, detetar bugs ou quiser adicionar mais idiomas ou funcionalidades, sinta-se à vontade para abrir uma issue ou enviar um pull request.
