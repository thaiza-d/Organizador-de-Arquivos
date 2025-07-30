# 🗂️ Organizador de Arquivos por Extensão
Este script Python organiza automaticamente os arquivos de uma pasta selecionada, movendo-os para subpastas de acordo com suas extensões (como .jpg, .pdf, .py, etc).

## ✅ Funcionalidades
Solicita ao usuário a escolha de uma pasta.

Identifica todos os arquivos presentes nela.

Cria subpastas (caso não existam) com base no tipo de arquivo.

Move cada arquivo para a subpasta correspondente.

## 📁 Tipos de arquivos suportados
O script atualmente organiza os seguintes tipos:

Categoria	Extensões
Imagens	.png, .jpg
Planilhas	.xlsx
PDFs	.pdf
CSV	.csv
Python	.py

## ▶️ Como usar
Execute o script com Python instalado:

bash
Copiar
Editar
python organizador.py
Uma janela será exibida pedindo que você selecione uma pasta.

Os arquivos da pasta escolhida serão organizados automaticamente.

## 🧠 Requisitos
Python 3

Módulo tkinter (incluso por padrão em instalações do Python)

## ✏️ Exemplo
Antes:

    bash
    Copiar
    Editar
    /meus_arquivos
    ├── foto.jpg
    ├── script.py
    ├── dados.csv
  
Depois de executar o script:
    
    bash
    Copiar
    Editar
    /meus_arquivos
    ├── imagens
    │   └── foto.jpg
    ├── python
    │   └── script.py
    ├── csv
        └── dados.csv
