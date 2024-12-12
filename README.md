## Introdução a Computação em Nuvem

- Modelos de Nuvem
    - É fornecimento de serviços de computação pela internet
    - Virtualização dos data centers por grandes empresas
    - Computação, Rede, Armazenamento
    - Pagar somente pelo que usa
    
    ### Nuvem privada
    
    - Organizações criam um ambiente em nuvem em seu datacenter
    - Organizações são responsáveis por operar os serviços que fornecem
    - Organizações tem o controle total
    - São responsáveis pela manutenção e atualização de hardware e software
    - Pessoas de fora da organização não tem acesso
        
    
    ### Nuvem publica
    
    - Vários usuários ou organizações que uma empresa (no caso Microsoft)
    - Acessada via conexão de rede segura
    - Organizações pagam apenas pelo que usam
    - Pode excluir e alterar sem grandes cobranças
        - Geralmente internet
        
    
    ### Nuvem híbrida
    
    - Combina nuvens para permitir que o aplicativo seja executado no local mais adequado
    - Ambas as nuvens (publica e privadas)
    - Organizações determinam onde executar os aplicativos
    - As organizações controlam a segurança, conformidade e requisitos legais.
    - Fornece maior flexibilidade
        
    
    ### MultiCloud
    
    - O uso de nuvens de diferentes empresas como microsoft e outras.
- CapEx e OpEx
    
    ### Despesas de Capital (CapEx)
    
    - Gasto inicial em dinheiro em infraestrutura física.
    - As despesas CapEx têm um valor que reduz ao decorrer do tempo
    
    ### Despesas Operacionais (OpEx)
    
    - Gastar com produtos e serviços conforme o necessário, pagamento conforme o uso
    - Tudo que for ativo, você está sujeito a pagar
    - Seja cobrado imediatamente (menos comum)
    
    ### Modelo Baseado em Consumo
    
    - Cobrança é feita com base no seu uso real.
    - Modelo da nuvem
 
      
## Benefícios da Computação em Nuvem

- Alta disponibilidade
    - Recursos disponíveis sempre que necessário
    - Contrato da Azure, onde a Microsoft garante um certo período de tolerância de indisponibilidade
        - SLA → Nome do contrato
        - 99% - 99.95%
        - Você ganha um voucher de crédito
- Escalabilidade e Elasticidade
    
    ### Escalabilidade
    
    - Refere-se à capacidade  de ajustar recursos para atender à demanda.
    - Para cima, escalada vertical
        - Adicionar mais CPUs, RAM…
    - Nuvem é baseada em consumo
    
    ### Elasticidade
    
    - Salto repentino acentuado na demanda
    - Dimensionar com base em requisições
    - Aumentam horizontalmente e reduzem horizontalmente
    - Nomalmente feito de forma automática.
- Confiabilidade, Previsibilidade e Segurança
    
    ### Confiabilidade
    
    - Modelo da nuvem é descentralizado
    - Permite que os recursos sejam implantados em várias regiões do mundo.
    - Escala global
    
    ### Previsibilidade
    
    - Confiança, seja no desempenho ou no custo
    
    ### Segurança
    
    - Ferramentas de segurança
    - Muitas implementações de segurança devem ser realizadas pelo cliente
    - Responsabilidade do provedor é oferecer recursos, já o seu é aplicar esses recursos.
- Governança e Gerenciabilidade
    
    ### Governança
    
    - Como gerir os recursos
    - Conformidades e padronizações
    - Auditoria
    - Padrões de gestão
      
  ### Gerenciabilidade
    
    - Gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem. Por exemplo:
    - Escalar automaticamente a implantação de recursos com base na necessidade

## Tipos de Serviço de Nuvem

- IaaS, PaaS e SaaS
    
    ### IaaS
    
    - Infraestrutura como Serviço
        
    - Clientes tem mais acesso
        - Precisa configura e personalizar o recurso
    - Serviço de nuvem mais flexível
    
    ### PaaS
    
    - Plataforma como Serviço
        
    - Fornece um ambiente para criação, teste e implantação, sem focar no gerenciamento da infraestrutura subjacente
    - Focado no desenvolvimento de aplicativos
    
    ### SaaS
    
    - Software como Serviço
        
    - Teams
    - Conforme o modelo de licença, o acesso do usuário é personalizável
    - Usuário paga pelo software que usam, em modelo de assinatura (licenciamento)
- Modelo de responsabilidade Compartilhada
    
    - No local → Toda a responsabilidade é do cliente
    - IaaS → Hosts físicos, Rede Física e Datacenter físico são responsabilidade da Microsoft
    - PaaS → As acima, e o SO são responsabilidade da Microsoft, já Controles de rede, Aplicativo e infra estrutura de identidade e diretório são compartilhadas
    - SaaS As acima, e Contole de Rede, Aplicativos são responsabilidade da microsoft, a infraestrurura de identidade e diretório são compartilhadas
