# resumo-lab7

Entendendo os Serviços de Armazenamento no Microsoft Azure
O Microsoft Azure oferece uma variedade de serviços de armazenamento para atender diferentes necessidades de gerenciamento de dados. Neste guia, exploraremos os principais componentes do armazenamento no Azure, incluindo tipos de contas, redundância, e os serviços de arquivos, blobs e discos.

1. Contas de Armazenamento:
As contas de armazenamento no Azure são fundamentais para acessar os serviços de armazenamento oferecidos. Existem algumas regras importantes a serem observadas ao criar uma conta de armazenamento:

Nome Exclusivo Globalmente:

O nome da conta de armazenamento deve ser globalmente exclusivo, ou seja, não pode haver outra conta com o mesmo nome em todo o Azure.
Isso garante que os usuários possam acessar suas contas sem confusões.
Variedade de Serviços:

Uma conta de armazenamento pode oferecer diferentes tipos de serviços, como blobs, filas, arquivos e discos.
2. Tipos de Armazenamento:
No Azure, existem vários tipos de armazenamento que atendem a diferentes propósitos:

Arquivos do Azure:

Este serviço permite criar compartilhamentos de arquivos que podem ser acessados usando o protocolo SMB (Server Message Block).
Isso significa que você pode mapear esses arquivos em estações de trabalho e servidores, facilitando a colaboração e o compartilhamento de dados em uma rede.
Blobs:

O serviço de blobs é ideal para armazenar grandes quantidades de dados não estruturados, como imagens, vídeos e documentos. 
Os blobs são acessíveis via HTTP/HTTPS e são otimizados para cenários de armazenamento em nuvem.
Filas:

As filas do Azure são usadas para armazenar mensagens que podem ser acessadas de forma assíncrona.
Elas são úteis para desacoplar aplicações e garantir que as mensagens sejam processadas em ordem, mesmo se a aplicação que envia as mensagens estiver temporariamente indisponível.
Discos do Azure:

Os discos do Azure são utilizados para fornecer armazenamento para máquinas virtuais.
Eles podem ser configurados para serem gerenciados ou não gerenciados e são essenciais para o desempenho e a durabilidade das VMs.
3. Redundância e Durabilidade:
A durabilidade dos dados armazenados no Azure é uma preocupação essencial, e o Azure oferece várias opções de redundância:

LRS (Locally Redundant Storage):
O LRS oferece uma durabilidade de 11 noves (99,999999999%).
Isso significa que os dados são replicados dentro de um único datacenter, protegendo-os contra falhas de hardware. É uma opção econômica para garantir a segurança dos dados.
4. Conclusão:
O Microsoft Azure proporciona uma gama de serviços de armazenamento que atendem a diferentes necessidades de negócios. Desde o armazenamento de arquivos acessíveis em rede até a gestão de grandes volumes de dados não estruturados, cada serviço tem suas características e vantagens. Ao entender essas opções, você pode escolher a solução de armazenamento mais adequada para suas aplicações, garantindo a segurança e a acessibilidade dos dados.

Dica: Ao trabalhar com contas de armazenamento, sempre considere a exclusividade do nome, a durabilidade e a redundância necessária para o seu cenário específico. 
Isso ajudará a otimizar a gestão de dados e a garantir a integridade das informações armazenadas.

