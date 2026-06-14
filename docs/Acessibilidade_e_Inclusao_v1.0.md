# Acessibilidade e Inclusão v1.0

## Projeto

**ComFYS**

O canal inteligente que aproxima a FYS de seus parceiros de negócio por meio de orientação, aprendizado, oportunidades e relacionamento contínuo.

---

# Visão

A acessibilidade no ComFYS não será tratada como um requisito adicional ou uma etapa posterior do desenvolvimento.

Ela será considerada um princípio fundamental do produto desde sua concepção, garantindo que qualquer pessoa possa acessar informações, interagir com a plataforma e obter valor de forma independente, segura e confortável.

O ComFYS deve ser acessível para todas as pessoas, independentemente de limitações físicas, sensoriais, cognitivas, tecnológicas ou do seu nível de familiaridade com ferramentas digitais.

---

# Objetivos

O ComFYS deve:

* Promover inclusão digital.
* Reduzir barreiras de acesso.
* Facilitar a comunicação.
* Apoiar diferentes perfis de usuários.
* Garantir autonomia na utilização da plataforma.
* Oferecer uma experiência simples, clara e intuitiva.

---

# Público Considerado

O projeto deverá contemplar as necessidades de:

* Pessoas com baixa visão.
* Pessoas cegas que utilizam leitores de tela.
* Pessoas daltônicas.
* Pessoas com dislexia.
* Pessoas com limitações motoras.
* Pessoas que utilizam navegação por teclado.
* Pessoas que utilizam comandos por voz do sistema operacional.
* Pessoas com baixa alfabetização digital.
* Pessoas com mais de 50 anos.
* Usuários em ambientes operacionais com alta carga de trabalho.

---

# Conformidade

## Padrão Principal

O ComFYS deverá buscar conformidade com:

**WCAG 2.1 Nível AA**

Sempre que tecnicamente viável.

---

# Princípios de Acessibilidade

## Perceptível

As informações devem ser apresentadas de forma que todos os usuários consigam perceber seu conteúdo.

### Diretrizes

* Contraste adequado entre texto e fundo.
* Textos legíveis em diferentes dispositivos.
* Estrutura visual consistente.
* Ícones acompanhados de texto quando necessário.
* Conteúdo não dependente exclusivamente de cor.

---

## Operável

Todos os usuários devem conseguir navegar e interagir com a plataforma.

### Diretrizes

* Navegação completa por teclado.
* Ordem lógica de foco.
* Estados de foco claramente visíveis.
* Áreas clicáveis adequadas.
* Compatibilidade com tecnologias assistivas.

---

## Compreensível

O conteúdo deve ser simples e fácil de entender.

### Diretrizes

* Linguagem objetiva.
* Frases curtas.
* Evitar jargões técnicos.
* Mensagens claras.
* Instruções simples.
* Feedback imediato das ações do usuário.

---

## Robusto

O sistema deve funcionar adequadamente com tecnologias assistivas.

### Diretrizes

* HTML semântico.
* Estrutura compatível com leitores de tela.
* Uso correto de landmarks.
* Uso apropriado de atributos ARIA quando necessário.

---

# Inclusão Digital

Além da acessibilidade técnica, o ComFYS adotará princípios de inclusão digital.

---

## Baixa Alfabetização Digital

Muitos comerciantes possuem pouca familiaridade com plataformas digitais.

### Diretrizes

* Fluxos guiados.
* Poucos passos por tarefa.
* Interface conversacional.
* Linguagem simples.
* Ações claramente identificadas.

---

## Usuários 50+

Grande parte dos proprietários e gestores de estabelecimentos possui idade superior a 50 anos.

### Diretrizes

* Fontes legíveis.
* Espaçamento adequado.
* Botões maiores.
* Redução da carga cognitiva.
* Navegação simples.
* Feedback visual consistente.

---

## Uso em Ambiente Operacional

O sistema poderá ser utilizado durante a rotina de trabalho.

### Diretrizes

* Interações rápidas.
* Pouca digitação.
* Respostas objetivas.
* Informações relevantes em destaque.
* Redução de distrações visuais.

---

# Diretrizes para Daltonismo

O ComFYS deverá considerar os principais tipos de deficiência na percepção de cores.

## Cenários Prioritários

* Daltonismo Vermelho-Verde.
* Daltonismo Azul-Amarelo.

### Diretrizes

* Não utilizar apenas cor para transmitir significado.
* Utilizar ícones, textos e indicadores complementares.
* Garantir contraste adequado.
* Validar componentes críticos em simuladores de daltonismo.

### Exemplos

Corretamente:

✔ Sucesso

⚠ Atenção

✖ Erro

Incorretamente:

Verde = sucesso

Vermelho = erro

Sem qualquer reforço visual adicional.

---

# Diretrizes para Dislexia

O ComFYS deverá minimizar barreiras relacionadas à leitura.

## Diretrizes

* Frases curtas.
* Parágrafos curtos.
* Estrutura hierárquica clara.
* Espaçamento adequado entre linhas.
* Evitar blocos extensos de texto.
* Evitar linguagem excessivamente técnica.

---

# Diretrizes para Baixa Visão

## Diretrizes

* Contraste elevado.
* Possibilidade de ampliação sem perda de conteúdo.
* Componentes responsivos.
* Boa legibilidade em dispositivos móveis.

---

# Navegação por Teclado

Todas as funcionalidades críticas deverão ser utilizáveis sem mouse.

## Diretrizes

* Tabulação lógica.
* Indicador de foco visível.
* Acesso a botões e formulários.
* Compatibilidade com atalhos assistivos.

---

# Leitores de Tela

## Diretrizes

* Estrutura semântica correta.
* Hierarquia adequada de títulos.
* Labels associadas aos campos.
* Textos alternativos quando aplicável.
* Feedback acessível para erros e confirmações.

---

# Comandos por Voz

## Estratégia Inicial

O MVP não implementará recursos próprios de reconhecimento de voz.

### Objetivo

Garantir compatibilidade com:

* Recursos nativos do Windows.
* Recursos nativos do Android.
* Recursos nativos do iOS.
* Ferramentas assistivas compatíveis com navegadores modernos.

---

# Metas Mensuráveis

## Conformidade

* WCAG 2.1 AA como referência principal.

## Lighthouse

* Accessibility Score ≥ 95.

## Navegação

* 100% das funcionalidades principais acessíveis por teclado.

## Contraste

* Todos os componentes críticos compatíveis com WCAG AA.

## Estrutura

* Hierarquia correta de títulos.
* Uso consistente de HTML semântico.

## Testes

Validação mínima utilizando:

* Lighthouse.
* Navegação por teclado.
* Simuladores de daltonismo.
* Leitor de tela.
* Testes responsivos.

---

# Princípio Final

A acessibilidade no ComFYS não será tratada apenas como conformidade técnica.

Ela será utilizada como ferramenta de inclusão, usabilidade e geração de valor, garantindo que comerciantes de diferentes perfis possam utilizar a plataforma com autonomia, conforto e eficiência.
