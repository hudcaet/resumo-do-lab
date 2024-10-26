# resumo-do-lab
 "Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO - Criando Máquinas Virtuais an Azure".

A criação de Máquinas Virtuais (VMs) no Azure é um processo essencial para configurar ambientes computacionais flexíveis, escaláveis e adaptáveis às necessidades de aplicativos. As VMs permitem que você hospede aplicações, execute cargas de trabalho e personalize as configurações do sistema operacional e de hardware.

Principais Etapas para Criar uma VM no Azure:

Escolha da Imagem e Sistema Operacional: Ao iniciar uma VM, você escolhe uma imagem do sistema operacional (Windows, Linux, etc.) do Azure Marketplace ou pode até usar uma imagem personalizada. Cada imagem vem com um conjunto de ferramentas e funcionalidades para as cargas de trabalho específicas.

Seleção de Tamanho da VM: O Azure oferece tamanhos variados para VMs que se ajustam às demandas de CPU, memória e armazenamento. Isso permite que você selecione uma configuração que corresponda ao desempenho desejado e ao orçamento disponível.

Configurações de Rede e Segurança: Cada VM é implantada dentro de uma Rede Virtual (VNet), e você pode aplicar regras de segurança com Grupos de Segurança de Rede (NSGs), definindo acessos, como SSH para Linux ou RDP para Windows, conforme necessário.

Armazenamento de Dados: A VM pode conter discos SSD ou HDD, incluindo discos para o sistema operacional e volumes adicionais para armazenamento persistente.

Configurações Avançadas e Implantação: Incluem configurações de backup, monitoramento e soluções de automação. Após revisar e configurar esses detalhes, a VM é implantada, estando pronta para ser gerenciada através do portal, CLI, ou APIs.

SLA (Acordo de Nível de Serviço) para VMs do Azure:

O SLA define a garantia de disponibilidade oferecida pela Microsoft para serviços específicos no Azure. Para VMs, o Azure oferece 99,9% de disponibilidade em uma única instância de VM, desde que ela seja implantada em discos gerenciados. Em cenários de alta disponibilidade, onde VMs são implantadas em conjuntos de disponibilidade ou zonas de disponibilidade, o SLA aumenta, chegando a 99,95% ou até 99,99%, dependendo da configuração.

Esses níveis de SLA refletem a robustez do serviço e a infraestrutura de recuperação de falhas do Azure, garantindo que seus aplicativos possam se recuperar de falhas de hardware e de rede e manter alta disponibilidade.
