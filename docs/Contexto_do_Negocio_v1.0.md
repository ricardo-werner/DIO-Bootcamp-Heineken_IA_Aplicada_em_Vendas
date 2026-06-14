# Contexto do Negócio v1.0

## Projeto

## ComFYS

### Copiloto Comercial Inteligente para Parceiros FYS

---

# Visão Geral do Negócio

A FYS é uma marca de bebidas inserida em um mercado altamente competitivo, onde presença de marca, disponibilidade de produto e relacionamento com o ponto de venda são fatores decisivos para a venda.

No contexto do bootcamp, a principal oportunidade identificada foi apoiar micro, pequenos e médios comerciantes que comercializam ou podem comercializar produtos FYS, fortalecendo a relação com a marca por meio de orientação comercial e informações úteis para o dia a dia do negócio.

---

# Desafio de Negócio

A equipe comercial da FYS atende uma grande quantidade de estabelecimentos espalhados por diferentes regiões do país.

Por limitações operacionais, não é possível manter vendedores ou representantes presentes diariamente em todos os pontos de venda.

Isso gera alguns desafios importantes:

- menor frequência de contato com o comerciante;
- perda de oportunidades de comunicação;
- dúvidas sobre produtos e campanhas sem resposta imediata;
- dificuldade para reforçar exposição, sazonalidade e promoções;
- menor presença percebida da marca no dia a dia do estabelecimento.

---

# Oportunidade

Existe uma oportunidade clara de criar um canal digital que complemente a atuação comercial da FYS e mantenha o comerciante mais próximo da marca, mesmo quando não houver visita presencial do vendedor.

Esse canal pode apoiar:

- dúvidas sobre produtos;
- entendimento de campanhas;
- identificação de oportunidades comerciais;
- orientação sobre exposição;
- comunicação de datas sazonais e eventos regionais;
- fortalecimento da presença da marca no estabelecimento.

---

# Cenário Atual

Atualmente o comerciante depende principalmente de:

- visitas presenciais;
- materiais promocionais;
- conhecimento próprio;
- contatos comerciais.

Nem sempre essas informações estão disponíveis quando surge uma dúvida ou oportunidade de negócio.

O ComFYS busca reduzir essa lacuna.

---

# Proposta da Solução

O ComFYS surge como um copiloto comercial inteligente baseado em Inteligência Artificial.

A solução foi pensada para atuar como um canal de apoio contínuo ao comerciante, oferecendo respostas rápidas, contextualizadas e úteis com base em uma base de conhecimento estruturada da própria FYS.

A ideia não é substituir o vendedor.

A proposta é ampliar seu alcance, oferecendo suporte quando o contato presencial não estiver disponível.

---

# Público de Interesse

## Público Principal

### Comerciante

- Mercadinhos de bairro
- Padarias
- Conveniências
- Bares
- Restaurantes
- Distribuidoras
- Deliverys de bebidas
- Pequenos e médios varejistas

Esse público precisa de orientações simples, práticas e objetivas, com baixo atrito de uso e linguagem clara.

---

## Público Secundário

### Equipe Comercial FYS

- Vendedores
- Representantes comerciais
- Supervisores de vendas
- Coordenadores comerciais

Esse público se beneficia da solução porque o ComFYS ajuda a manter o relacionamento com o parceiro comercial mesmo entre as visitas presenciais.

---

# Necessidade de Mercado

Muitos comerciantes ainda operam com baixa maturidade digital e possuem pouco tempo para lidar com ferramentas complexas.

Na prática, isso significa que a solução precisa ser:

- fácil de usar;
- rápida;
- acessível;
- mobile-first;
- clara na comunicação;
- útil desde a primeira interação.

---

# Papel da Base de Conhecimento

Para responder com qualidade, o ComFYS depende de uma base de conhecimento organizada.

Essa base será composta por documentos internos que reúnem informações sobre produtos, dúvidas frequentes, objeções comerciais e contexto do negócio.

## Arquivos previstos

```text
knowledge/

├── produtos.md
├── perguntas-frequentes.md
├── objecoes.md
└── contexto-do-negocio.md

---

## Base de Conhecimento da Solução

O ComFYS utiliza uma base de conhecimento estruturada para apoiar as respostas fornecidas aos comerciantes e à equipe comercial.

Essa base de conhecimento foi organizada de forma modular, permitindo evolução contínua do conteúdo e futura integração com mecanismos de Inteligência Artificial, busca semântica ou sistemas de recuperação de informações (RAG).

Estrutura prevista:

knowledge/

├── produtos.json
├── faq.json
├── objecoes.json
├── campanhas.json
└── eventos_regionais.json

Cada arquivo possui uma responsabilidade específica:

- produtos.json: informações sobre portfólio, categorias e características dos produtos.
- faq.json: dúvidas frequentes dos comerciantes.
- objecoes.json: tratamento de objeções comerciais.
- campanhas.json: campanhas promocionais e ações comerciais.
- eventos_regionais.json: oportunidades relacionadas a datas sazonais, eventos locais e características regionais.

Essa organização permite que o ComFYS forneça respostas mais contextualizadas, relevantes e alinhadas às necessidades do negócio.
