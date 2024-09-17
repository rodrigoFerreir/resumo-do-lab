# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab "Criando máquinas Virtuais na Azure" na DIO 🚀

Aula sobre SLAs: Garantindo a Disponibilidade dos Seus Serviços na Azure
O que é um SLA e por que ele é importante?
SLA, ou Service Level Agreement, é um contrato formal entre um provedor de serviços (como a Microsoft Azure) e um cliente, que define os níveis de serviço que o cliente pode esperar. No contexto da Azure, um SLA especifica a disponibilidade, desempenho e outras métricas de qualidade para os serviços da nuvem.

Por que os SLAs são importantes?

Planejamento: Permitem que você planeje suas aplicações e serviços com base em garantias de desempenho.
Tomada de decisão: Ajudam a tomar decisões sobre quais serviços escolher, considerando suas necessidades específicas.
Proteção: Oferecem uma camada extra de proteção em caso de problemas, pois definem as responsabilidades de cada parte.
Criando uma Máquina Virtual na Azure
A criação de uma máquina virtual (VM) na Azure é um processo relativamente simples e pode ser feito através do portal do Azure, da Azure CLI ou do Azure PowerShell.

Passo a passo básico (via portal do Azure):

Acessar o portal: Acesse o portal do Azure (https://portal.azure.com/) e faça login com sua conta.
Criar um recurso: Clique em "Criar um recurso" e pesquise por "Máquina Virtual".
Selecionar uma imagem: Escolha a imagem do sistema operacional desejado (Windows ou Linux).
Configurar a VM: Defina o nome da VM, o tipo de instância, a região, o grupo de recursos e outras configurações como tamanho de disco, rede e segurança.
Revisar e criar: Revise as configurações e clique em "Criar".
Identificando as Zonas de Disponibilidade na Azure
As zonas de disponibilidade são localizações físicas distintas dentro de uma região do Azure, projetadas para isolar seus aplicativos e dados de falhas em um único local físico.

Como identificar as zonas de disponibilidade:

Ao criar um recurso: Ao criar uma VM ou outro recurso, você terá a opção de selecionar uma zona de disponibilidade específica.
Na página de propriedades do recurso: Após criar um recurso, você pode acessar a página de propriedades e verificar em qual zona de disponibilidade ele está localizado.
Utilizando a Azure CLI ou PowerShell: Você pode utilizar comandos específicos para listar as zonas de disponibilidade disponíveis em uma determinada região.
Por que as zonas de disponibilidade são importantes?

Alta disponibilidade: Ao distribuir seus recursos entre diferentes zonas, você aumenta a resiliência da sua aplicação, pois uma falha em uma zona não afetará as outras.
Recuperação de desastres: As zonas de disponibilidade podem ser utilizadas para implementar estratégias de recuperação de desastres, garantindo que seus dados estejam seguros em caso de falhas generalizadas.
Observação: As opções e configurações específicas podem variar dependendo da sua assinatura do Azure e das regiões disponíveis.

Para aprofundar seus conhecimentos:

Documentação da Microsoft: A documentação oficial da Microsoft oferece tutoriais detalhados e exemplos práticos sobre a criação e gerenciamento de máquinas virtuais na Azure.
Cursos online: Plataformas como a Microsoft Learn e o Coursera oferecem cursos completos sobre os serviços da Azure, incluindo SLAs e zonas de disponibilidade.
