# Trabalho Prático 2 (TP2) — Design de IHC: Plataforma de Locação de Imóveis em Itacoatiara

Repositório do Trabalho Prático 2 da disciplina **Interação Humano-Computador (IHC)**, ministrada pelo **Prof. Dr. Andrey Rodrigues** no Instituto de Ciências Exatas e Tecnologia da Universidade Federal do Amazonas (**ICET/UFAM**).

## Equipe

- Felipe Gabriel dos Santos Silva
- João Henrique de Souza Barros
- Jorge Victor Lima de Oliveira
- Lucia Vitória dos Santos Menezes
- Matheus Azevedo Dino Sousa
- Rhuan Felipe Neves Sena

---

## Apresentação do Sistema

O projeto desenvolve o design de IHC de uma **plataforma digital para locação mensal de imóveis residenciais em Itacoatiara (AM)**, voltada principalmente a estudantes universitários — muitos vindos de outros municípios ou estados — e a locadores locais.

Atualmente, a divulgação e a busca por moradia na cidade dependem de indicações de terceiros, grupos informais e ligações sem garantia de disponibilidade, o que gera insegurança, falta de informações sobre custos reais e desistências após acordos verbais. A solução proposta centraliza os anúncios com fotos de todos os cômodos, localização no mapa, valor total mensal e itens inclusos, além de oferecer recursos de verificação de identidade, atualização de disponibilidade, agendamento de visitas (presenciais ou virtuais) e configurações de acessibilidade para usuários com baixa visão e dificuldade motora nas mãos.

---

## Índice Navegável

### 1. Imersão
- [Briefing com o Cliente](01-imersao/1-briefing.md)
- [Matriz CSD](01-imersao/2-matriz-csd.md)
- [Pesquisa com Usuários](01-imersao/3-pesquisa-com-usuario.md)

### 2. Ideação
- [Personas (PATHY)](02-ideacao/1-personas.md)
- [Metamensagem](02-ideacao/2-metamensagem.md)
- [Mapa de Objetivos](02-ideacao/3-mapa-de-objetivos.md)
- [HTAs (Hierarchical Task Analysis)](02-ideacao/4-htas.md)
- [Diagramas MoLIC](02-ideacao/5-molic.md)

### 3. Prototipação
- [Protótipos de Baixa Fidelidade (Sketches)](03-prototipacao/1-sketches.md)

---

## Organização do Repositório

```text
Design-IHC/
├── 01-imersao/
│   ├── 1-briefing.md
│   ├── 2-matriz-csd.md
│   └── 3-pesquisa-com-usuario.md
├── 02-ideacao/
│   ├── 1-personas.md
│   ├── 2-metamensagem.md
│   ├── 3-mapa-de-objetivos.md
│   ├── 4-htas.md
│   └── 5-molic.md
├── 03-prototipacao/
│   └── 1-sketches.md
├── imagens/
└── README.md
```

---

## Resumo das Etapas Realizadas

### Etapa 1: Imersão
- **Briefing com o Cliente:** Realizado presencialmente nos dias 15/11 e 16/11/2026 com um casal de locadores de Itacoatiara (8 a 10 anos de atuação), utilizando roteiro semiestruturado em 4 blocos para levantar demanda inicial, público afetado, problemas prioritários, fontes, padrão prévio e restrições.
- **Matriz CSD:** Organização dos achados do briefing em 19 linhas de Certezas, Suposições e Dúvidas, mapeando diretamente os itens que orientaram a pesquisa complementar com os usuários.
- **Pesquisa com Usuários:** Estudo exploratório com 13 participantes (12 respostas via formulário online e 1 entrevista com participante com baixa visão e dificuldade motora nas mãos), investigando canais de busca, dificuldades, critérios de escolha, contrato, confiança e experiência com tecnologia.

### Etapa 2: Ideação
- **Personas:** Criação de quatro personas baseadas na técnica PATHY — **Davi Nascimento** (estudante de fora de Itacoatiara), **Isabela Cunha** (estudante de Itacoatiara), **Thiago Moreira** (estudante com necessidade de acessibilidade) e **Antônio Ribeiro** (locador).
- **Metamensagem:** Elaboração da metamensagem do sistema segundo o template da Engenharia Semiótica, contemplando estudantes, locadores e necessidades de acessibilidade, acompanhada de legenda e tabela de evidências.
- **Mapa de Objetivos:** Modelagem visual dos objetivos dos papéis **L** (Locatário), **LA** (Locatário com necessidade de acessibilidade) e **LO** (Locador), organizados em seis grupos funcionais.
- **HTAs:** Modelagem de cinco tarefas principais decompostas em subtarefas e planos de operação (Criar perfil de locatário, Criar perfil de locador, Cadastrar imóvel, Buscar um imóvel disponível e Alugar um imóvel disponível), apresentadas em alinhamento direto com o Mapa de Objetivos.
- **Diagramas MoLIC:** Representação da interação usuário-sistema como conversa em cinco diagramas correspondentes aos HTAs, com visão geral e recortes ampliados detalhando cenas, transições e recuperações de ruptura.

### Etapa 3: Prototipação
- **Sketches:** Elaboração de cinco telas de baixa fidelidade no Excalidraw (Criar conta, Acessibilidade, Busca de imóveis, Detalhes do imóvel e Cadastrar imóvel), com versões alternativas (A e B) para as telas 2, 3 e 5, analisando usabilidade, comunicabilidade, experiência do usuário (UX) e coerência com o MoLIC e os HTAs.

---

## Tecnologias e Ferramentas Utilizadas

* **GitHub & Markdown:** Documentação e gestão do repositório.
* **Google Meet & Google Forms:** Realização de reuniões dedicadas à direção do trabalho e aplicação dos formulários de pesquisa com o usuário.
* **Excel:** Modelagem da Matriz CSD.
* **Draw.io:** Modelagem e elaboração visual do Mapa de Objetivos, dos diagramas HTA e dos diagramas MoLIC.
* **Canva:** Modelagem e elaboração visual das Personas.
* **Excalidraw:** Modelagem e elaboração visual dos sketches de baixa fidelidade do sistema.

---

## Observações Gerais

- A identidade de todos os participantes do briefing e da pesquisa com usuários foi preservada em todos os registros e evidências.

---

## Declaração de Uso de IA

A equipe utilizou ferramentas de Inteligência Artificial, como Claude e Gemini, para auxiliar na organização de partes da documentação e revisão textual. As ferramentas foram utilizadas apenas como suporte metodológico, sendo que todas as ações foram revisadas e validadas integralmente pelos integrantes da equipe.
