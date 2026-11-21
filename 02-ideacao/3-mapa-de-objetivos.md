# Mapa de Objetivos

O mapa de objetivos representa graficamente os principais objetivos dos usuários ao interagir com a plataforma, a partir das personas (`1-personas.md`) e da metamensagem (`2-metamensagem.md`). Cada objetivo aparece com o papel que o realiza, e os objetivos compartilhados por mais de um papel estão identificados com todos os papéis no mesmo rótulo. As operações e os planos detalhados ficam para os HTAs (`4-htas.md`).

## Mapa

![Mapa de objetivos](../img/mapa-objetivos.jpeg)

## Legenda

Cada objetivo segue o formato **Papel | Objetivo final**, e a seta indica que o objetivo da direita é instrumentado diretamente pelos objetivos da esquerda.

| Papel | Significado | Personas |
|---|---|---|
| **L** | Locatário | Davi Nascimento e Isabela Cunha |
| **LA** | Locatário com necessidade de acessibilidade | Thiago Moreira |
| **LO** | Locador | Antônio Ribeiro |

Objetivos rotulados **L LA** são compartilhados pelas personas Davi, Isabela e Thiago. O objetivo rotulado apenas **LA** (aplicar configurações de acessibilidade) pertence à persona Thiago. O objetivo rotulado **L LA LO** (formalizar contrato de locação) é compartilhado pelas quatro personas.

## Objetivos por grupo

### Perfil de locatário (L, LA)
**Criação de perfil de locatário**
- Criar login e senha (L, LA)
- Adicionar dados complementares (L, LA)
- Definir preferências iniciais (L, LA)
- Aplicar configurações de acessibilidade (LA)

### Perfil de locador (LO)
**Criação de perfil de locador**
- Criar login e senha
- Adicionar dados complementares
- Definir preferências iniciais
- Cadastrar um imóvel (detalhado no grupo "Cadastrar um imóvel")

### Cadastrar um imóvel (LO)
**Cadastrar um imóvel na plataforma**
- Informar as especificações gerais
- Adicionar a localização do imóvel
- Inserir fotos do imóvel
- Informar medidas de segurança
- Informar valor total mensal e o que está incluso
- Publicar anúncio de imóvel disponível
- Atualizar disponibilidade do imóvel

### Busca de imóveis (L, LA)
**Buscar um imóvel disponível**
- Aplicar filtros de busca
- Checar localidade no mapa
- Consultar informações do imóvel
- Adicionar imóvel à lista de favoritos

### Aluguel de imóveis (L, LA)
**Alugar um imóvel disponível** (depende de buscar um imóvel disponível)
- "Demonstrar interesse" ao locador
- Contactar o locador através do chat
- Agendar visita ao imóvel
- Consultar status do processo

### Confirmar locação (LO)
**Confirmar locação junto ao locatário**
- Acessar notificação de interesse do locatário
- Checar perfil do locatário
- Contactar o locatário através do chat
- Confirmar visita ao imóvel
- Solicitar dados adicionais do locatário
- Formalizar contrato de locação (L, LA, LO)

## Relações entre os objetivos

- **Cadastrar um imóvel** é um dos objetivos do perfil de locador e se detalha no grupo "Cadastrar um imóvel".
- **Alugar um imóvel disponível** depende de **buscar um imóvel disponível**: o locatário escolhe o imóvel na busca antes de demonstrar interesse.
- O **interesse** demonstrado pelo locatário gera a notificação que o locador acessa em **confirmar locação**.
- **Formalizar contrato de locação** é um objetivo compartilhado: o locatário e o locador formalizam a locação juntos.

## Objetivos principais e a base nas etapas anteriores

| Objetivo principal | Papéis | Base nas etapas anteriores |
|---|---|---|
| Criação de perfil de locatário | L, LA | Pesquisa com usuários: 9 de 13 aceitam informar comprovante de estudante e 7 de 13 CPF para criar conta, e só 4 de 13 aceitam informar contato de familiar (opcional na metamensagem). A persona Thiago (baixa visão e dificuldade motora nas mãos) fundamenta as configurações de acessibilidade. |
| Criação de perfil de locador | LO | Briefing: os locadores sugeriram CPF ou CNPJ no cadastro, e a persona Antônio descreve esse perfil. |
| Cadastrar um imóvel na plataforma | LO | Briefing: os locadores querem divulgar os imóveis com as condições oferecidas (fotos, mobília e despesas), citam as câmeras de segurança e têm como um dos problemas a disponibilidade desatualizada. Pesquisa com usuários: valor total mensal (12 de 13) e o que está incluso (7 de 13) são informações indispensáveis, e 8 de 13 já descobriram que não havia vaga só depois do contato. |
| Buscar um imóvel disponível | L, LA | Pesquisa com usuários: endereço e mapa (12 de 13), valor total mensal (12) e fotos de todos os cômodos (11) são as informações mais indispensáveis. |
| Alugar um imóvel disponível | L, LA | Pesquisa com usuários: 8 de 13 já descobriram que não havia vaga só depois do contato, e 3 de 13 apontaram não poder visitar antes. Briefing: muitos interessados só veem fotos do imóvel. |
| Confirmar locação junto ao locatário | LO (o sub-objetivo de formalizar o contrato é L LA LO) | Briefing: os locadores priorizam o contrato, as desistências após acordo verbal e a falta de dados do inquilino e de familiares, além de querer receber avisos de interessados. Metamensagem: o estudante também formaliza a locação por contrato. |
