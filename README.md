## Desafio AWS Step Functions!

Olá! Eu sou a Bianca, e esse é meu repositório do desafio de AWS Step Functions. Aqui eu vou contar um pouco da minha jornada de aprendizado, mostrar meus experimentos e insights, e até aquele momento bagunçado que aconteceu (spoiler: foi aprendizado puro 😅).


### 📌 Sobre o Desafio:

Este projeto tem como objetivo explorar o AWS Step Functions, criando workflows automatizados para orquestrar diferentes serviços da AWS. Durante o aprendizado, testei a integração com serviços como Lambda, EC2, DynamoDB e EBS, entendendo como cada serviço pode ser conectado dentro de uma máquina de estado.


## 📋 Conceitos Explorados:

🛠 **Workflow:** a sequência de passos que uma aplicação ou processo deve seguir.

🔄 **State Machine:** a “máquina de estados” que controla cada passo do workflow.

❓ **Choice:** decisões dentro do fluxo, como um “se isso, faça aquilo”.

🪣 **Buckets:** lugares para armazenar arquivos e dados.

📝 **Templates:** modelos prontos para agilizar a criação de workflows.



## ⚙️ Funcionalidades Exploradas:

•	Criação de máquinas de estado no AWS Step Functions.

•	Integração com AWS Lambda para execução de funções serverless.

•	Uso de Amazon DynamoDB para operações de banco de dados.

•	Testes com EC2 e EBS para entender fluxos de computação e armazenamento.

•	Exploração de diferentes padrões e APIs do AWS SDK.



## 📋 Como Funciona:

1.	O workflow começa no estado Start.
2.	Executa a função Lambda.
3.	Passa por diferentes serviços dependendo do fluxo (DynamoDB, EC2, EBS, etc.).
4.	Finaliza no estado End.
   

📍**Nota:** O fluxo completo é experimental e foi construído explorando diferentes ações disponíveis no Step Functions, sem um objetivo final específico, mas com foco em aprendizado.


## 📄 Meu Processo de Aprendizado:

**1.	Primeiros testes:** comecei seguindo os passos básicos, entendendo cada elemento do Step Functions.
**2.	Explorando possibilidades:** fui testando e modificando, criando fluxos próprios e tentando entender cada detalhe.
**3.	O “experimento bagunçado”:** Na terceira imagem, você vai ver que eu estava testando tudo que aparecia na tela, misturando ideias e fluxos. Sim, ficou uma bagunça! Mas foi nesse caos que eu aprendi coisas valiosas sobre como o Step Functions reage a diferentes inputs, erros e decisões. Cada tentativa foi um passo para entender melhor a ferramenta.


## 🖼️ Capturas de Tela:

**1.	Tela de início do console do AWS Step Functions:**
<img width="1917" height="1033" alt="Imagem 1" src="https://github.com/user-attachments/assets/69615618-0dae-4f9b-af24-15bff9e353f6" />

**2.	Tela do meu modelo de criação:**
<img width="1731" height="1022" alt="Imagem 2" src="https://github.com/user-attachments/assets/8c07ac7d-a6c5-434a-b0f1-7668feea252f" />

**3.	Tela da minha experiência montando um workflow:**
 <img width="1754" height="1029" alt="Imagem 3" src="https://github.com/user-attachments/assets/7147a478-efeb-4e0a-a2d3-7662997ae3b5" />

**4.	Tela pra escolher o modelo pronto:**  
<img width="1791" height="1026" alt="Imagem 4" src="https://github.com/user-attachments/assets/0631a337-9e4f-462f-8c2e-6c8eef0bbc78" />

**5.	Tela do modelo escolhido:**
<img width="1838" height="707" alt="Imagem 5" src="https://github.com/user-attachments/assets/c33ddb73-bc9a-4a0c-85ec-d675f2c43e2d" />

**6.	Tela do workflow e suas funcionalidades:**
   <img width="1909" height="823" alt="Imagem 6" src="https://github.com/user-attachments/assets/d883312e-68b9-4fe2-91ba-a36e7f14b385" />

 
## 💡 Principais Aprendizados:

•	Aprendi a criar workflows claros e organizados, mesmo quando comecei bagunçando tudo.

•	Entendi como usar Choice States para tomar decisões automáticas dentro do fluxo.

•	Descobri como debugar erros e entender porque alguns caminhos não funcionavam.

•	Percebi que errar faz parte do aprendizado — e que é divertido quando a bagunça se transforma em conhecimento!



## 📚 Próximos Passos:

•	Refinar meus workflows, deixando tudo mais limpo e eficiente.

•	Experimentar integrações com outros serviços AWS.

•	Continuar explorando e documentando cada insight, para transformar aprendizado em prática real.


## ✨ Conclusão: 

Esse desafio foi uma experiência incrível! Mostrou que, mesmo quando tudo parece confuso, a curiosidade e a prática transformam bagunça em conhecimento. 

**Feito com dedicação por [Bianca Curcino](https://github.com/bfcurcino-blip).**  

🚀 *Explorando o poder da nuvem com AWS e DIO!*




