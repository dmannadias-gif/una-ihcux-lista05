💱 GLOBAL EXCHANGE - Conversor de Moedas v1.0

Este projeto foi desenvolvido como atividade final da disciplina de IHC & UX, com o objetivo de criar um conversor de moedas no terminal que não apenas realiza cálculos, mas também oferece uma boa experiência para o usuário (UX).

🎯 Objetivo

Construir um sistema simples em C# que:

Converta valores de reais para dólares
Forneça feedback visual ao usuário
Previna erros de entrada
Tenha uma interface clara e agradável no terminal

🧠 Heurísticas de UX Aplicadas

🔍 1. Visibilidade do Status do Sistema

O sistema informa ao usuário o que está acontecendo:

"Conectando ao Banco Central..."
"Calculando taxas..."

Isso simula um sistema real e evita a sensação de travamento.

⚠️ 2. Prevenção de Erros

Foi utilizado try-catch para evitar que o programa quebre:

Caso o usuário digite algo inválido, o sistema exibe:
Mensagem clara de erro
Destaque visual com fundo vermelho

🎨 3. Estética e Design Minimalista

Foram utilizados elementos visuais simples:

Cores no terminal (amarelo, verde, vermelho)
Separadores com linhas
Texto organizado e legível

Isso melhora a leitura e a experiência do usuário.

⚙️ Tecnologias Utilizadas
Linguagem: C#
Plataforma: .NET Console
IDE: Visual Studio Code

📸 Evidência

O arquivo evidencia-final.png contém um print do sistema em funcionamento, mostrando:

Entrada de dados,
Mensagens de carregamento,
Resultado final formatado

📁 Estrutura do Projeto - 
una-ihcux-lista05/
│
├── ConversorExpert/
│   └── Program.cs
│
├── evidencia-final.png
└── README.md

🚀 Como Executar - 
Abra o terminal,
Navegue até a pasta do projeto,
Execute:
dotnet run
