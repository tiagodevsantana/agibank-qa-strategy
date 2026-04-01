# QA Strategy - Agibank Test Ecosystem

## Visão Geral

Este conjunto de projetos representa uma estratégia completa de qualidade de software, cobrindo diferentes camadas de teste para garantir confiabilidade, estabilidade e escalabilidade da aplicação.

A abordagem segue princípios modernos de QA, incluindo separação por camadas, automação contínua e validação orientada a risco.

## Arquitetura de Testes

A estratégia está organizada em três camadas principais:

| Camada        | Objetivo                                      | Repositório |
|---------------|-----------------------------------------------|------------|
| E2E           | Validar fluxos completos do usuário           | https://github.com/tiagodevsantana/agibank-e2e |
| API           | Validar regras de negócio e integrações       | https://github.com/tiagodevsantana/agibank-api |
| Performance   | Validar escalabilidade e comportamento sob carga | https://github.com/tiagodevsantana/agibank-performance |

---

## Estratégia de Qualidade

A estratégia segue o conceito de pirâmide de testes:

- Testes de API garantem validação rápida e confiável das regras de negócio
- Testes E2E validam os fluxos críticos do usuário
- Testes de performance avaliam a capacidade do sistema sob carga

Essa abordagem reduz custo de manutenção, aumenta cobertura e melhora a confiabilidade das entregas.

---

## Fluxo de Validação

O processo de validação segue a seguinte ordem:

1. Testes de API são executados para validar regras de negócio
2. Testes E2E validam os fluxos principais da aplicação
3. Testes de performance avaliam comportamento sob carga
4. Resultados são analisados e utilizados para tomada de decisão

---

## Objetivos da Estratégia

- Reduzir falhas em produção
- Aumentar confiança nas releases
- Identificar gargalos de performance
- Garantir cobertura dos fluxos críticos
- Melhorar a qualidade percebida pelo usuário final

---

## Boas Práticas Aplicadas

- Separação por tipo de teste
- Automação como base da estratégia
- Execução via linha de comando (CI-ready)
- Publicação de relatórios
- Uso de métricas para tomada de decisão

---

## Métricas de Qualidade

A estratégia considera:

- Tempo de resposta (performance)
- Percentis (P90 / P95)
- Taxa de erro
- Cobertura de testes
- Estabilidade dos fluxos críticos

---

## Evolução Contínua

Os projetos estão estruturados para evolução contínua, permitindo:

- Inclusão de novos cenários de teste
- Escalabilidade da execução
- Integração com pipelines CI/CD
- Monitoramento contínuo de qualidade

---

## Autor

Tiago Santana  
QA Engineer  

LinkedIn: https://www.linkedin.com/in/tssqa/

---

## Considerações Finais

Este ecossistema demonstra uma abordagem estruturada de qualidade, indo além da execução de testes e focando em estratégia, cobertura e confiabilidade das entregas.
