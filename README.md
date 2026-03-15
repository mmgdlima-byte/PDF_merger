📄 Automação de União de PDFs com Python

Este projeto foi desenvolvido para automatizar a união de múltiplos arquivos PDF em um único documento utilizando Python.
O script lê todos os PDFs definidos no código e gera um novo arquivo PDF consolidado, facilitando a organização de documentos.

🚀 Tecnologias utilizadas

Python

Biblioteca pypdf (ou PyPDF2)

📦 Instalação

Clone o repositório ou baixe os arquivos do projeto.

git clone https://github.com/seu-usuario/automacao-pdf.git

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

Coloque os arquivos PDF que deseja unir dentro da pasta do projeto e execute:

python projeto1.py

O programa irá:

Ler os arquivos PDF definidos no script

Unir todos os documentos em um único PDF

Gerar um novo arquivo PDF consolidado

📂 Estrutura do projeto
Automacao
│
├── projeto1.py
├── README.md
└── .venv
💡 Possíveis melhorias

Permitir que o usuário escolha os PDFs automaticamente

Unir todos os PDFs de uma pasta

Criar uma interface simples para seleção de arquivos

Permitir definir a ordem dos documentos

🎯 Objetivo do projeto

Este projeto faz parte dos meus estudos em Análise e Desenvolvimento de Sistemas (ADS) e tem como objetivo praticar:

Automação com Python

Manipulação de arquivos PDF

Uso de bibliotecas externas

Estruturação de projetos simples em Python

Se quiser, também posso melhorar ainda mais esse README deixando ele com padrão que recrutadores de tecnologia gostam de ver no GitHub (fica muito mais profissional).

tambem tem que informar que tem que colocar em uma pasta especifica os pdfs para mesclar

Aqui está o README atualizado, agora explicando corretamente que os PDFs devem ser colocados em uma pasta específica para serem mesclados.

📄 Automação de União de PDFs com Python

Este projeto foi desenvolvido para automatizar a união de múltiplos arquivos PDF em um único documento utilizando Python.
O script lê todos os arquivos PDF presentes em uma pasta específica e gera um novo arquivo PDF consolidado, facilitando a organização de documentos.

🚀 Tecnologias utilizadas

Python

Biblioteca pypdf (ou PyPDF2)

📦 Instalação

Clone o repositório ou baixe os arquivos do projeto.

git clone https://github.com/seu-usuario/automacao-pdf.git

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

Ler todos os arquivos PDF dentro da pasta pdfs

Mesclar os documentos

Gerar um novo arquivo PDF unificado

📂 Estrutura do projeto
Automacao
│
├── projeto1.py
├── README.md
├── pdfs
│   ├── arquivo1.pdf
│   ├── arquivo2.pdf
│   └── arquivo3.pdf
└── .venv
💡 Possíveis melhorias

Permitir que o usuário escolha a pasta dos PDFs

Definir automaticamente a ordem dos arquivos

Criar uma interface simples para seleção dos documentos

Permitir renomear o PDF final automaticamente

🎯 Objetivo do projeto

Este projeto faz parte dos meus estudos em Análise e Desenvolvimento de Sistemas (ADS) e tem como objetivo praticar:

Automação com Python

Manipulação de arquivos PDF

Uso de bibliotecas externas

Estruturação de projetos simples em Python
