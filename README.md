 <h1>AWSConceitos</h1>
    
   <img src="https://images.ctfassets.net/6yom6slo28h2/627q8AupcAWUiqMwkcESeS/d04f3bf1523f22249b0b80770fa2224e/featured-aws-cloud.png?w=500&h=324&q=100&fm=webp " alt="Imagem AWS">

   <h2>Introdução à AWS</h2>
   <h3>Conteúdo Essencial</h3>

   <p>Os Três Modelos de Implementação de Computação em Nuvem:</p>
    <ul>
        <li>Implantação Baseada na Nuvem:
            <ul>
                <li>Migrar aplicativos existentes para a nuvem.</li>
                <li>Projetar e criar novos aplicativos diretamente na nuvem.</li>
            </ul>
        </li>
        <li>Implantação no Local:
            <ul>
                <li>Também conhecida como implantação de nuvem privada.</li>
                <li>Recursos implantados localmente usando ferramentas de virtualização e gerenciamento de recursos.</li>
            </ul>
        </li>
        <li>Implantação Híbrida:
            <ul>
                <li>Recursos baseados em nuvem conectados à infraestrutura local.</li>
                <li>Útil em situações como manutenção de aplicativos legados no local ou conformidade com regulamentações governamentais.</li>
            </ul>
        </li>
    </ul>

   <p>Benefícios da Computação em Nuvem:</p>
    <ul>
        <li>Troque Despesas Iniciais por Despesas Variáveis.</li>
        <li>Pare de gastar dinheiro para executar e manter datacenters.</li>
        <li>Pare de Tentar Adivinhar a Capacidade.</li>
        <li>Beneficie-se de enormes economias de escala.</li>
        <li>Aumente a Velocidade e a Agilidade.</li>
        <li>Tenha Alcance Global em Minutos.</li>
    </ul>

   <p>Este módulo fornece uma visão geral dos modelos de implementação em nuvem e destaca os benefícios fundamentais que a computação em nuvem oferece. Entender esses conceitos é crucial para explorar efetivamente os serviços e recursos disponíveis na Amazon Web Services (AWS).</p
                                                                                                                                                                                                                                                                                       
   <h2>Módulo 2: Computação</h2>
    <h3>Conteúdo Essencial</h3>

   <p><strong>SUPER IMPORTANTE!</strong></p>

   <p>Amazon Elastic Compute Cloud (Amazon EC2):</p>
   <p>O Amazon EC2 fornece capacidade computacional segura e redimensionável na nuvem como instâncias do Amazon EC2.</p>

   <p>Tipos de instância do EC2:</p>
    <ul>
 <li><strong>Instância Tipo T2:</strong> Projetada para cargas de trabalho com requisitos de CPU intermitentes. Ideal para aplicativos de desenvolvimento e teste.</li>
    <li><strong>Instância Tipo M5:</strong> Oferece um equilíbrio entre recursos de computação, memória e armazenamento. Adequada para aplicativos de banco de dados e servidores de aplicativos.</li>
    <li><strong>Instância Tipo C5:</strong> Otimizada para cargas de trabalho de computação de alto desempenho. Indicada para processamento de dados intensivo.</li>
    </ul>

   <p>Definição de preços do EC2:</p>
    <ul>  <li><strong>Preço Sob Demanda:</strong> Pague pelo uso sem compromissos de longo prazo. Ideal para cargas de trabalho com demanda variável ou desconhecida.</li>
    <li><strong>Preço Reservado:</strong> Comprometa-se com um contrato de um ou três anos para obter descontos significativos em comparação com os preços sob demanda.</li>
    <li><strong>Preço Spot:</strong> Aproveite os preços variáveis do mercado, ideais para cargas de trabalho tolerantes a interrupções e flexíveis em termos de tempo.</li>
   
   </ul>

   <p>Escalabilidade:</p>
    <p>A escalabilidade envolve começar apenas com os recursos de que você precisa e projetar sua arquitetura para responder automaticamente às alterações de demanda, fazendo aumentos ou reduções.</p>

   <p>Escalonamento automático do Amazon EC2:</p>
    <p>Se você quiser que o processo de escalabilidade aconteça automaticamente, qual serviço AWS você usaria? O serviço AWS que fornece essa funcionalidade para instâncias do Amazon EC2 é o Amazon EC2 Auto Scaling.</p>

   <p>Balanceamento de carga elástico:</p>
    <p>É o serviço AWS que distribui automaticamente o tráfego de entrada de aplicativos entre vários recursos, como instâncias do Amazon EC2.</p>

   <h2>Sistema de mensagens e arquivo:</h2>
    <ul>
      
   <p>O <strong>Amazon Simple Notification Service (Amazon SNS)</strong> é um serviço de publicação/assinatura. Utilizando tópicos do Amazon SNS, um editor envia mensagens para assinantes, semelhante a uma cafeteria onde o operador de caixa entrega pedidos ao barista que prepara as bebidas.</p>

   <p>O <strong>Amazon Simple Queue Service (Amazon SQS)</strong> é um serviço de enfileiramento de mensagens. Ele é utilizado para enviar, armazenar e receber mensagens entre componentes de software, garantindo que as mensagens não se percam e não dependam da disponibilidade de outros serviços. Em um ambiente Amazon SQS, um aplicativo envia mensagens para uma fila, e um usuário ou serviço recupera, processa e exclui a mensagem da fila.</p>
    <p><strong>AWS Lambda:</strong></p>
    <p>O AWS Lambda permite a execução de códigos sem a necessidade de provisionar ou gerenciar servidores. Você paga apenas pelo tempo de computação consumido, aplicando cobranças apenas durante a execução do código. Isso proporciona a capacidade de executar códigos para diversos tipos de aplicativos ou serviços de back-end sem a necessidade de gerenciamento adicional.</p>

   <p><strong>Container:</strong></p>
    <p>Os contêineres são uma maneira comum de empacotar códigos, configurações e dependências do aplicativo em um único objeto. São úteis para processos e fluxos de trabalho com requisitos essenciais de segurança, confiabilidade e escalabilidade.</p>

   <p><strong>Amazon Elastic Container Service (Amazon ECS):</strong></p>
    <p>O Amazon ECS é um sistema de gerenciamento de contêineres altamente dimensionável e de alto desempenho. Permite a execução e escalabilidade de aplicativos em contêineres na AWS, compatível com contêineres Docker. Com o Amazon ECS, você pode usar chamadas de API para iniciar e interromper aplicativos baseados em Docker.</p>

   <p><strong>Amazon Elastic Kubernetes Service (Amazon EKS):</strong></p>
    <p>O Amazon EKS é um serviço totalmente gerenciado para executar o Kubernetes na AWS. O Kubernetes é um software de código aberto para implantar e gerenciar aplicativos em contêineres em grande escala. A AWS colabora ativamente com a comunidade Kubernetes para fornecer suporte contínuo e facilidade na aplicação de atualizações aos aplicativos gerenciados pelo Amazon EKS.</p>

   <p><strong>AWS Fargate:</strong></p>
    <p>O AWS Fargate é um mecanismo de computação sem servidor para contêineres, compatível com o Amazon ECS e o Amazon EKS. Com o AWS Fargate, você não precisa provisionar ou gerenciar servidores, pois ele cuida da infraestrutura de servidor para você. Isso permite que você se concentre na inovação e no desenvolvimento de seus aplicativos, pagando apenas pelos recursos necessários para executar os contêineres.</p>

   </ul>
   <p>Curtiu? Compartilhe! <a href='https://www.linkedin.com/in/edson-bruno-dev/'>Edson Bruno Linkedin</a> <3
