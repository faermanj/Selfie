---
layout: clean
---

# AWS Summit San Francisco 2015 Review
by [Julio Faerman](http://jfaerman.com.br)

* [This Document: http://jfaerman.com.br/sf.html](http://jfaerman.com.br/sf.html)
* [Keynote with Andy Jassy](https://youtu.be/JRODD1_jBww)
* [SF Summit Playlist](https://www.youtube.com/playlist?list=PLhr1KZpdzukfOdRFXjVcllo-AJzShOSti)

## Business Growth
* YoY Growth: S3 Transfer: +102%, EC2 Hours: 93%
* 1+ Million *Active* Customers in Startup, Enterprise and Public Sector
* Premier Consulting and ISV Partners
* [Gartner Magic Quadrant](http://aws.amazon.com/resources/gartner-mq-2014-learn-more/)

> A rising tide lifts all boats

* Fasterst Growing Multi-Billion IT Company

## Cloud Has Become The New Normal

![Fishbowl](/assets/fishbowl.jpg)

### Cool Fish Of The Day

* Chris Anderson - The Long Tail [Blog](http://www.longtail.com/)

* Nicholas Carr - The Big Switch [Book](http://www.amazon.com/The-Big-Switch-Rewiring-Edison/dp/039334522X)

* Barry Schwartz - The Paradox Of Choice [TED](http://www.ted.com/talks/barry_schwartz_on_the_paradox_of_choice?language=en)

* Jez Humble - Lean Enterprise: How High Performance Organizations Innovate at Scale [Book](http://amzn.com/1449368425)

* Matt Stine - Migrating to Cloud-Native Application Architectures [eBook](http://pivotal.io/platform-as-a-service/migrating-to-cloud-native-application-architectures-ebook) and [Interview](http://www.infoq.com/articles/cloud-native-architectures-matt-stine?utm_campaign=infoq_content&utm_source=infoq&utm_medium=feed&utm_term=global)

## [Amazon Elastic File System](http://aws.amazon.com/efs/)

> The Preview of Amazon EFS is Coming Summer 2015

[Postagem no Blog](https://aws.amazon.com/blogs/aws/amazon-elastic-file-system-shared-file-storage-for-amazon-ec2/)
[Postagem no AWS Hub](http://awshub.com.br/amazon-elastic-file-system-armazenamento-de-arquivos-compartilhados-para-amazon-ec2/)

_Por quê?_

* Sistema de Arquivos Distribuido (NFSv4)
* Escalabilidade (DRDB vs. GlusterFS vs... ? PB!)
* Performance (SSD!)
* Disponibilidade (Multi-AZ!)
* Gerenciamento

_Por que não S3?_

* Object Storage (Map) vs File System (Tree)
* Legado

[Pricing](http://aws.amazon.com/efs/pricing/)

## [Amazon Machine Learning](http://aws.amazon.com/machine-learning/)
> Available Today

[Postagem no Blog](https://aws.amazon.com/blogs/aws/amazon-machine-learning-make-data-driven-decisions-at-scale/)
[Postagem no AWS Hub](http://awshub.com.br/amazon-machine-learning-tomada-de-decisoes-orientadas-por-dados-em-escala/)

_Por quê?_

* [A Cauda Longa](http://www.springer.com/cda/content/document/cda_downloaddocument/9783642132865-c1.pdf?SGWID=0-0-45-983845-p174021159)

* Sistemas de Recomendação
    * Clientes: Amazon, Netflix, GoodReads, ...
    * Parceiros: [Chaordic](https://www.chaordic.com.br)
    * Cuidado: http://www.businessinsider.com/amazon-suggested-items-2014-4

_Como?_

Aprendizagem **Supervisionada**

* Modelar
    * S3, Redshift, MySQL RDS
* Validar e otimizar
    * [EML Benchmark - Blog da Concrete](http://blog.concretesolutions.com.br/2015/04/amazon-machine-learning-benchmark/)
* Previsões
    * em lote
    * em tempo real

[Curso de ML no Coursera](https://www.coursera.org/course/ml)
[Pricing](http://aws.amazon.com/machine-learning/pricing/)


## [Desktop Markeplace and WAM](http://aws.amazon.com/workspaces/)

[Postagem no Blog](https://aws.amazon.com/blogs/aws/new-workspaces-application-marketplace/)
[Postagem no AWS Hub](http://awshub.com.br/novo-amazon-workspaces-application-manager-wam/)

[AWS Marketplace for Desktop](http://aws.amazon.com/marketplace/)

> You will be charged the price listed on AWS Marketplace for Desktop Apps for each application on a monthly subscription basis.

## Amazon EC2 ECS GA and Improved
[Postagem no Blog](https://aws.amazon.com/blogs/aws/ec2-container-service-ready-for-production-use/)
[Postagem no AWS Hub](http://awshub.com.br/ec2-container-service-aplicacoes-de-longo-prazo-balanceamento-de-cargo-e-muito-mais/)

### Anúncios
* GA
* Management Console
* Geographic Expansion (not GRU)
* CloudTrail Integration

### Novas Funcionalidades
* Load Balancing
* Health Management
* Scale-Up and Scale-Down
* Update Management 

## AWS Lambda – In Full Production with New Features for Mobile Devs
[Postagem no Blog](https://aws.amazon.com/blogs/aws/aws-lambda-update-production-status-and-a-focus-on-mobile-apps/)
[Postagem no AWS Hub](http://awshub.com.br/aws-lambda-a-todo-vapor-com-novos-recursos-para-mobile-devs/)

* "Production Grade" (100 concurrent)
* **Synchronous** Invoke 
* Trigger from SNS, Mobile SDK and **Cognito**
* IAM: Simplified and Cross Account Access
* Enhanced Console, Metrics & API
* Multiple Functions per Stream (DynamoDB/Lambda)
* **Java** soon

[Pricing](https://aws.amazon.com/lambda/pricing/)
