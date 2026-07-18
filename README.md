# Framework Comitê de Investimentos para GPT

> Uma arquitetura metodológica para transformar Grandes Modelos de Linguagem (LLMs) em um Comitê de Investimentos disciplinado, auditável e orientado à gestão patrimonial de longo prazo para investidores pessoa física brasileiros.

---

# Visão Geral

Este projeto não é um conjunto de prompts.

Também não é um sistema para indicar ativos, prever o mercado ou substituir a tomada de decisão do investidor.

O **Framework Comitê de Investimentos para GPT** fornece uma metodologia estruturada para utilização de Inteligência Artificial na gestão patrimonial de longo prazo, permitindo que um GPT atue como um Comitê de Investimentos permanente, consistente, transparente e auditável.

O foco está na qualidade do processo decisório, e não na tentativa de prever o comportamento futuro do mercado.

---

# Objetivos

O Framework foi desenvolvido para:

* aumentar a qualidade das decisões patrimoniais;
* reduzir decisões impulsivas;
* padronizar análises de investimento;
* manter consistência ao longo dos anos;
* integrar diferentes fontes de informação;
* transformar conhecimento externo em inteligência patrimonial independente;
* preservar a estratégia de longo prazo do investidor.

---

# Filosofia

O Comitê não busca "acertar o mercado".

Busca tomar decisões patrimoniais melhores.

Toda decisão deverá priorizar, nesta ordem:

1. Preservação patrimonial;
2. Controle de risco;
3. Crescimento sustentável da renda passiva;
4. Crescimento patrimonial.

A alocação estratégica representa o destino da carteira, mas não determina automaticamente a destinação de cada novo aporte.

Cada aporte é tratado como uma **decisão patrimonial marginal**, considerando simultaneamente:

* Política Patrimonial;
* estágio patrimonial;
* oportunidades identificadas;
* riscos;
* cenário econômico;
* benefício patrimonial esperado.

---

# Público-Alvo

O Framework foi desenvolvido para investidores pessoa física brasileiros que:

* investem com horizonte de longo prazo;
* encontram-se em fase de acumulação ou pré-aposentadoria;
* desejam utilizar Inteligência Artificial como apoio à decisão;
* valorizam disciplina, governança patrimonial e gestão de risco.

---

# Arquitetura

O projeto está dividido em duas grandes camadas.

## Base de Conhecimento

Representa a inteligência permanente do Comitê.

Ela define:

* como o Comitê pensa;
* quais princípios utiliza;
* quais metodologias aplica;
* como as decisões devem permanecer consistentes ao longo do tempo.

```text
knowledge-base/
│
├── 00-Instruções.md
├── 01-Framework.md
├── 02-Política Patrimonial.md
├── 03-Perfil e Parâmetros.md
├── 04-Metodologia de Avaliação de Ativos.md
├── 05-Política de Oportunidades Patrimoniais.md
├── 06-Metodologia de Rebalanceamento.md
├── 07-Metodologia de Research.md
├── 08-Política Tributária.md
├── 09-Registro de Decisões.md
├── 10-Convenções.md
└── 11-Glossário.md
```

---

## Protocolos

Os Protocolos representam os procedimentos operacionais utilizados em cada interação.

Cada conversa utiliza um Protocolo Principal, responsável por conduzir a análise daquele ciclo.

```text
protocols/
│
├── 00-Protocolo Geral.md
├── 01-Protocolo de Leitura da Carteira.md
├── 02-Protocolo de Research.md
├── 03-Protocolo de Aportes.md
├── 04-Protocolo de Rebalanceamento.md
├── 05-Protocolo de Revisão Estratégica.md
├── 06-Protocolo de Simulações.md
└── 07-Protocolo de Análise Tributária.md
```

---

# Arquitetura de Decisão

Toda análise segue o fluxo abaixo.

```text
Instruções
        │
        ▼
Framework
        │
        ▼
Política Patrimonial
        │
        ▼
Perfil e Parâmetros
        │
        ▼
Metodologia correspondente
        │
        ▼
Protocolo selecionado
        │
        ▼
Dados do ciclo
(carteira, aporte, research e mercado)
        │
        ▼
Análise integrada
        │
        ▼
Conclusão consolidada
        │
        ▼
Registro de Decisões
```

---

# Fluxo de Trabalho

Um ciclo típico de utilização ocorre da seguinte forma:

```text
Atualizar carteira
        │
Enviar novos aportes
        │
Enviar novos relatórios (quando houver)
        │
Selecionar o protocolo
        │
Executar a análise
        │
Receber a conclusão consolidada
        │
Registrar a decisão
```

Quando o protocolo não for informado, o Comitê deverá identificar automaticamente o procedimento mais adequado e informar essa escolha antes de iniciar a análise.

---

# Princípios do Projeto

Todo o Framework foi desenvolvido seguindo os seguintes princípios:

* independência analítica;
* disciplina;
* transparência;
* rastreabilidade;
* auditabilidade;
* visão de longo prazo;
* construção patrimonial;
* benefício patrimonial;
* simplicidade operacional;
* melhoria contínua.

---

# Como Utilizar

## 1. Criar um GPT Personalizado

Configure um GPT utilizando:

* Instruções;
* Base de Conhecimento;
* Protocolos.

---

## 2. Carregar a Base de Conhecimento

Adicione todos os documentos da pasta `knowledge-base`.

Esses documentos representam o conhecimento permanente do Comitê.

---

## 3. Executar um Protocolo

Sempre que possível, informe o protocolo desejado.

Exemplo:

```text
Execute o Protocolo 03 – Aportes.

Considere:

• carteira atual;
• aporte disponível;
• dividendos recebidos;
• materiais de research analisados neste ciclo.
```

Caso nenhum protocolo seja informado, o Comitê deverá selecionar automaticamente o procedimento mais adequado.

---

# Limitações

Este projeto:

* não prevê preços;
* não garante retornos;
* não substitui consultoria profissional;
* não realiza recomendações automáticas;
* não elimina riscos de investimento.

A responsabilidade pelas decisões permanece integralmente com o investidor.

---

# Contribuições

Contribuições são bem-vindas.

Caso deseje sugerir melhorias:

* abra uma *Issue*;
* envie um *Pull Request*;
* apresente justificativas técnicas para alterações metodológicas.

Consulte também o arquivo **CONTRIBUTING.md**.

---

# Licença

Este projeto está licenciado sob a **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**.

Consulte os arquivos **LICENSE** e **NOTICE.md** para mais informações.

---

# Aviso

Este Framework foi desenvolvido considerando o contexto do mercado financeiro brasileiro.

Conceitos como Tesouro Direto, FIIs, B3, CVM, tributação e previdência refletem a realidade regulatória do Brasil.

Embora sua arquitetura metodológica possa ser adaptada para outros países, recomenda-se revisar a Política Patrimonial, a Política Tributária e os Protocolos para adequação às respectivas legislações.

---

# Autor

**Marcus Vinicius Cirino e Silva**

Projeto iniciado em 2026 com o objetivo de desenvolver uma arquitetura metodológica para utilização de Inteligência Artificial como Comitê de Investimentos voltado à construção, preservação e gestão de patrimônio de longo prazo.
