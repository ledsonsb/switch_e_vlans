A diferença entre VLAN (Virtual Local Area Network) de Layer 2 e Layer 3 está relacionada às funcionalidades que cada uma oferece dentro do modelo OSI (Open Systems Interconnection), especificamente nas camadas 2 e 3.

VLAN Layer 2 (Camada de Enlace)
Uma VLAN de Layer 2 opera na camada de enlace de dados (Data Link Layer) do modelo OSI. Nesta camada, a VLAN é responsável pela segmentação da rede de acordo com os endereços MAC (Media Access Control). A VLAN de Layer 2 divide a rede em diferentes domínios de broadcast, ou seja, as transmissões de broadcast são limitadas ao grupo de dispositivos dentro de uma mesma VLAN.

Características:

As VLANs são configuradas em switches Layer 2.
Os pacotes de dados são encaminhados com base nos endereços MAC.
Dispositivos dentro da mesma VLAN, independentemente de sua localização física, estão no mesmo domínio de broadcast.
Switches Layer 2 não fazem roteamento entre VLANs. Para comunicação entre VLANs diferentes, é necessário um roteador ou um switch de camada 3 (Layer 3 switch).
A comunicação entre dispositivos na mesma VLAN não exige o uso de roteamento.
Exemplo de uso:

Segmentação de redes em diferentes departamentos de uma empresa (por exemplo, VLAN para o departamento financeiro e outra para o departamento de TI) para isolar o tráfego de broadcast e aumentar a segurança.
VLAN Layer 3 (Camada de Rede)
Uma VLAN de Layer 3 opera na camada de rede (Network Layer) do modelo OSI. Neste caso, além de segmentar o tráfego como uma VLAN de Layer 2, a VLAN de Layer 3 pode realizar roteamento entre diferentes VLANs. Isso é possível porque os switches Layer 3 possuem funcionalidades de roteamento, permitindo que pacotes sejam encaminhados com base nos endereços IP.

Características:

As VLANs são configuradas em switches Layer 3 (ou roteadores).
Os pacotes de dados são encaminhados com base nos endereços IP (não apenas MAC).
A comunicação entre VLANs diferentes é possível sem a necessidade de um roteador externo, pois os switches Layer 3 podem realizar o roteamento interno entre as VLANs.
Switches de Layer 3 combinam a função de switches Layer 2 (segmentação em VLANs) e de roteadores (encaminhamento entre redes).
