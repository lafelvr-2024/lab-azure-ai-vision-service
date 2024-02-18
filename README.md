# lab-azure-ai-vision-service
Laboratorio do Azure A.I. Vision Service


Criado workspace no ml.azure.com
Aberto https://portal.azure.com/?azure-portal=true
Clicado no menu a esquerda em "IA + Azure Learning"
Clicado na op��o "Servi�os Cognitivos" e em criar.
Criado servi�o cognitivo informando:
    Detalhes do projeto
        Assinatura: Azure subscription 1
            Grupo de recursos: LAB-01 (grupo criado no ml.azure.com)

    Detalhes da inst�ncia:
        Regi�o: East-US
        Nome: lab-azure-ai.vision

    Tipo de pre�o: Standard S0
    Clicado em "examinar + criar"

Acessado https://portal.vision.cognitive.azure.com/?azure-portal=true

Analise de imagem (Face):
    Clicar na op��o FACE da lista de op��es;
    Clique na op��o Detect faces in an image;
    Na op��o "Please select a resource.", informe a assinatura e workspace criados anteriormente;
    Marque a op��o "Try it out";
    Upload da IMAGE001.
    ![alt text](image-2.png)


An�lise da imagem (Descrevendo cenario):
    Na tela principal do Vision Studio, selecione "Add captions to images";
    Fa�a upload da IMAGE001.
    ![alt text](image-1.png)

Exemplos de usabilidade levando em considera��es outras modalidades n�o usadas neste exemplo:
    Detectar face para identificar se tem pessoas na foto.
    Traduzir anota��es ou documentos antigos para formato texto facilitando importa��o em sistemas;
    Detectar se h� pessoas em um local, quantas s�o ou distanciamento entre elas.
