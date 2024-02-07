# Amazon Bedrock 
1) No console clicar no Amazon Bedrock 
![img_1.png](imagens/img_11.png)

2) Dentro do Amazon Bedrock temos o menu de modelo de acesso,  clicar em managem model acess, 
você escolher os modelos , e após escolher clique em salve changes .  

![img_2.png](imagens/img_20.png)
![img_4.png](imagens/img_22.png)

3) No proprio console tem o playground onde você pode escolher os provedores de modelos 

![img_5.png](imagens/img_23.png)

Exemplo de Text playground 
![img_6.png](imagens/img_24.png)

Exemplo de geração de imagem : abaixo ele pede um novo produto, o qual teria que ser uma caixa azul com o logo da AWS
![img_7.png](imagens/img_25.png)

## Usando o Bedrock interação usando um arquivo

1) No menu a esquerda Knowledege base
![img_8.png](imagens/img_26.png)
2) Clique em create Knowledge base

![img_9.png](imagens/img_27.png)

3) Insira um nome , uma descrição , uma role , em tags tem a opção de apontar um arquivo no S3 e clique em next ,
e crie uma base vetorial e aperte next.
![img_10.png](imagens/img_28.png)
![img_13.png](imagens/img_13.png)
![img_14.png](imagens/img_14.png)

4) Vai criar um open source serveless (onde irá armazenar os vetores e é uma base serveless)
![img_15.png](imagens/img_15.png)

5) Na collections no menu a esquerda , é a collection que o Bedrock criou automaticamente 

![img_16.png](imagens/img_16.png)
6) Então irá clicar em Sync que seria para sincronizar com o arquivo que apontou no S3 e converter o pdf para vetor
![img_17.png](imagens/img_17.png)
7) VocÊ escolhe o modelo que irá interagir , no exemplo abaixo foi utilizado o claude , observe que ele faz um pergunta 
e o claude responde baseado no arquivo que foi sincronizado ou seja foi criado um chatbot 
![img_18.png](imagens/img_18.png)
8) 
