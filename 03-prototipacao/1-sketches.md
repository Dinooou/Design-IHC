# Sketches

Os sketches são protótipos de baixa fidelidade de **cinco telas** da plataforma, desenhados no Excalidraw, sem interação. As telas 2, 3 e 5 têm **duas versões alternativas (A e B)**, para discutir qual corresponde melhor ao modelo de interação. Cada tela vem do MoLIC (`5-molic.md`) e dos HTAs (`4-htas.md`), e atende às personas (`1-personas.md`). Os valores, nomes e fotos são fictícios e servem só como exemplo, e o nome do aplicativo ainda é representado por um espaço de logo.

Em todas as telas, as anotações amarelas ao lado resumem a **usabilidade** (facilidade e eficiência de uso), a **comunicabilidade** (clareza da mensagem do designer ao usuário) e a **experiência do usuário** (emoções e percepções durante o uso), e indicam a origem da tela.

## Visão geral

| Tela | Versões | MoLIC de origem | HTA | Personas |
|---|---|---|---|---|
| 1. Criar conta | Única | Criação de perfil (Informar dados de acesso) | HTA 1 e 2, nó 1 | Davi, Isabela, Thiago e Antônio |
| 2. Acessibilidade | A e B | Criação de perfil de locatário (Aplicar configurações de acessibilidade) | HTA 1, nó 4 | Thiago |
| 3. Busca de imóveis | A e B | Busca de imóvel (Filtros, Resultados e Mapa) | HTA 4, nós 1 e 2 | Davi, Isabela e Thiago |
| 4. Detalhes do imóvel | Única | Busca de imóvel (Consulta das informações e Favoritos) | HTA 4, nós 3 e 4; HTA 5, nós 1 e 2 | Davi, Isabela e Thiago |
| 5. Cadastrar imóvel | A e B | Cadastro do imóvel (Valor total mensal, Revisão e publicação) | HTA 3, nós 3 a 8 | Antônio |

---

## Tela 1: Criar conta

![Tela 1: Criar conta](../imagens/sketch-tela-1-criar-conta.png)

**Elementos.** Barra com Cancelar, espaço de logo, indicador de progresso (etapa 1 de 4), escolha entre alugar e anunciar um imóvel, escolha do método de acesso (e-mail ou celular), campo de e-mail, aviso de que um código será enviado, botão Enviar código, entrada com conta Google e link para quem já tem conta.

**MoLIC.** Corresponde à cena Informar dados de acesso, em que o usuário escolhe entre e-mail, número de celular ou conta Google (XOR), e à opção de cancelar a criação do perfil. O envio do código leva à cena seguinte, Verificar identidade. A escolha entre alugar e anunciar define se o usuário segue o MoLIC do locatário ou do locador, que começam igual.

**HTA.** Nó 1 (Criar login e senha) dos HTAs 1 e 2, com a escolha do método de acesso (1.1) e os dados de acesso (1.2).

**Usabilidade, comunicabilidade e UX.** O usuário decide uma coisa por vez, vê em que etapa está e pode cancelar a qualquer momento. O texto avisa que um código será enviado antes de ele prosseguir. A entrada com Google evita criar mais uma senha.

---

## Tela 2: Acessibilidade

### Versão A: etapa final do perfil

![Tela 2, versão A](../imagens/sketch-tela-2a-acessibilidade.png)

### Versão B: painel com prévia, disponível em qualquer etapa

![Tela 2, versão B](../imagens/sketch-tela-2b-acessibilidade.png)

**Elementos.** A versão A traz o controle do tamanho da fonte com uma prévia de texto, a escolha do contraste, a chave de compatibilidade com leitor de tela e o botão Salvar configurações, como etapa 4 de 4. A versão B acrescenta um aviso de que a tela está disponível em qualquer etapa, uma prévia com um anúncio de exemplo, botões grandes para o tamanho da fonte, a escolha do tamanho dos botões e áreas de toque, e a opção de restaurar o padrão.

**MoLIC.** Corresponde à cena Aplicar configurações de acessibilidade do MoLIC de criação do perfil de locatário (ajustar a exibição com fonte e contraste, compatibilidade com leitor de tela e salvar configurações).

**HTA.** Nó 4 do HTA 1 (Aplicar configurações de acessibilidade).

**Persona.** Thiago, com baixa visão e dificuldade motora nas mãos.

**Discussão das versões.**
- **A** segue o modelo de interação: a acessibilidade é a última etapa do perfil, como no MoLIC e no HTA. A prévia de texto ajuda quem tem baixa visão a ver o efeito antes de salvar.
- **B** atende melhor à persona Thiago, porque permite ajustar a interface antes de preencher os dados e traz áreas de toque grandes, mas propõe o acesso em qualquer etapa e a opção de botões maiores, que não estão no MoLIC nem no HTA.
- **Escolha para a próxima etapa:** manter a versão A como base e incorporar da B a prévia com anúncio de exemplo e os botões maiores. O acesso antecipado depende de atualizar o MoLIC e o HTA 1.

---

## Tela 3: Busca de imóveis

### Versão A: lista de resultados

![Tela 3, versão A](../imagens/sketch-tela-3a-busca-lista.png)

### Versão B: mapa como visão principal

![Tela 3, versão B](../imagens/sketch-tela-3b-busca-mapa.png)

**Elementos.** Em ambas, campo de região (Itacoatiara, AM), filtros de bairro, preço e tipo, alternância entre Lista e Mapa e barra de navegação (Buscar, Favoritos, Solicitações e Perfil). A versão A mostra cards com foto, tipo, bairro, distância da UFAM, valor total mensal e o que está incluso. A versão B mostra o mapa com os preços dos imóveis, a referência da UFAM e o cartão do imóvel selecionado com o botão Detalhes.

**MoLIC.** Correspondem às cenas Filtros de busca (região, faixa de preço e tipo de imóvel), Visualização dos resultados (lista de imóveis e informações resumidas, com acesso ao mapa) e Visualização do mapa (exibir mapa com imóveis, localizar, explorar a região ao redor e acessar detalhes). A região mostra apenas Itacoatiara e o bairro, porque a plataforma atende a cidade.

**HTA.** Nó 1 (Aplicar filtros de busca) e nó 2 (Checar localidade no mapa) do HTA 4.

**Personas.** Davi, Isabela e Thiago. A pesquisa mostrou que endereço e mapa são considerados indispensáveis por 12 de 13 participantes, o valor total mensal por 12 de 13 e a distância da universidade é critério de 10 de 13.

**Discussão das versões.**
- **A** segue a ordem do MoLIC: primeiro a lista de resultados e depois o mapa. O card dá destaque ao que mais pesa na escolha, como o valor total mensal e o que está incluso.
- **B** explora melhor a localização e a distância até a UFAM, mas abre pelo mapa, o que inverte a ordem do MoLIC.
- **Escolha para a próxima etapa:** a versão A como tela inicial da busca, com a alternância Lista e Mapa que já existe nas duas versões.

---

## Tela 4: Detalhes do imóvel

![Tela 4: Detalhes do imóvel](../imagens/sketch-tela-4-detalhes-imovel.png)

**Elementos.** Fotos navegáveis, título, bairro e distância da UFAM, bloco do valor total mensal em destaque (com o detalhamento do aluguel e dos encargos), o que está incluso, características (quartos, banheiros, área e comodidades), segurança, localização, informações do locador e uma barra fixa com Demonstrar interesse e Chat. A tela é rolável e aparece inteira no sketch.

**MoLIC.** Corresponde à cena Consulta das informações do imóvel (características, quantidade de quartos e banheiros, características adicionais, valor, imagens com navegação entre as fotos e informações do locador) e à ação Adicionar aos favoritos, no topo da tela.

**HTA.** Nós 3 (Consultar informações do imóvel) e 4 (Adicionar à lista de favoritos) do HTA 4. Os botões Demonstrar interesse e Chat vêm dos nós 1 e 2 do HTA 5 (Alugar um imóvel disponível).

**Personas.** Davi, Isabela e Thiago.

**Usabilidade, comunicabilidade e UX.** A ação principal fica fixa na base da tela. O valor total mensal e o que está incluso têm o maior destaque, como a pesquisa indicou. A segurança do imóvel e o bloco do locador dão confiança antes do contato, já que a desconfiança de quem anuncia foi apontada pelos participantes.

---

## Tela 5: Cadastrar imóvel

### Versão A: cadastro em etapas

![Tela 5, versão A](../imagens/sketch-tela-5a-cadastro-etapas.png)

### Versão B: página única

![Tela 5, versão B](../imagens/sketch-tela-5b-cadastro-pagina-unica.png)

**Elementos.** A versão A mostra a etapa 5 de 6 (Valor total mensal) com a barra de progresso, o campo de valor total, a seleção do que está incluso (água, energia, internet e condomínio), os encargos e a garantia (opcionais), os botões Voltar e Prosseguir e o link para cancelar o cadastro. A versão B reúne as seções em uma só página, com as quatro primeiras completas, a seção Valor total mensal aberta, a Revisão e publicação bloqueada e o botão Publicar anúncio desabilitado.

**MoLIC.** Correspondem às cenas Valor total mensal (valor total, encargos de condomínio e IPTU, garantia de caução e reajuste, e Prosseguir), Revisão e publicação do anúncio e Confirmar cancelamento. A seleção do que está incluso vem do título da etapa no HTA 3.

**HTA.** Nó 7 (Informar valor total mensal e o que está incluso) e, na versão B, os nós 3 a 8 do HTA 3.

**Persona.** Antônio, que quer divulgar os imóveis com as condições oferecidas.

**Discussão das versões.**
- **A** é a que mais se aproxima do MoLIC: uma cena por etapa, Prosseguir entre elas e confirmação ao cancelar. Guia o locador passo a passo.
- **B** dá a visão do cadastro inteiro e deixa o locador escolher a ordem, mas a tela fica longa e foge do fluxo em etapas do MoLIC.
- **Escolha para a próxima etapa:** a versão A.

