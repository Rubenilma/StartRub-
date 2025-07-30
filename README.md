# COMO INSTALAR E EXECUTAR O PROJETO:

1. Clique em "Download" (ícone de nuvem ou botão "Raw" > botão direito > salvar como...).





2. Extraia o conteúdo do ZIP

Clique com o botão direito no arquivo .zip → "Extrair aqui" ou "Extrair para...".

Você verá uma pasta com o projeto StartRub, com todos os arquivos e pastas descompactados.





3. Abra a pasta no Visual Studio Code

Abra o Visual Studio Code.

Vá em File > Open Folder... e selecione a pasta extraída do projeto.





4. Crie e ative o ambiente virtual

> Este passo é importante para isolar as dependências do projeto.

No terminal do VS Code:

python -m venv venv

Depois:

Se você usa Windows:

venv\Scripts\activate

Se você usa Linux/Mac:

source venv/bin/activate




5. Instale as dependências

pip install -r requirements.txt




6. Execute o projeto:

python app.py

Acesse no navegador:

http://localhost:5000



✅ Testes de unidade 
execute o teste do backend com:

python test_database.py
