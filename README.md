<h1>DESAFIO ILAB AWS (SEMANA 2)</h1>

<h2>ATIVIDADES</h2>

<h3>1. Crie um serviço de mensagens em fila usando a Amazon SQS</h3>

<ul>
    <li>Repositório: <a href="https://github.com/nettojulio/aws-sqs-consomer">AWS Consomer</a></li>
    <li>Repositório: <a href="https://github.com/nettojulio/aws-sqs-producer">AWS Producer</a></li>
</ul>

<h3>2. Compare e descreva as diferenças e o objetivo entre a Amazon SQS e a Amazon SNS</h3>

Definições

<h4>AMAZON SQS</h4>
<p>O Amazon Simple Queue Service (SQS) é um serviço de filas de mensagens gerenciado que permite o desacoplamento e a escalabilidade de microsserviços, sistemas distribuídos e aplicações sem servidor e oferecendo dois tipos de filas de mensagens.</p>
<p>As filas padrão oferecem throughput máximo, o melhor esforço de classificação e entrega pelo menos uma vez. As filas FIFO do SQS são criadas para garantir que as mensagens serão processadas exatamente uma vez, na ordem exata em que forem enviadas.</p>
<p>Podemos afirmar que o SQS é mais eficaz em ocasiões que requisições HTTP podem expirar o tempo de requisição. Sua fácil configuração permite a comunicação entre os microsserviços de forma assíncrona e eficaz.</p>
<h4>AMAZON SNS</h4>
<p>O Amazon Simple Notification Service (Amazon SNS) é um serviço de mensagens totalmente gerenciado para a comunicação de aplicação para aplicação (A2A) e de aplicação para pessoa (A2P).</p>
<p>A funcionalidade pub/sub de A2A fornece tópicos para sistemas de mensagens de alta taxa de transferência baseados em push e de muitos para muitos entre sistemas distribuídos, microsserviços e aplicações sem servidor orientadas por eventos. Usando tópicos do Amazon SNS, seus sistemas editores podem repassar mensagens para um grande número de sistemas de assinantes, incluindo filas do Amazon SQS, funções do AWS Lambda e endpoints HTTPS e o Amazon Kinesis Data Firehose para processamento paralelo. A funcionalidade A2P permite enviar mensagens para usuários em grande escala por SMS, push de dispositivos móveis e e-mail.</p>
<p>Já o SNS é voltado mais para notificações, alertas e ações do sistema em questão. Não sendo viável a utilização para público externo, mas sim pela equipe envolvida no projeto.</p>
