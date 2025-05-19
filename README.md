Lousa # Resumo do Lab Java Cloud Native

Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO Java Cloud Native.

## Computação em Nuvem

De forma simples: nossos recursos virtualizados são disponibilizados por grandes players como: Microsoft Azure, AWS, IBM Cloud e Oracle Cloud. Além de serviços que vão desde armazenamento até inteligência artificial e análise de dados.

## Modelos de Computação em Nuvem

### Nuvem Pública:

* Baseada em utilização de recursos disponibilizados por organizações terceiras.
* Pagamento apenas pelo uso.
* Sem despesas físicas.
* Os aplicativos podem ser provisionados e desprovisionados rapidamente.

### Nuvem Privada:

* As organizações têm total controle sobre a infraestrutura.
* Envolve despesas físicas e operacionais.
* A própria organização é responsável pela manutenção e configuração.

### Nuvem Híbrida:

* Combina o melhor dos dois mundos.
* As organizações determinam onde e por quanto tempo executar seus aplicativos.
* Permite estratégias de otimização de custos e melhoria da escalabilidade.
* Oferece controle sobre segurança, conformidade e requisitos legais.

## Comparação de CapEx e OpEx

### CapEx (Capital Expenditure):

* Gasto com estrutura física (ex: servidores, datacenters).
* Ativos que se desvalorizam com o tempo.

### OpEx (Operational Expenditure):

* Gasto com produtos e serviços sob demanda.
* Pagamento conforme o uso.
* Valor cobrado imediatamente e com maior previsibilidade.

## Modelo Baseado em Consumo

* Melhor previsão de custos.
* Preços definidos para recursos e serviços individuais.
* Cobrança baseada no uso real de recursos.

## Conceitos Importantes

### Escalabilidade

* Capacidade de aumentar (ou diminuir) recursos conforme a demanda.
* Pode ser **vertical** (aumentar a capacidade de um único recurso) ou **horizontal** (adicionar mais instâncias de recursos).

### Elasticidade

* Ajuste automático dos recursos de forma rápida e eficiente, conforme a variação da carga de trabalho.
* Essencial para lidar com picos de acesso de forma econômica.

### Gerenciabilidade

* Facilidade de monitorar, configurar e manter os recursos da nuvem.
* Muitas plataformas oferecem painéis de controle, APIs e ferramentas automatizadas para facilitar o gerenciamento.

### SLA (Service Level Agreement)

* Acordo formal entre fornecedor e cliente definindo o nível de serviço esperado.
* Define métricas como disponibilidade, tempo de resposta e suporte.
* Exemplo comum: 99,9% de uptime mensal.

### Alta Disponibilidade

* Garantia de que os serviços estarão disponíveis com o mínimo de interrupções.
* Atingida por meio de redundância, replicação e distribuição geográfica de servidores.

### Segurança na Nuvem

* Inclui medidas como criptografia, autenticação multifator, firewalls e compliance com normas (como LGPD, GDPR, ISO).
* Na nuvem pública, é comum adotar o modelo de **responsabilidade compartilhada**: o provedor cuida da infraestrutura e o cliente dos dados e acessos.

## Tipos de Serviços em Nuvem

### IaaS (Infrastructure as a Service)

* Fornecimento de infraestrutura básica como servidores, redes, máquinas virtuais e armazenamento.
* O usuário gerencia o sistema operacional, os aplicativos e os dados.
* Exemplo: Amazon EC2, Google Compute Engine, Microsoft Azure VMs.

### PaaS (Platform as a Service)

* Oferece uma plataforma com ferramentas e serviços para desenvolvimento, teste e implantação de aplicações.
* O usuário gerencia apenas as aplicações, enquanto o provedor gerencia a infraestrutura e a plataforma.
* Exemplo: Google App Engine, Heroku, Azure App Services.

### SaaS (Software as a Service)

* Aplicações prontas para uso final entregues pela internet.
* O usuário não se preocupa com infraestrutura ou manutenção.
* Exemplo: Gmail, Google Docs, Microsoft 365, Salesforce.

## Computação e Rede

* A computação em nuvem depende fortemente de uma infraestrutura de rede confiável e escalável.
* Os recursos são acessados por meio da internet ou redes privadas, exigindo baixa latência e alta largura de banda.
* A segmentação de rede, firewalls e VPNs são essenciais para garantir a segurança e o isolamento dos dados.
* Conceitos como **Content Delivery Network (CDN)** são usados para distribuir conteúdo globalmente com rapidez e eficiência.
* Protocolos como HTTP, HTTPS, TCP/IP e DNS são fundamentais para a comunicação entre os serviços na nuvem.
* O balanceamento de carga distribui o tráfego entre múltiplos servidores para garantir disponibilidade e desempenho.

---

Essas anotações cobrem os principais conceitos de computação em nuvem aprendidos no laboratório da DIO. Podem ser atualizadas conforme o conteúdo do curso evoluir.
