📄 Automação de União de PDFs com Python

Este projeto foi desenvolvido para automatizar a união de múltiplos arquivos PDF em um único documento utilizando Python.
O script lê todos os arquivos PDF presentes em uma pasta específica e gera um novo arquivo PDF consolidado, facilitando a organização de documentos.

🚀 Tecnologias utilizadas

Python

Biblioteca pypdf (ou PyPDF2)

📦 Instalação

Clone o repositório ou baixe os arquivos do projeto.

git clone (https://github.com/mmgdlima-byte/PDF_merger)

Entre na pasta do projeto:

cd automacao-pdf

Crie um ambiente virtual:

python -m venv .venv

Ative o ambiente virtual:

Windows (PowerShell)
.venv\Scripts\Activate.ps1
Windows (CMD)
.venv\Scripts\activate.bat

Instale as dependências:

pip install pypdf
▶️ Como executar

Crie uma pasta chamada pdfs dentro do projeto.

Coloque todos os arquivos PDF que deseja unir dentro dessa pasta.

Execute o script.

python projeto1.py

O programa irá:

Ler todos os arquivos PDF dentro da pasta arquivos.

Mesclar os documentos

Gerar um novo arquivo PDF unificado

📂 Estrutura do projeto
Automacao
│
├── projeto1.py
├── README.md
├── arquivos
│   ├── arquivo1.pdf
│   ├── arquivo2.pdf
│   └── arquivo3.pdf
└── .venv
💡 Possíveis melhorias

Permitir que o usuário escolha a pasta dos arquivos

Definir automaticamente a ordem dos arquivos

Criar uma interface simples para seleção dos documentos

Permitir renomear o PDF final automaticamente

🎯 Objetivo do projeto

Este projeto faz parte dos meus estudos em Análise e Desenvolvimento de Sistemas (ADS) e tem como objetivo praticar:

Automação com Python

Manipulação de arquivos PDF

Uso de bibliotecas externas

Estruturação de projetos simples em Python
