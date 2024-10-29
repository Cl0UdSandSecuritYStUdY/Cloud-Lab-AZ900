# Cloud-Lab-AZ900
Resumo dos conteúdos cobrados na certificação AZ-900:  Azure Fundamentals. Conteúdo adquirido e desenvolvidos com apoio do site da Microsoft e do Bootcamp da DIO.

O que é computação em Nuvem?

A computação em nuvem é a entrega de serviços de computação pela Internet. Os serviços de computação incluem infraestrutura de TI comum, como máquinas virtuais, armazenamento, bancos de dados e rede. Os serviços de nuvem também expandem as ofertas tradicionais de TI para incluir itens como IoT (Internet das Coisas), ML (machine learning) e IA (inteligência artificial).

Como a computação em nuvem usa a Internet para fornecer esses serviços, ela não precisa ficar restrita pela infraestrutura física da mesma forma que um datacenter tradicional. Isso significa que, se você precisar aumentar rapidamente sua infraestrutura de TI, não precisará esperar para construir um novo datacenter; você pode usar a nuvem para expandir rapidamente seu volume de TI.

Rápida introdução à computação em nuvem:

Como quando você compra um computador, a computação em nuvem permite escolher a capacidade e os recursos necessários para executar o software.
 A diferença é que , na computação em nuvem, o computador fica no data center de um provedor de nuvem e não fisicamente com você.
Assim, você pode pagar apenas pelos serviços que usa. Além disso, outra pessoa pode gerenciar a manutenção do computador.
Cada provedor de nuvem tem a própria seleção de serviços para você escolher, mas os serviços básicos fornecidos por todos os provedores de nuvem são potência de computação e armazenamento.
A potência de computação (Computer power) é a quantidade de processamento que o computador consegue executar.
Por exemplo, ao comprar um computador doméstico, você pode escolher um computador com oito gigabytes de RAM e o processador mais recente para executar o software de que precisa hoje. Mas, à medida que a carga  no computador aumenta, você percebe que ele fica mais lento. Na computação em nuvem, você pode adicionar e remover potência de computação conforme a necessidade. Isso gera economia, pois você só paga pelos recursos que usa.
Armazenamento (Storage) é o volume de dados que pode ser armazenado no computador.
Um computador tradicional tem o espaço em disco rígido limitado. Com o tempo, você pode ficar sem espaço e precisar comprar outro disco rígido para armazenar mais dados. Na computação em nuvem, você pode solicitar mais armazenamento conforme a necessidade. 
Os provedores de nuvem gerenciam a manutenção do computador para que você não precise fazer. Eles asseguram a presença de backups, a atualização do sistema operacional e também que tudo esteja em funcionamento 24 horas por dia.
Então, à medida que seus negócios crescem e as necessidades de computação mudam, você pode contar com novos recursos de computação de modo rápido e econômico.

Modelo de responsabilidade compartilhada:

Comece com um datacenter corporativo tradicional. A empresa é responsável por manter o espaço físico, garantir a segurança e manter ou substituir os servidores se algo acontecer. O departamento de TI é responsável por manter toda a infraestrutura e o software necessários para manter o datacenter em funcionamento. É provável que eles também sejam responsáveis por manter todos os sistemas corrigidos e na versão correta.
Com o modelo de responsabilidade compartilhada, essas responsabilidades são compartilhadas entre o provedor de nuvem e o consumidor. Segurança física, energia, resfriamento e conectividade de rede são responsabilidade do provedor de nuvem. O consumidor não fica na mesma localização do datacenter, portanto, não faria sentido que o consumidor tivesse algumas dessas responsabilidades.
Ao mesmo tempo, o consumidor é responsável pelos dados e pelas informações armazenados na nuvem. (Você não gostaria que o provedor de nuvem pudesse ler suas informações). O consumidor também é responsável pela segurança de acesso, o que significa que você só dá acesso àqueles que precisam.
Então, para algumas coisas, a responsabilidade depende da situação. Se você estiver usando um banco de dados SQL na nuvem, o provedor de nuvem será responsável pela manutenção do banco de dados real. No entanto, você ainda será responsável pelos dados que são ingeridos no banco de dados. Se você implantasse uma máquina virtual e instalasse um banco de dados SQL nela, seria responsável pelos patches e atualizações do banco de dados, além da manutenção dos dados e das informações armazenados no banco de dados.
Com um datacenter local, você é responsável por tudo. Com a computação em nuvem, essas responsabilidades mudam. O modelo de responsabilidade compartilhada está fortemente vinculado aos tipos de serviço de nuvem (abordados posteriormente neste roteiro de aprendizagem): IaaS (infraestrutura como serviço), PaaS (plataforma como serviço) e SaaS (software como serviço). A IaaS coloca a maior responsabilidade sobre o consumidor, com o provedor de nuvem sendo responsável pelas questões básicas de segurança física, energia e conectividade. Na outra ponta do espectro, o SaaS coloca a maior parte da responsabilidade no provedor de nuvem. A PaaS, sendo um meio termo entre IaaS e SaaS, situa-se no meio desses dois cenários e distribui uniformemente a responsabilidade entre o provedor de nuvem e o consumidor.

Diagrama do Modelo de responsabilidade Compartilhada dependendo do tipo de serviço em nuvem:



Ao usar um provedor de nuvem, você sempre será responsável por:
	• Informações e dados armazenados na nuvem
	• Dispositivos que têm permissão para se conectar à nuvem (telefones celulares, computadores e assim por diante)
	• Contas e identidades das pessoas, serviços e dispositivos em sua organização
O provedor de nuvem é sempre responsável por:
	• Datacenter físico
	• Rede física
	• Hosts físicos
Seu modelo de serviço determinará a responsabilidade por coisas como:
	• Sistemas operacionais
	• Controles de rede
	• Aplicativos
	• Identidade e infraestrutura
	
Definir modelos de nuvem:

Nuvem privada: 

Uma nuvem privada é, de certa forma, a evolução natural de um datacenter corporativo. Ela é uma nuvem (que fornece serviços de TI pela Internet) usada por uma única entidade. A nuvem privada fornece um controle muito maior para a empresa e o departamento de TI. No entanto, ela também tem mais custos e menos benefícios em relação a uma implantação de nuvem pública. Por fim, uma nuvem privada pode ser hospedada em seu datacenter local. Ela também pode ser hospedada em um datacenter dedicado externo, até mesmo por terceiros que tenham dedicado esse datacenter à sua empresa.

Nuvem pública:

Uma nuvem pública é criada, controlada e mantida por um provedor de nuvem de terceiros. Com uma nuvem pública, qualquer pessoa que queira comprar serviços de nuvem pode acessar e usar os recursos. A disponibilidade pública geral é uma diferença fundamental entre nuvens públicas e privadas.

Nuvem híbrida:

Uma nuvem híbrida é um ambiente de computação que usa nuvens públicas e privadas em um ambiente interconectado. Um ambiente de nuvem híbrida pode ser usado para permitir que uma nuvem privada escale para atender a uma demanda maior temporária implantando recursos de nuvem pública. A nuvem híbrida pode ser usada para fornecer uma camada adicional de segurança. Por exemplo, os usuários podem escolher com flexibilidade quais serviços manter na nuvem pública e quais implantar na infraestrutura de nuvem privada.



Várias nuvens (multinuvem):

O quarto cenário, é um cenário de várias nuvens. Em um cenário de várias nuvens, você usa vários provedores de nuvem pública. Talvez você use recursos diferentes de diferentes provedores de nuvem. Ou você pode ter iniciado seu percurso de nuvem com um provedor e esteja em processo de migração para um provedor diferente. Independentemente disso, em um ambiente de várias nuvens, você lida com dois (ou mais) provedores de nuvem pública e gerencia recursos e segurança em ambos os ambientes.

Azure Arc

O Azure Arc é um conjunto de tecnologias que ajuda a gerenciar seu ambiente de nuvem. O Azure Arc pode ajudar a gerenciar o seu ambiente de nuvem, seja uma nuvem pública exclusivamente no Azure, uma nuvem privada em seu datacenter, uma configuração híbrida ou até mesmo um ambiente de várias nuvens em execução em vários provedores de nuvem ao mesmo tempo.

Solução VMware no Azure

E se você já estiver estabelecido com o VMware em um ambiente de nuvem privada, mas quiser migrar para uma nuvem pública ou híbrida? A Solução VMware no Azure permite executar suas cargas de trabalho do VMware no Azure com integração e escalabilidade total.

Modelo baseado em consumo:

A CapEx normalmente é uma despesa inicial única para comprar ou proteger recursos tangíveis. Um prédio novo, a repavimentação do estacionamento, a construção de um datacenter ou a compra de um veículo da empresa são exemplos de CapEx.
Ao contrário, a OpEx é o gasto de capital em serviços ou produtos ao longo do tempo. O aluguel de um centro de convenções, o leasing de um veículo da empresa ou a assinatura de serviços de nuvem são exemplos de OpEx.

A computação em nuvem se enquadra na OpEx porque opera em um modelo baseado em consumo. Na computação em nuvem, você não paga pela infraestrutura física, pela eletricidade, pela segurança nem por nada que esteja associado à manutenção de um datacenter. Você paga pelos recursos de TI que usa. Se você não usar nenhum recurso de TI durante o mês, não pagará nada.
Um modelo baseado em consumo oferece vários benefícios, como:
	• Sem custos prévios.
	• Não há necessidade de comprar nem gerenciar uma infraestrutura cara que os usuários talvez não usem na capacidade máxima.
	• A capacidade de pagar para obter mais recursos quando necessário.
	• A capacidade de parar de pagar por recursos que não são mais necessários.
	
Em um modelo baseado em nuvem, você não precisa se preocupar em acertar perfeitamente as necessidades de recursos. Se você achar que precisa de mais máquinas virtuais, bastará adicioná-las. Se a demanda cair e você não precisar de tantas máquinas virtuais, bastará remover algumas, conforme o necessário. De qualquer forma, você só paga pelas máquinas virtuais que usa, não pela "capacidade extra" que o provedor de nuvem tem em mãos.

Comparar os modelos de preços de nuvem
Computação em nuvem é a entrega de serviços de computação pela Internet, usando o modelo de preço pago conforme o uso. Normalmente, você paga apenas pelos serviços de nuvem que usa, o que ajuda a:
	• Planeje e gerencie os custos operacionais.
	• Executar a infraestrutura com mais eficiência.
	• Escale as operações de acordo com as necessidades de negócios.
Em outras palavras, a computação em nuvem é uma forma de alugar capacidade computacional e armazenamento do datacenter de terceiros. Você pode tratar os recursos de nuvem como faria com os recursos em seu próprio datacenter. Mas, ao contrário do seu próprio datacenter, ao terminar de usar os recursos de nuvem, basta devolvê-los. Você é cobrado apenas pelo que usa.
Em vez de manter CPUs e armazenamento no seu datacenter, você aluga esses recursos pelo tempo necessário. O provedor em nuvem é responsável por manter a infraestrutura subjacente para você. A nuvem permite que você supere rapidamente os desafios empresariais mais difíceis e ofereça soluções de ponta para seus usuários.

Os benefícios da alta disponibilidade e da escalabilidade na nuvem:

Ao criar ou implantar um aplicativo de nuvem, duas das maiores considerações são o tempo de atividade (ou disponibilidade) e a capacidade de lidar com a demanda (ou a escala).

Alta disponibilidade:

Quando você está implantando um aplicativo, um serviço ou qualquer recurso de TI, é importante que os recursos estejam disponíveis quando necessário. A alta disponibilidade se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer.
Ao arquitetar sua solução, você precisará considerar as garantias de disponibilidade do serviço. O Azure é um ambiente de nuvem altamente disponível com garantias de tempo de atividade, dependendo do serviço. Essas garantias fazem parte dos SLAs (Contratos de Nível de Serviço).

Azure service level agreements (SLAs) - é um contrato formal entre um provedor de serviços e o cliente que garante ao cliente um nível de serviço declarado. O provedor de serviços pode ser uma empresa comercial que fornece o serviço, como a Microsoft, quando você usa os serviços do Azure.
Mas os SLAs também são usados dentro das organizações, em um contrato entre o departamento de TI e os usuários de negócios.
Os contratos de nível de serviço do Azure são representados como um percentual relacionado à disponibilidade do serviço ou do aplicativo. Essa disponibilidade também é conhecida como "tempo de atividade".
Se o serviço estivesse sempre disponível para uso, você diria que estava 100% disponível ou que tinha 100% de tempo de atividade.
Um SLA também geralmente inclui detalhes como o que é definido como tempo de inatividade, quando o serviço está indisponível e qualquer crédito a que você possa ter direito se o SLA não for cumprido.
Na realidade, 100% de tempo de atividade é difícil e caro de alcançar, porque não permite tempo para interromper o serviço para manutenção ou atualizações necessárias. Também exigiria as duplicação de cada componente em caso de falha de um componente e exigiria que esses componentes de backup realizassem as tarefas de serviço sem interrupção para o cliente.
Por esses motivos, SLAs de 99%, 99,9% e 99,95% são mais comuns. 99,99% também está disponível em alguns serviços no Azure. Existe uma grande diferença em um serviço que está 99% disponível vs que está 99,9% disponível? Sim, um serviço com um percentual de SLA 99%  pode ficar indisponível por até 1,6 horas por semana ou 7,2horas por mês e ainda estar 99% disponível. Esse tempo é cumulativo, o que significa que pode ser somado em vários incidentes de indisponibilidade do serviço. Um serviço com um percentual de SLA 99,9% pode ficar indisponível por apenas 10 minutos por semana ou 43,2 minutos por mês.
Se o serviço for crítico para o seu negócio, minutos versus horas de inatividade podem fazer grande diferença, mas os serviços altamente disponíveis tem custo extra. Cada serviço do Azure tem seu próprio SLA.

Escalabilidade:

Outro grande benefício da computação em nuvem é a escalabilidade dos recursos de nuvem. A escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda. Se você experimentar um pico repentino de tráfego e seus sistemas ficarem sobrecarregados, a capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.
O outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços. Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa. Se a demanda cair, você poderá reduzir seus recursos e, assim, reduzir seus custos.
A escala geralmente vem em duas variedades: vertical e horizontal. A escala vertical se concentra em aumentar ou diminuir a capacidade dos recursos. A escala horizontal é adição ou subtração do número de recursos.

Dimensionamento vertical:

Com a escala vertical, se você estivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual. Por outro lado, se você percebesse que superestimou as necessidades, poderia reduzir verticalmente, diminuindo as especificações de CPU ou RAM.

Dimensionamento horizontal:

Com a escala horizontal, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente). Por exemplo, você pode adicionar máquinas virtuais ou contêineres por meio da expansão. Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente (de maneira automática ou manual).

Os benefícios da confiabilidade e da previsibilidade na nuvem

Confiabilidade
Resiliência é a capacidade que um sistema tem de se recuperar de falhas e continuar funcionando. Ela também é um dos pilares do Microsoft Azure Well-Architected Framework.
Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente. Com um design descentralizado, a nuvem permite que você tenha recursos implantados em várias regiões do mundo. Com essa escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento. Você pode criar aplicativos para aproveitar automaticamente essa confiabilidade maior. Em alguns casos, o próprio ambiente de nuvem mudará automaticamente para uma região diferente, sem que você precise realizar nenhuma ação. Você entenderá melhor como o Azure aproveita a escala global para oferecer confiabilidade mais adiante nesta série.

Previsibilidade

A previsibilidade na nuvem permite que você avance com confiança. A previsibilidade pode se concentrar na previsibilidade de desempenho ou na previsibilidade de custo. Tanto a previsibilidade de desempenho quanto a de custo são bastante influenciadas pelo Microsoft Azure Well-Architected Framework. Implante uma solução criada em torno dessa estrutura e você terá uma solução cujo custo e desempenho são previsíveis.

Desempenho

A previsibilidade de desempenho se concentra em prever os recursos necessários para oferecer uma experiência positiva aos clientes. O dimensionamento automático, o balanceamento de carga e a alta disponibilidade são apenas alguns dos conceitos de nuvem que dão suporte à previsibilidade de desempenho. Se de repente você precisar de mais recursos, o dimensionamento automático poderá implantar recursos adicionais para atender à demanda e depois reduzir a implantação quando a demanda cair. Ou se o tráfego estiver bem concentrado em uma área, o balanceamento de carga ajudará a redirecionar parte da sobrecarga para áreas menos sobrecarregadas.

Custo

A previsibilidade de custos se concentra em prever o custo dos gastos com a nuvem. Com a nuvem, você pode acompanhar o uso de recursos em tempo real, monitorar os recursos para garantir a maior eficiência de uso possível e aplicar a análise de dados para encontrar padrões e tendências que ajudam a planejar melhor as implantações de recursos. Operando na nuvem e usando a análise e as informações da nuvem, você pode prever custos futuros e ajustar os recursos conforme o necessário. Você pode até mesmo usar ferramentas como TCO (custo total de propriedade) ou a Calculadora de Preços para obter uma estimativa de possíveis gastos com a nuvem.

Os benefícios da segurança e da governança na nuvem 

Se você estiver implantando infraestrutura como serviço ou software como serviço, os recursos de nuvem vão dar suporte à governança e à conformidade. Itens como modelos de conjunto ajudam a garantir que todos os seus recursos implantados atendam aos padrões corporativos e aos requisitos regulatórios governamentais. Além disso, você pode atualizar todos os seus recursos implantados com novos padrões à medida que os padrões são alterados. A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação. Dependendo do seu modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e na segurança.
Em relação à segurança, você pode encontrar uma solução de nuvem que atenda às suas necessidades de segurança. Se você quiser o controle máximo da segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção. Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você.
E como a nuvem se destina a uma entrega de recursos de TI via Internet, os provedores de nuvem normalmente são adequados para lidar com situações como ataques de DDoS (negação de serviço distribuído), tornando sua rede mais robusta e segura.
Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.

Os benefícios da capacidade de gerenciamento na nuvem:

Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento

Gerenciamento da nuvem - 

O gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem. Na nuvem, você pode:
	• Escalar automaticamente a implantação de recursos com base na necessidade.
	• Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
	• Monitorar a integridade dos recursos e substituir automaticamente os recursos com falha.
	• Receber alertas automáticos com base em métricas configuradas, de modo a ficar ciente do desempenho em tempo real.

Gerenciamento na nuvem - 

O gerenciamento na nuvem diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos. Você pode gerenciá-los:
	• Por meio de um portal da Web.
	• Usando uma interface de linha de comando.
	• Usando APIs.
	• Usando o PowerShell.

Os tipos de serviço de nuvem:

A infraestrutura como serviço (IaaS): 

O IaaS (infraestrutura como serviço) é a categoria mais flexível de serviços de nuvem, pois oferece o máximo de controle sobre os recursos de nuvem. Em um modelo de IaaS, o provedor de nuvem é responsável por manter o hardware, a conectividade de rede (com a Internet) e a segurança física. Você é responsável por todo o resto: instalação, configuração e manutenção do sistema operacional; configuração de rede; configuração de banco de dados e armazenamento e assim por diante. Com o IaaS, basicamente o hardware é alugado em um datacenter de nuvem, mas cabe a você decidir o que fazer com ele.

O modelo de responsabilidade compartilhada se aplica a todos os tipos de serviço de nuvem. No IaaS, a maior parte da responsabilidade fica com você. O provedor de nuvem é responsável por manter a infraestrutura física e o acesso à Internet. Você é responsável por: instalação e configuração, aplicação de patch, atualizações e segurança.

Alguns cenários comuns em que o IaaS faz sentido incluem:
	• Migração lift-and-shift: Você está configurando recursos de nuvem semelhantes aos do datacenter local e apenas migra os elementos em execução local para execução na infraestrutura IaaS.
	• Teste e desenvolvimento: você estabeleceu configurações para ambientes de desenvolvimento e teste que precisa replicar rapidamente. Você pode inicializar ou desativar os diferentes ambientes rapidamente com uma estrutura de IaaS, mantendo o controle completo.


Plataforma como serviço (PaaS): é um meio termo entre alugar espaço em um datacenter (infraestrutura como serviço) e pagar uma solução completa e implantada (software como serviço). Em um ambiente de PaaS, o provedor de nuvem mantém a infraestrutura física, a segurança física e a conexão com a Internet. Ele também mantém os sistemas operacionais, o middleware, as ferramentas de desenvolvimento e os serviços de business intelligence que compõem uma solução de nuvem. Em um cenário de PaaS, você não precisa se preocupar com o licenciamento nem com a aplicação de patch em sistemas operacionais e bancos de dados.

O PaaS é adequado para fornecer um ambiente de desenvolvimento completo sem a preocupação de manter toda a infraestrutura de desenvolvimento.

O modelo de responsabilidade compartilhada se aplica a todos os tipos de serviço de nuvem. O PaaS divide a responsabilidade entre você e o provedor de nuvem. O provedor de nuvem é responsável por manter a infraestrutura física e o acesso à Internet, como no IaaS. No modelo de PaaS, o provedor de nuvem também mantém os sistemas operacionais, os bancos de dados e as ferramentas de desenvolvimento. Pense no PaaS como o uso de um computador conectado ao domínio: o departamento de TI mantém o dispositivo com atualizações, patches e renovações regulares.

Dependendo da configuração, você ou o provedor de nuvem pode ser responsável pelas configurações de rede e a conectividade no ambiente de nuvem, a segurança da rede e do aplicativo e a infraestrutura de diretório.

Alguns cenários comuns em que o PaaS faz sentido incluem:
	• Estrutura de desenvolvimento: O PaaS fornece uma estrutura que os desenvolvedores podem usar como base para desenvolver ou personalizar aplicativos baseados em nuvem. Semelhante à forma como você cria uma macro do Excel, o PaaS permite aos desenvolvedores criar aplicativos usando componentes de software internos. São incluídos recursos de nuvem, como escalabilidade, alta disponibilidade e a funcionalidade de multilocatário, reduzindo a quantidade de codificação que os desenvolvedores precisam realizar.
	• Análise ou business intelligence: as ferramentas fornecidas como serviço com o PaaS permitem que as organizações analisem e minerem dados, encontrando insights e padrões e prevendo resultados para aprimorar a previsão, as decisões de design de produto, o retornos sobre investimentos e outras decisões de negócios.
	

Software como serviço (SaaS):  

O SaaS (software como serviço) é o modelo de serviço de nuvem mais completo do ponto de vista do produto. Com o SaaS, você está essencialmente alugando ou usando um aplicativo totalmente desenvolvido. Email, software financeiro, aplicativos de mensagens e software de conectividade são exemplos comuns de uma implementação de SaaS.
Embora o modelo de SaaS possa ser o menos flexível, ele também é o mais fácil de colocar em funcionamento. Ele requer a menor quantidade de conhecimento técnico ou experiência para o emprego total.

O modelo de responsabilidade compartilhada se aplica a todos os tipos de serviço de nuvem. O SaaS é o modelo que coloca a maior responsabilidade sobre o provedor de nuvem e a menor responsabilidade com o usuário. Em um ambiente de SaaS, você é responsável pelos dados que coloca no sistema, pelos dispositivos que permite que se conectem ao sistema e pelos usuários que têm acesso. Quase todo o resto é responsabilidade do provedor de nuvem. O provedor de nuvem é responsável pela segurança física dos datacenters, pela energia, pela conectividade de rede e pelo desenvolvimento e aplicação de patch dos aplicativos.

Alguns cenários comuns de SaaS são:
	• Email e mensagens.
	• Aplicativos de produtividade empresarial.
	• Controle de finanças e despesas.

 -------
DIO - Formação Microsoft AZ-900 Certification
 -------

 	- Conceitos do Azure
	- Principais serviços do Azure
	- Principais soluções e ferramentas de gerenciamento segurança geral e segurança de rede
	- Governança, privacidade e recursos de conformidade e gerenciamento de custo do Azure
 
Computação em nuvem

	- O que é computação em nuvem:  A computação em nuvem é o fornecimento de serviços de computação pela internet, habilitando inovações mais rápidas, recursos flexíveis e economias de escala. 
	
				

	- Modelos de nuvem (incluindo público, privado e híbrido)
	
	Nuvem privada:  As organizações criam um ambiente em nuvem em seu datacenter.
	As organizações são responsáveis por operar os serviços que fornecem.
	Não fornece acesso aos usuários fora da organização.
	
	
	Nuvem pública: Pertencente a serviços de nuvem ou provedor de hosting.
	Fornece recursos e serviços a várias organizações e usuários.
	Acessada via conexão de rede segura (geralmente pela Internet).
	
	
	Nuvem híbrida: Combina nuvens públicas e privadas para permitir que os aplicativos sejam executados no local mais adequado.
	
	
	- Comparação entre Custo de capital (CapEx) versus custo operacional (OpEx):
	
	Despesas de capital (CapEx): 
	O gasto inicial de dinheiro em infraestrutura física.
	As despesas do CapEx têm um valor que se reduz com o tempo.
	
	Despesas operacionais (OpEx): 
	Gastar com produtos e serviços conforme necessário, pagamento conforme o uso.
	Seja cobrado imediatamente.

	- Descrever o modelo baseado no consumo:
	Os provedores de serviços em nuvem operam em um modelo baseado em consumo, o que significa que os usuários finais pagam somente pelos recursos que usam.
	Melhor previsão de custos.
	São fornecidos preços para recursos e serviços individuais.
	A cobrança é feita com base no seu uso real.
	
	- Comparar os modelos de preços de nuvem:
	Nuvem pública: 
	Nenhuma despesa de capital (CapEx) para escalar verticalmente. 
	Os aplicativos podem ser provisionados e desprovisionados rapidamente.
	As organizações pagam apenas pelo que utilizam.
	
	Nuvem privada: 
	As organizações têm controle total sobre os recursos e a segurança.
	As organizações são responsáveis pela manutenção e pelas atualizações de hardware e software.
	
	Nuvem híbrida: 
	As organizações determinam onde executar seus aplicativos.
	As organizações controlam a segurança, a conformidade e os requisitos legais.
	Fornece a maior flexibilidade.
	
