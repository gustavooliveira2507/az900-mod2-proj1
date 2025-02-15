# az900-mod2-proj1
Projeto de componentes e arquitetura do Azure.
O Azure é dividido em regiões que estão espalhadas entre o globo.
Cada região possui suas zonas de disponibilidades que em sua maioria são 3 e as mesmas se comunicação entre si com objetivo de manter a disponibilidade dos serviços e dados, com a minima latencia.
Existem duas regiões soberanas que não são acessiveis aos usuários comuns do AZURE são elas, a do governo dos EUA e a zona da China, no caso da China existe uma operadora intermediaria chamada 21VIANET para garantir que os dados não saiam do pais.
Para organizar o Azure temos alguns recursos que facilitam são eles:
* Grupo de recursos - Agregamos um ou mais recusos de multiplas regiões;
* Assinaturas - É utilizada quando queremos separar financeiramente nossos recursos, onde uma conta pode ter N Assinaturas porem uma assinatura só pertence a uma conta;
* Grupos de gerenciamentos - Gerencia suas assinaturas muito utilizado quando queremos criar politicas ou controles de acessos globais a diferentes assinaturas e grupo de recursos;  
