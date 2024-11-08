# RESUMO DO ÚLTIMO MÓDULO

## CURSO 📒
### Instrodução a Computação em Nuvem 
A comutação em nuvem refere-se ao fornecimento de serviços de computação por meio da internet, possibilitando inovações mais rápidas, recursos escaláveis e economia de escala.

Tipos de Nuvem ☁️
- Nuvem Privada: As organizações criam e gerenciam um ambiente de nuvem dentro de seus próprios data centers. O controle sobre os serviços e a segurança é total, mas a nuvem privada não oferece acesso a usuários fora da organização.
- Nuvem Pública: Oferecida por provedores de serviços de nuvem ou empresas de hospedagem. Ela disponibiliza recursos e serviços para várias organizações e usuários, sendo acessada por meio de uma rede segura, geralmente pela internet.
- Nuvem Híbrida: Combina elementos das nuvens públicas e privadas, permitindo que os aplicativos sejam executados no ambiente mais adequado, dependendo das necessidades da organização.

Comparação entre os Tipos de Nuvem 🆚
- Nuvem Pública: Não há necessidade de investimentos em infraestrutura física (CapEx) para escalabilidade. Os aplicativos podem ser rapidamente provisionados e desprovisionados, e as organizações pagam apenas pelos recursos efetivamente utilizados.
- Nuvem Privada: Oferece maior controle sobre os recursos e a segurança, uma vez que a organização gerencia a infraestrutura. A organização é responsável pela manutenção, atualizações de hardware e software.
- Nuvem Híbrida: Permite maior flexibilidade, pois a organização decide onde seus aplicativos serão executados. Oferece controle sobre segurança, conformidade e requisitos legais, equilibrando os benefícios da nuvem pública e privada.

Comparação entre CapEx e OpEx 🆚
- CapEx (Despesas de Capital): Refere-se ao investimento inicial em infraestrutura física. Esses custos são depreciados ao longo do tempo, com o valor dos ativos diminuindo conforme o uso.
- OpEx (Despesas Operacionais): São os gastos recorrentes com produtos e serviços conforme a necessidade. No modelo de OpEx, os pagamentos são feitos conforme o uso, sem a necessidade de grandes investimentos iniciais.

Os provedores de serviços em nuvem adotam o modelo baseado no consumo, ou seja, os usuários pagam apenas pelos recursos que realmente utilizam.

## DESAFIO DE PROJETO ⚙️
### Microsoft Azure - Localizando Serviços por Categoria
O Portal do Microsoft Azure é uma plataforma completa que oferece uma ampla gama de serviços para soluções em nuvem. A seguir, apresentamos uma visão geral dos principais recursos disponíveis no portal.

Painel Esquerdo 🖥️
Ao clicar no botão "Todos os serviços", você tem acesso a uma lista completa dos serviços oferecidos pelo Azure. Entre as opções, destacam-se: Inteligência Artificial e Machine Learning, Banco de Dados, DevOps, e Computação.

Categoria: Computação 👩‍💻
Esta categoria inclui uma variedade de serviços essenciais, como:
- Área de Trabalho Virtual do Azure
- Máquinas Virtuais
- Imagens
- Habilidades SSH e muito mais.
  
Categoria: Rede 🌐
Na área de Rede, o Azure oferece recursos avançados para garantir a conectividade e segurança, como:
- Azure Bastion (rede segura)
- Links de Rede
- Zonas de DNS
- Firewalls
  
Categoria: Armazenamento 💾
Os serviços de Armazenamento no Azure incluem opções como:
- Servidores
- Discos
- Migração de dados

Essas categorias representam apenas uma amostra dos serviços disponíveis, permitindo que você crie, gerencie e expanda suas soluções em nuvem com flexibilidade e segurança.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## CURSO 📒
### Benefícios da Computação em Nuvem

Alta Disponibilidade 🔝 
- A Azure se concentra em garantir a máxima disponibilidade, assegurando que os serviços permaneçam acessíveis mesmo durante interrupções ou eventos imprevistos.

Escalabilidade 📈
- A capacidade de ajustar recursos conforme a demanda. Com a Azure, você pode adicionar mais recursos para lidar com picos de demanda e pagar apenas pelo que usar, sem custos extras desnecessários.

Elasticidade ↗️ 
- A Azure permite ajustar os recursos de forma flexível diante de flutuações repentinas na demanda. Em caso de aumento, os recursos podem ser expandidos automaticamente ou manualmente; em caso de queda, os recursos são reduzidos de forma proporcional.

Confiabilidade 🔒 
- Com infraestrutura robusta e resiliente, a Azure garante a confiabilidade de seus serviços, com recursos distribuídos em várias regiões do mundo para minimizar riscos.

Previsibilidade 📊 
- Avance com confiança, sabendo exatamente o que esperar tanto em termos de desempenho quanto de custo, permitindo um planejamento eficiente e sem surpresas.

Segurança 🛡️ 
- A Azure oferece ferramentas de segurança avançadas, atendendo a uma ampla gama de necessidades dos clientes e garantindo a proteção dos dados e sistemas na nuvem.

Governança 📋 
- Com auditorias baseadas em nuvem, a Azure facilita a identificação de recursos fora de conformidade com os padrões corporativos, além de oferecer estratégias de mitigação. Atualizações e patches são aplicados automaticamente, garantindo que sua nuvem esteja sempre protegida e bem gerenciada.

Gerenciabilidade 🛠️ 
- O gerenciamento de recursos na Azure é facilitado com modelos pré-configurados para implantação, eliminando a necessidade de configurações manuais e tornando o processo mais eficiente e controlado.

## DESAFIO DE PROJETO ⚙️
### Criando Máquinas Virtuais na Azure

No contexto dos serviços em nuvem, um SLA (Acordo de Nível de Serviço) define as responsabilidades do provedor de nuvem e os padrões de desempenho que ele deve garantir, como disponibilidade (tempo de uptime), capacidade de armazenamento, velocidade de processamento, suporte técnico e tempo de resposta para resolução de incidentes. O SLA também pode especificar compensações ou penalidades caso o provedor não cumpra as metas acordadas, assegurando que o cliente tenha acesso a um serviço consistente e confiável.

--- colocar imagem

Ao criar uma Máquina Virtual (VM), o cliente pode escolher configurações de Opções de Disponibilidade e Zona de Disponibilidade, que impactam diretamente o SLA, determinando a redundância e a resiliência do serviço.

Da mesma forma, ao configurar uma conta de armazenamento, a escolha de replicar dados entre datacenters e regiões pode afetar o SLA. Quanto mais cópias dos dados forem feitas, maior a redundância e a disponibilidade do serviço. Porém, é importante observar que, ao aumentar a replicação, o tempo de recuperação também pode ser otimizado, o que contribui para a melhoria da disponibilidade.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## CURSO 📒
### Tipos de Serviço em Nuvem

IaaS (Infraestrutura como Serviço) 💻 ➡️ 🖥️🔐🏢
- O IaaS fornece infraestrutura de TI sob demanda, permitindo que os clientes aluguem servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais de um provedor de nuvem. O provedor gerencia a infraestrutura física, como servidores, firewalls, segurança da rede e a planta física do datacenter, enquanto o cliente é responsável pelo sistema operacional, aplicativos e dados.

PaaS (Plataforma como Serviço) 🖥️➡️⚙️💡📊
- O PaaS vai além do IaaS, fornecendo uma plataforma completa para o desenvolvimento, teste e implantação de aplicativos. O provedor cuida da infraestrutura (servidores, armazenamento, redes, sistemas operacionais, segurança) e da plataforma (ferramentas para desenvolvedores, banco de dados, e análises de negócios), enquanto o cliente foca apenas na criação e gerenciamento das aplicações.

SaaS (Software como Serviço) 📱➡️🌐🔧📲
- O SaaS oferece aplicativos hospedados na nuvem acessíveis pela internet. O provedor gerencia toda a infraestrutura, sistemas operacionais, plataformas e aplicativos, enquanto o cliente se preocupa apenas com o uso dos serviços e a gestão de dados. O modelo de pagamento é baseado no uso, geralmente em formato de assinatura.

Modelo de Responsabilidade Compartilhada
- IaaS: O provedor gerencia a infraestrutura, enquanto o cliente é responsável pelo sistema operacional, aplicativos e dados.
- PaaS: O provedor gerencia tanto a infraestrutura quanto a plataforma (ferramentas e banco de dados), e o cliente é responsável pelas aplicações e dados.
- SaaS: O provedor gerencia toda a infraestrutura, plataforma e software, enquanto o cliente é responsável apenas pelos dados e pelo uso do serviço.

---colocar imagem

Comparação dos Modelos 🆚
- IaaS: O serviço de nuvem mais flexível. O cliente configura e gerencia o hardware e a infraestrutura para seu aplicativo.
- PaaS: Focado no desenvolvimento de aplicativos. O provedor gerencia a plataforma e os recursos necessários para a criação de software.
- SaaS: Modelo de preço por uso. Os usuários pagam pela assinatura de aplicativos prontos para uso na nuvem.

## DESAFIO DE PROJETO ⚙️
### Configurando uma Instância de Banco de dados na Azure

No Painel Esquerdo, Opção: Banco de Dados SQL 📊

Configurar o Banco de Dados  🔧 
- Nome do Banco: Defina um nome exclusivo para o seu banco de dados.
- Criar e Utilizar um Servidor: Você precisará criar um servidor ou selecionar um servidor existente para hospedar o banco de dados.
- Modelo de Redundância: Escolha o modelo de redundância para garantir alta disponibilidade e recuperação de falhas. (Exemplos: redundância entre zonas de disponibilidade ou réplicas em diferentes regiões).
- Custo Estimado: O próprio Azure calcula automaticamente o custo com base na configuração escolhida, considerando fatores como capacidade de armazenamento, número de conexões e redundância.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## CURSO 📒
### Deploy na nuvem Microsoft Azure Cloud.

O deploy na nuvem Microsoft Azure é o processo de disponibilizar uma aplicação ou serviço na infraestrutura da Azure. Ele pode ser feito de várias formas, como:
- App Services para aplicações web.
- Máquinas Virtuais (VMs) para maior controle de ambiente.
- Contêineres (AKS, ACI) para aplicações baseadas em Docker.
- Azure Functions para soluções serverless.
- Azure DevOps para automação de deploy com CI/CD.
- O Azure oferece escalabilidade, alta disponibilidade, segurança e integração com outras soluções da Microsoft.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## CURSO 📒
### Introdução a Conceitos de Mensageria e Service Bus com Azure

Mensagem: É um pacote de dados que pode estar em diferentes formatos, como XML, JSON ou bytes.

Evento: Refere-se a uma notificação leve que indica uma condição ou alteração de estado em um sistema.

Filas: Armazenam mensagens até que o aplicativo receptor esteja disponível para recebê-las e processá-las. Elas garantem a entrega confiável de mensagens em uma arquitetura assíncrona.

Tópicos: Permitem múltiplas assinaturas independentes, possibilitando que diferentes assinantes recebam a mesma mensagem, de acordo com seu interesse.

Event Grid: É uma ferramenta do Azure que suporta arquiteturas orientadas a eventos, utilizando o modelo Pub/Sub (Publicação/Assinatura). Ele facilita a distribuição de eventos de maneira eficiente e escalável.

O que é o Azure Service Bus? O Azure Service Bus é um mediador de mensagens totalmente gerenciado, confiável e seguro para a transferência assíncrona de dados. Ele permite a comunicação entre sistemas utilizando filas e tópicos, possibilitando o envio e o recebimento de mensagens de maneira desacoplada e escalável.

É possível criar filas no Azure Service Bus? Sim, é possível criar filas no Azure Service Bus diretamente pelo portal do Azure. Você pode criar um namespace, adicionar filas ao barramento de serviço e configurar credenciais de autorização para que aplicativos clientes possam enviar e receber mensagens de forma segura e eficiente.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## RESUMO DO CURSO

Para ter acesso ao resumo do curso completo, clone e baixe a projeto na sua máquina e acesse o arquivo:
- estudos.txt
