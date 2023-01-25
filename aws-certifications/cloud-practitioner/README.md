# AWS Cloud Practitioner

## Link do curso

https://www.udemy.com/course/aws-certified-cloud-practitioner-new

## Índice
<!-- TODO:  -->

## O que compõem um servidor (slide 13)

- CPU;
- Memória RAM;
  - CPU + Memória RAM = cérebro
- Guardar dados
- Banco de dados
- Network: Roteadores, switch, DNS

![Alt text](../../assets/it-terminology.png "Title")

## Problemas com o padrão tradicional de servidores

- Gerenciar um datacenter físico;
- Pagar aluguel, luz e todas as despesas para manter um local físico;
- Escalar a infra é limitada;
- Contratar equipe 24/7 para monitorar;
- Desastres naturais.

## O que é computação na nuvem?

- Serviços computacionais disponíveis "On-demand";
- Paga apenas o que usar/consumir;
- Permite provisionar exatamente o tamanho e tipo de recursos que precisar;
- Acesso a quantos recursos quiser;
- "Forma simples" de acessar banco de dados, servidores e outras aplicações de infra.

## Modelos de "deployment" da nuvem

- Private cloud:
  - Usado por uma única companhia, não exposta ao público;
  - Segurança para aplicações sensíveis;
  - Regras de negócio bem específicas para a companhia em questão.

- Public cloud:
  - Recursos de nuvem mantidos por uma empresa terceira, disponibilizados na internet;
  - Ex.: AWS, Google Cloud

- Hybrid cloud:
  - Mantém alguns servidores "on premises" e extende a capacidade para a nuvem também;
  - Flexibilidade e custo da nuvem pública.

## As 5 características da computação na nuvem

- Serviços "on-demand":
  - Os clientes podem usar qualquer serviço sem depender de interação humana.

- Recursos disponíveis em qualquer parte do mundo:

- Recursos e aplicações compartilhadas
  - Múltiplos clientes compartilham a mesma infraestrutura e aplicações com segurança e privacidade;
  - Múltiplos clientes são servidos com a mesma infraestrutura física.

- Rápida elasticidade e escalabilidade:
  - Recursos podem ser adquiridos quando preciso;
  - Possibilidade de escalar os serviços quando preciso ("on-demand").

- Paga o que usar.

## 6 vantagens da computação na nuvem

- Troca de "capital expense (CAPEX)" por "operational expense (OPEX)"
  - Paga o que usa, não é dono do hardware;
  - Custos de "Total cost of ownership (TCO)" e "operational expense (OPEX)" são reduzidos.

- Benefício econômico de serviços em grande escala:
  - Preços são menores pois a AWS é mais eficiente devido a larga escala.

- Não há necessidade de adivinhar a capacidade:
  - Serviços são escalados conforme uso.

- Agilidade e velocidade aumentados

- Não há necessidade de manter datacenter físico

- Disponibilidade global em poucos minutos

## Problemas resolvidos pela nuvem

- Flexibilidade: 
  - Permite alterar tipos de recursos conforme necessidade.

- Custo "justo":
  - Paga o que consumir.

- Escalabilidade

- Elasticidade:
  - Habilidade de escalar para qualquer "lado" quando preciso.

- Alta disponibilidade dos serviços

- Agilidade:
  - Possibilita desenvolver, testar e lançar aplicações rapidamente.

## Tipos de computação na nuvem

- Infrastructure as a Service (IaaS):
  <!-- TODO: explicar melhor -->
  - Ex: EC2, Azure, Digital Ocean

- Platform as a Service (PaaS):
  - Remove a necessidade de lidar com infra de baixo nível;
  - Foco no deploy e gerenciamento da aplicação;
  - Lida com dados e aplicação.
  - Ex: Elastic beanstalk, Heroku, Windows Azure

- Software as a Service (SaaS):
  - Produto completamente gerenciado pelo provedor do serviço.
  - GMail, Dropbox, Zoom

![Alt text](../../assets/tipos-computacao.png "Title")

## Precificação

A precificação da AWS possui 3 fundamentos:

- Processamento:
  - Paga por tempo de processamento.

- Armazenamento:
  - Paga por quantidade de dados armazenados na nuvem.

- Dados transferidos para FORA da nuvem:
  - Dados transferidos dentro, são grátis.

## Regiões da AWS

- Uma região possui um "cluster" de data centers no mundo todo;
- Alguns serviços da AWS só estão disponíveis em regiões específicas;

## Como escolher a região certa?

- Compliance:
  - Questões e regras legais do governo de cada região.

- Proximidade:
  - Proximidade dos usuários, reduz a latência.

- Disponibilidade de serviços:
  - Algumas regiões não possuem todos os serviços.

- Precificação:
  - Preço dos serviços pode variar entre as regiões.

## Availability Zones (AZ)

- Cada região possui algumas AZ. Mínimo 3, máximo 4;

- Cada AZ possui um ou mais data center físico;

- Cada AZ é separada uma da outra, para evitar desastres;

- Elas são conectadas umas com as outras e possuem latência muito baixa

![Alt text](../../assets/AZ.png "Title")

## Pontos de presença (Edge locations)

![Alt text](../../assets/edge-locations.png "Title")

## Diagrama do modelo de responsabilidade compartilhada

- Informação completa no site:
  - https://aws.amazon.com/compliance/shared-responsibility-model/

## Política de uso

- Proibido:
  - Uso de conteúdo ofensivo e ilegal;
  - Violações de segurança;
  - Abuso na rede;
  - Abuso no envio de emails e outras mensagens.
