# PC_ModuloIntrodutorio
 Este repositório é referente ao plantão do módulo introdutório.

 Vamos começar pela UC6 - Metodologias Ágeis
 
- [ ] Abrir o Trello:
> https://trello.com/

## UC6 - Metodologias Ágeis

Em seguida clique em "Criar novo quadro" e dê a ele o nome de sua preferência, nós faremos o exemplo da atividade que é o sistema de gestão de clínicas.

Crie as seguintes colunas nesta ordem respectivamente
- Product Backlog;
- Sprint Backlog (À fazer);
- Fazendo;
- Sprint Review (Testando) e
- Concluído (Feito).

![image](https://github.com/CTM-SENAI-134/PC_ModuloIntrodutorio/assets/144062335/075b40fc-2d29-42b6-a7f3-782b3955a8de)

Agora na coluna Product Backlog crie todos estes cards
- Criar metódo de login;
- Fazer/montar a modelagem dos dados (banco de dados);
- Criar a home page;
- Criar agenda para as consultas;
- Criar base de dados para cadastro de clientes e animais;
- Criar página para cadastro de produtos;
- Criar página para cadastro de medicamentos;
- Criar página para compras online e
- Criar catálogo para as compras onlineCriar página de relatório de colaboradores.

Agora você vai definir quais tarefas serão feitas na próxima sprint, arraste e solte as 3 primeiras tarefas para a coluna Sprint Backlog (À fazer) (2ª coluna), para deixar mais nítido de qual sprint é cada tarefa e você vai separar essas tarefas em setores (Front-End e Back-End) usando as queridas etiquetas lá na frente.

Comece criando a etiqueta da "Sprint 1", clique no primeiro card da 2ª coluna e clique na opção "Etiquetas" no menu lateral dentro do card. Agora é só clicar no lápis ao lado de uma cor para dar um nome, salvar e depois clicar no checkbox ao lado ou em cima da etiqueta para aplicá-la ao card.
Atribua a etiqueta para todos os cards que estão na coluna Sprint Backlog (À fazer).

![image](https://github.com/CTM-SENAI-134/PC_ModuloIntrodutorio/assets/144062335/3a994b36-e2ae-4133-a316-428652a81279)

À medida que as tarefas vão sendo feitas, testadas e concluídas elas vão sendo arrastadas para a direita.

![image](https://github.com/CTM-SENAI-134/PC_ModuloIntrodutorio/assets/144062335/625ff35d-dc68-4911-96f2-762f6f7f6e97)


Assim como você criou a primeira etiqueta agora crie para a Sprint 2, Front-End, Back-End e atribua-as aos cards, seu quadro vai ficar mais ou menos assim:

![image](https://github.com/CTM-SENAI-134/PC_ModuloIntrodutorio/assets/144062335/1f78d8bd-f17e-4864-9c6f-5088c6c5a1b2)

 ---

## UC8 - Lógica de Programação

Agora na parte da atividade de Lógica, onde você desenvolverá o fluxograma, você utilizará a ferramenta draw.io.
Assim que você abri-la será aberto um modal, é só seguir as seguintes etapas:
- Clicar em "Aparelho";
- Clicar em “Criar diagrama novo”;
- Colocar o nome como “Fluxograma” e clicar em “Criar” mantendo como “Diagrama em branco” e
- Escolha a pasta da sua preferência para guardar o fluxograma e clique em "Salvar";

## Modelo de Figuras
![image](https://github.com/CTM-SENAI-134/PC_ModuloIntrodutorio/assets/144062335/5b78d2ca-cd22-41b9-a1ac-f710096cafae)

Assim que abrir o seu projeto comece selecionando no menu lateral à esquerda a nossa forma de início que é o Elipse, ela aparecendo na tela clique 2 vezes em cima da mesma e digite “Início”.

![image](https://github.com/CTM-SENAI-134/PC_ModuloIntrodutorio/assets/144062335/ee7b7568-109a-4bfd-8b1c-b78100b6fb32)

No nosso caso depois que se inicia o fluxo você vai receber o valor de entrada do usuário onde ele vai informar para você(sistema) qual o saldo inicial de peças dele, então você vai solicitar essa informação para ele usando a figura de “Impressão/Output” que está dentro da aba "Avançado".

![image](https://github.com/CTM-SENAI-134/PC_ModuloIntrodutorio/assets/144062335/9db31e3b-8a60-463f-afae-c1ba21f4e029)

Dê 1 clique e coloque o que vai mostrar para o usuário → “Insira a quantidade inicial de peças do seu sistema” e ajuste o tamanho da figura com as bolinhas azuis ao redor da mesma para comportar todo o texto.
Ligue a figura de início à figura de display com a seta para demonstrar a direção do fluxo.

Agora que solicitou uma informação ao usuário você precisa guardar a informação que foi informada, para isso utilizamos o trapézio, adicione-o e ligue a figura do Display à ele.
Dê 1 clique e coloque o que vai estar sendo recebido/guardado naquela entrada de dados do usuário → “qtd Inicial (X)” e já puxando a seta igual foi feito acima

Agora nós iremos criar uma condicional, para condicionais nós utilizamos a figura Losango.
Dê 1 clique e vamos colocar o que vai estar sendo decidido aqui, qual vai ser a nossa condição para direcionarmos o fluxo → “Deseja adicionar/somar peças?” e já vamos puxando a seta igual fizemos acima.

Caso o texto ficar apertado é só redimensionar

![image](https://github.com/CTM-SENAI-134/PC_ModuloIntrodutorio/assets/144062335/90cb9262-1e72-4aa4-be0c-762be4f6a751)

Aqui você vai dividir o fluxo entre se a resposta para a condição é afirmativa ou negativa. Divida diretamente já na Impressão para o usuário perguntando quantas peças ele vai somar ou subtrair.
Então coloque uma figura de impressão de cada lado da nossa condicional e já ligar as setas, de um lado coloque “Informe a quantidade a subtrair” e do outro “Informe a quantidade a somar”.

Por mais que esteja meio implícito qual é a resposta da condição que vai direcionar o fluxo você precisa mostrar, deixar nítido o que está acontecendo, para isso dê 2 cliques em cima da linha da seta afirmativa(quantidade a somar) ai é só digitar “Sim” e fazer o mesmo no outro lado

![image](https://github.com/CTM-SENAI-134/PC_ModuloIntrodutorio/assets/144062335/be4ac7f2-a1f8-48b6-84a9-6dcc50797118)

Então pode seguir os mesmos passos que foram feitos acima né, depois que imprir uma mensagem para o usuário você vai guardar a informação, para isso utilize o trapézio igual usou na quantidade inicial. Para não perder tanto tempo faça dos dois lados por vez.

![image](https://github.com/CTM-SENAI-134/PC_ModuloIntrodutorio/assets/144062335/e05c7515-b1ea-4b55-94ca-40a0df0d21e9)

Agora que você tem todas as informações que precisa, agora vai trabalhar com ela onde de um lado nós iremos somar e do outro subtrair. 
Para ilustrar uma ação ou um processo nós utilizamos a figura Retângulo então vamos lá, adicione-as e mostre qual operação será realizada.

![image](https://github.com/CTM-SENAI-134/PC_ModuloIntrodutorio/assets/144062335/c80cbec4-945a-4d18-bb44-08dbdbe99d50)

Após isso, você concorda que o ideal seria mostrar para o usuário qual foi o resultado final?
E ai feito isso podem finalizar o fluxograma.
Então vamos devolver o resultado da operação, seja ela soma ou subtração e finalizamos o fluxograma com a mesma figura que iniciamos, no final vai ficar assim:

![image](https://github.com/CTM-SENAI-134/PC_ModuloIntrodutorio/assets/144062335/9ef2dd3e-38e8-40d9-ac73-e2bea507c723)

 ---

## UC7 - Versionamento

Agora você vai para a última parte, Versionamento, vai subir o que é realizado na máquina (repositório local) para o seu repositório lá no Github (repositório remoto).

---
> [!IMPORTANT]
> O que precisamos ter para conseguir fazer esta atividade?
> 1) Instalar o Github Desktop

- [ ] Instalação do Github Desktop:
> https://desktop.github.com/
---

Após fazer o download você vai entrar com a mesma conta do github e apontar alguns detalhes.
Agora crie um repositório local clicando em "Create a new repository on your hard drive...".

Preencher com os dados (Nome do repositório e descrição) e clique em “Create repository”.
Agora vá até a pasta do repositório que acabou de ser criado e dentro dela, crie um arquivo txt e coloque algo dentro dele.

## Caminho: Documentos → Github → nomeDoRepositorio

Então vamos fazer o seu primeiro commit no input escrito "Summary (required)" e clique em “Commit to main”

![image](https://github.com/CTM-SENAI-134/PC_ModuloIntrodutorio/assets/144062335/04885dae-81fb-4776-8dd9-de2cc65a2d71)

Agora é só clicar aqui em “Publish Repository”, dessa forma vamos subir as alterações que foram feitas para o Github.
Clique em "publish Repository" novamente.

![image](https://github.com/CTM-SENAI-134/PC_ModuloIntrodutorio/assets/144062335/6cdf32cf-6344-4ce9-9254-ff2f52d55bcb)

Agora você pode ir lá no Github para dar uma olhada como ficou! 😎
