# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 15 de outubro de 2024  
**Empresa:** Abstergo Industries  
**Responsável:** Alexandre Dresch.

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Alexandre Dresch. O objetivo do projeto foi elencar 3 serviços AWS com a finalidade de realizar diminuição de custos imediatos, otimizando a infraestrutura da plataforma virtual da farmácia fictícia.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos:

### Etapa 1: 
- **Amazon EC2 Auto Scaling**
- **Foco da ferramenta:** Otimização de custos com computação
- **Descrição de caso de uso:** Implementação de auto scaling para ajustar automaticamente a capacidade de computação conforme a demanda da plataforma da farmácia. Durante horários de pico (9h-12h e 14h-18h), o sistema escala horizontalmente para atender à demanda, e fora desses horários reduz automaticamente o número de instâncias, resultando em economia de aproximadamente 40% nos custos com EC2.

### Etapa 2: 
- **Amazon CloudFront**
- **Foco da ferramenta:** Redução de custos com transferência de dados e melhoria de performance
- **Descrição de caso de uso:** Implementação de CDN (Content Delivery Network) para distribuir conteúdo estático da plataforma (imagens de produtos, CSS, JavaScript) através de edge locations globais. Isso reduz a carga nos servidores origin, diminui a latência para usuários finais e reduz custos com transferência de dados em até 60%, além de melhorar a experiência do cliente.

### Etapa 3: 
- **Amazon S3 Intelligent-Tiering**
- **Foco da ferramenta:** Otimização de custos com armazenamento
- **Descrição de caso de uso:** Migração do armazenamento de arquivos estáticos (documentos, backups, imagens antigas) para o S3 Intelligent-Tiering, que automaticamente move os dados entre tiers de acesso frequente, infrequente e arquivamento baseado nos padrões de acesso. Isso resulta em economia média de 30-40% nos custos de armazenamento sem impacto na disponibilidade dos dados.

## Conclusão

A implementação dessas ferramentas na empresa Abstergo Industries tem como esperado **redução imediata de aproximadamente 45% nos custos mensais com infraestrutura na AWS**, além de melhorar a performance e escalabilidade da plataforma da farmácia virtual. A automação proporcionada por esses serviços também reduz a necessidade de intervenção manual na gestão de infraestrutura. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- Documentação técnica de implementação do Auto Scaling
- Relatório de análise de custos pré e pós-implantação
- Dashboard de monitoramento de performance da plataforma

---

**Assinatura do Responsável pelo Projeto:**

Alexandre Dresch.  
*Arquiteto de Soluções AWS*  
Abstergo Industries
