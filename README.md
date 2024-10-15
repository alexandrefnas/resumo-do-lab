# Resumo:

- O portal do Microsoft Azure é padrão para todos os tipos de clientes, seja 
CPF ou PJ.
A única diferença é que as vezes não teremos todos os recursos disponível dependendo da região.

- No portal é possível trocar o idioma, a cor de Layout, tipo da aparéncia, etc...

- Em "Todos os Serviços" voce tem acesso ao servíços por categorias.

- Alguns servíços, aparece uma descrição "Versão prévia", é quando o servíço está começando a ser disponibilizado e em processo de teste. Normalmente esse tipo de produto não tem garantias.

## Benefícos da nuvem

- Alta disponibilidade: 
A alta disponibilidade se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer.
O Azure é um ambiente de nuvem altamente disponível com garantias de tempo de atividade, dependendo do serviço. 
Essas garantias fazem parte dos SLAs  (Contratos 
de Nível de Serviço).


- Escalabilidade: 
A escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda. 
A capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.
O outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços. 
Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa. 
Se a demanda cair, você poderá reduzir seus recursos e, assim, reduzir seus custos.
Com a escala vertical, se você estivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual. 

- Elasticidade:
Com a elasticidade, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente).
Por exemplo, você pode adicionar máquinas virtuais ou contêineres por meio da expansão. 
Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente (de maneira automática ou manual).

- Confiabilidade:
Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente. 
Com um design descentralizado, a nuvem permite que você tenha recursos implantados em várias regiões do mundo.
Com essa escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento. 

- Previsibilidade:
A previsibilidade na nuvem permite que você avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo Microsoft Azure Well-Architected Framework. 

- Segurança:
A nuvem oferece ferramentas de segurança que atendem às necessidades dos clientes mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente. 
Se você quiser o controle máximo da segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção. 
Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você.

- Governança:
Dependendo do seu modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e na segurança.
Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.

- Gerenciabilidade:
Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Há dois tipos de capacidade de gerenciamento para computação em nuvem que você aprenderá nesta série e ambos trazem excelentes benefícios.
  - O gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem. Por exemplo:
    - Escalar automaticamente a implantação de recursos com base na necessidade.
    - Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.    
  - O gerenciamento na nuvem diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos. Por exemplo:
    - Por meio de um portal da Web.
    - Usando uma interface de linha de comando.
    - Usando APIs.
    - Usando o PowerShell.
    
