# Azure
Criando maquinas virtuais na Azure

Benefícios da nuvem
O uso da computação em nuvem traz diversos benefícios, como alta disponibilidade, que garante acesso contínuo aos serviços com suporte de SLAs que asseguram compensações em caso de falhas. A escalabilidade permite ajustar os recursos conforme a demanda, evitando gastos desnecessários. A elasticidade oferece flexibilidade para lidar com picos de uso, como em eventos imprevisíveis. A confiabilidade é garantida por um design descentralizado que mantém os serviços mesmo diante de falhas regionais. A previsibilidade assegura controle sobre desempenho e custos. A segurança é compartilhada entre o provedor e o cliente, com ferramentas adaptáveis ao nível de controle desejado. A governança permite auditorias e correções automáticas para manter a conformidade. Por fim, a gerenciabilidade facilita o controle dos recursos por meio de portais, APIs e automações, tornando o gerenciamento mais eficiente e flexível.
Domínio de Objetivo 
Esses são os tópicos usados em aula e alguns pontos importante que anotei:
•	Descrever os benefícios da alta disponibilidade e da escalabilidade na nuvem.
•	Descrever os benefícios da confiabilidade e da previsibilidade na nuvem.
•	Descrever os benefícios da segurança e da governança na nuvem.
•	Descrever os benefícios da capacidade de gerenciamento na nuvem.
•	Alta disponibilidade: è um sistema que você consegue acessar de qualquer lugar, qualquer horário, podem ser usados sempre que necessário, que também esta ligado ao SLA , que é a garantia do serviço.
•	Se a Azure não atender a porcentagem que esta no contrato , eu serei ressarcido . 
•	Caso a Microsoft fique fora do ar ou deixe de atender o que foi contratado, o cliente recebe créditos na próxima fatura
•	A alta disponibilidade se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer
•	O Azure é um ambiente de nuvem altamente disponível com garantias de tempo de atividade, dependendo do serviço. 
•	Essas garantias fazem parte dos SLAs  (Contratos 
de Nível de Serviço).

Escalabilidade 

•	A escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda. 
•	A capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.
•	O outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços. 
•	Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa. 
•	Se a demanda cair, você poderá reduzir seus recursos e, assim, reduzir seus custos.

•	Com a escala vertical, se você estivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual. 
•	É  mudar acapacidade de determinado recurso para atender  a nova necessidade.

Elasticidade 

•	Um exemplo de comparação seira a  Black Friday, porque eu não sei o quanto eu preciiso crescer, não tem como saber quanto acessos serão requisistados ,só na hora para descobrir.
•	Com a elasticidade, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente).
•	Por exemplo, você pode adicionar máquinas virtuais ou contêineres por meio da expansão. 
•	Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente (de maneira automática ou manual).
•	Eu posso dimensionar o meu ambiente com base em requisições

Confiabilidade 
•	Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente. 
•	Com um design descentralizado, a nuvem permite que você tenha recursos implantados em várias regiões do mundo. 
•	Com essa escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento. 

Previsibilidade 
•	A previsibilidade na nuvem permite que você avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo Microsoft Azure Well-Architected Framework. 
Quando falamos de previsibilidade , estamos falando de confiança.
Um exemplo é as empresas mais antigas que funcionam a anos de determinado jeito, então a microsft tem que passar confiança para essa empresa aceitar o seu trabalho.

Segurança 

A nuvem oferece ferramentas de segurança que atendem às necessidades dos clientes mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente
•	Se você quiser o controle máximo da segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção. 
•	Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você.
A responsabilidade do provider é  oferecer recursos e serviços pra atender a minha demanda, a minha responsabilidade é aplica-los

Governança 
•	A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação. 
•	Dependendo do seu modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e na segurança.
•	Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.

Gerenciabilidade 

•	Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Há dois tipos de capacidade de gerenciamento para computação em nuvem que você aprenderá nesta série e ambos trazem excelentes benefícios.
O gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem. Por exemplo:
•	Escalar automaticamente a implantação de recursos com base na necessidade.
•	Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
O gerenciamento na nuvem diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos. Por exemplo:
•	Por meio de um portal da Web.
•	Usando uma interface de linha de comando.
•	Usando APIs.
•	Usando o PowerShell



