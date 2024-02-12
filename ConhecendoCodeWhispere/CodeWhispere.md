# Code Whisperer 
O Code Whisperer é um assistente gratuito que, instalado em uma IDE como o VSCode ou vinculado ao próprio ambiente 
da AWS, utiliza IA generativa para gerar código para você, de acordo com o contexto do programa 
em que você esteja trabalhando, como uma ferramenta de autocompletar elevada à enésima potência. 
Além disso, ele é capaz de usar a infraestrutura da AWS para escanear o seu código em busca de vulnerabilidades 
e outros problemas de segurança para ajudar a corrigi-las!

## Qual a vantagem de usar o Code Whisperer?
 - É gratuito , basta cadastrar na aws
 - Verificações de segurança : Você pode fazer até 50 por mês, e elas varrem seu código buscando todo tipo de oportunidade de melhoria para apontar e te ajudar a fazer.
 - Contexto da AWS: A ferramenta já vem, de largada, treinada e pronta para te ajudar com quaisquer códigos que envolvam o ferramental da AWS.

## Como usar o Code Whisperer?
1. Instale a extensão AWS Toolkit - Amazon Q, CodeWhisperer, and more;
2. Após instalar, o VSCode irá pedir para que você faça login em sua conta da AWS. Siga adiante nesse processo - ele te direcionará para o browser.
3. Se você não tiver uma conta AWS, siga as instruções da página e crie uma.
4. Para usar a ferramenta, é necessário permitir à Amazon o acesso a certos dados. Leia quais são e, caso concorde, siga adiante.
5. Por fim, acesse a extensão no VSCode, com o login já feito, e habilite as auto-suggestions

### Três formas de usar
Lembre-se que você pode utilizar o Code Whisperer de três maneiras:

1. Iniciando uma linha nova, apertando, por exemplo, o Enter, e esperando ele completá-la, usando Tab e demais atalhos para circular pelas sugestões e aceitar alguma.
2. Apertando Alt + C, ou Option + C, para ver numa lista todas as opções de código que o Code Whisperer gerou para aquela linha.
3. Escrevendo um comentário com um comando, como Faça um teste automatizado para a função LALALA, e deixando o Code Whisperer autocompletar na linha seguinte uma porção maior de código.

# Conhecendo Code Whispere
É uma solução de code Companion ajuda a construir aplicações de forma mais rápida e segura ,
gerando os codigos em tempo real diretamente na sua ide , vai configurar a IDE com o serviço ,
vai descrever as funções qeu você gostaria  , ele vai ajudar a criar o codigo , vai gerar esse códigos
de forma automática, tudo dentro da sua ide.

## Onde é retirado o codigo no Code Whispere
O modelo foi treinado em bilhões de codigo , treinado numa base de dados open source e uma base de dados
proprietária da AWS , tudo que estiver aberto na IDE ele vai contar , os arquivos , as bibliotecas que importou
as funçoes que tem dentro do arquivo os comentarios que coloca dentro do codigo, tudo isso vai ser passado como
como dado de contexto pro Amazon code Whisper que irá usar essas informações para gerar o codigo.
Os dados serão armazenado de forma efêmera vai ser acessado pelos Amazon COde Whispere e vai ser deletado após
gerar a recomendação para o cliente , então nenhum dado de propriedade telectual do cliente vai ser armazenado para
melhoria

- Licença entreprise: não irá compartilhar os dados.
- Linceça free: compartilha esse dado temporariamente, mas pode configurar na sua ide para não compartilhar


## Open Code Reference log
Permite que veja as referências de quando gerar um código licenciado,

## Securiy Scan
ajuda a indentificar se a biblioteca é segura, ele começa a buscar dentro da sua pasta e fazer uma análise
de segurança do que tem linkando vunerabilidade lá do Open e web application   