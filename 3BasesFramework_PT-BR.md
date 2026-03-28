📄 **Informações do documento**
Data de criação: 11/03/2026
Última modificação: 14/03/2026

---

## Sumário

1. Sobre o Framework
2. As 3 Bases
   2.1 Base Executiva
   2.2 Base Design
   2.3 Base Dev
3. Sistema de Hierarquia
   3.1 Bases e Operários
   3.2 Sistema de Ícones
4. Protocolo de Comunicação
   4.1 Comunicação entre Operários
   4.2 Comunicação entre Bases
5. Modelo de Elemento
6. Fluxo de Decisão e Iniciativa
   6.1 Critério de Entrada
   6.2 Fluxo de Iniciativa
   6.3 Limites de Escopo da Executiva
7. Arsenal
8. Representação Visual

---

## 1. Sobre o Framework

O 3 Bases Framework é um protocolo integrado de pensamento, documentação e tomada de decisão. Ele organiza qualquer projeto sob 3 perspectivas complementares e independentes — Executiva, Design e Dev — garantindo que nenhuma decisão seja tomada de forma isolada.

O framework nasceu da necessidade de um desenvolvedor solo organizar pensamento estratégico, criativo e técnico sem perder nenhuma perspectiva. Sua lógica, no entanto, é agnóstica de domínio — aplica-se a qualquer projeto que envolva estratégia, experiência e tecnologia.

O triângulo é a forma geométrica mais estável. 3 bases, 3 perspectivas, nenhuma hierarquia entre elas.

---

## 2. As 3 Bases

Cada base possui soberania absoluta sobre seu domínio. Nenhuma tem autoridade sobre o domínio da outra. Algo só entra no projeto se atender às 3.

O veto de uma base não é um ato de conflito — é um ato de proteção. Se o Dev veta, está salvando o projeto de um colapso técnico. Se a Executiva veta, está salvando do escopo incontrolável. Se o Design veta, está salvando da perda de identidade.

Cada base trabalha com uma linguagem própria de documentação: a Executiva documenta em Filosofias — define intenção, não implementação. Design e Dev documentam em Pilares e Diretrizes — definem como implementar. Quanto mais próximo da execução, mais concreto e mensurável.

Quando as bases são bem definidas, tendem a chegar nos mesmos princípios de forma independente — cada uma dentro do seu domínio, sem precisar referenciar as outras. Isso não é coincidência, é sinal de que o projeto tem uma visão central coerente. As bases são sócias, não subordinadas.

### 2.1 Base Executiva 🏛️🏢

Responsável pelo que o projeto deve ser, ter e quando. Cuida de tudo que é estrutural, burocrático e estratégico — escopo, versões, distribuição, RH, relações externas. É a base que separa a organização do público e protege as outras duas do caos operacional.

### 2.2 Base Design 🏛️🎨

Responsável por tudo que guia o jogador e define a experiência — direção de arte, direção de game design, roteiro, modelagem, música, marketing, embalagem física se houver. É a base criativa. Define a identidade e a sensação que o projeto transmite.

### 2.3 Base Dev 🏛️🛠️

Responsável por toda a infraestrutura técnica do projeto — linguagens, engines, frameworks, arquitetura, design patterns, algoritmos, banco de dados, APIs, metodologias de desenvolvimento. O Scrum e outras metodologias ágeis vivem dentro desta base, no subdomínio de gerenciamento de projeto. Não substitui o Scrum — complementa.

---

## 3. Sistema de Hierarquia

### 3.1 Bases e Operários

Cada base possui uma liderança e operários. Os operários são especialistas dentro do domínio de sua base — UX, roteiristas e animadores são operários do Design; front-end, back-end e QA são operários do Dev; RH e administrativo são operários da Executiva.

**Liderança** — toma decisões de base, representa a perspectiva nos conflitos entre bases.

**Operário** — aplica os princípios da sua base dentro dos elementos do projeto. Onde a base não especifica, o operário tem liberdade criativa.

### 3.2 Sistema de Ícones

O 🏛️ indica que algo é um princípio de base — uma decisão que governa e não é questionada pelos operários.

```
🏛️🏢 — princípio da Base Executiva
🏛️🎨 — princípio da Base Design
🏛️🛠️ — princípio da Base Dev
```

Sem 🏛️ — decisão de operário. Liberdade criativa dentro do domínio da sua base.

---

## 4. Protocolo de Comunicação

### 4.1 Comunicação entre Operários

Operários não se comunicam diretamente com operários de outras bases. Todo conflito ou necessidade de alinhamento é reportado ao líder da própria base.

```
Operário A (Design) → Líder Design → Líder Executiva → Operário B (Executiva)
```

Isso evita conflitos pessoais e garante que decisões sejam tomadas no nível correto.

### 4.2 Comunicação entre Bases

Líderes se comunicam diretamente quando há conflito ou decisão que impacta mais de uma base, podendo inclusive começar nos operários. A resolução sempre sobe, passando pelas 3 perspectivas antes de ser implementada. O problema de uma base pode exigir reestruturação em outras — e isso é esperado, não exceção.

**Exemplo real:**

O RH percebe que o dev front-end está demorando muito para entregar telas e reporta ao Líder Executivo.

O Líder Executivo conversa com o Líder Dev. O Líder Dev já conhece a situação internamente — o front-end está sobrecarregado, o QA mal consegue acompanhar o volume de testes por causa da quantidade de rotas e fluxos. O problema não está no front-end. Está em outro lugar.

O Líder Dev convoca os 3 líderes.

Com as 3 perspectivas na mesa:

- **Executiva** — o prazo está comprometendo o escopo?
- **Design** — o fluxo de rotas e UX está complexo demais?
- **Dev** — o front-end tem suporte de QA suficiente?

A causa raiz emerge: o Design havia criado um fluxo de rotas com complexidade desnecessária, sobrecarregando front-end e QA em cascata.

A solução exigiu reestruturação no Design — simplificação do fluxo — e ajuste no Dev — redistribuição dos testes. A Executiva atualizou o prazo.

Sem o protocolo, o Dev teria sido culpado por um problema que nasceu no Design.

---

## 5. Modelo de Elemento

Todo elemento do projeto possui 3 operários obrigatórios, cada um representando sua base, garantindo que todas as bases conheçam e tenham perspectiva sobre todos os elementos. Mesmo que não haja nada a documentar no momento, o operário está presente com N/A. Quando o elemento evoluir, o operário já tem seu lugar reservado.

**Elemento** é tudo que existe no projeto — sistemas, personagens, lugares, facções, mecânicas, conceitos.

```
## Elemento: [Nome]

🏛️🏢 Executiva
[Relevância para o escopo — faz parte do core? É essencial? É secundário?]

🏛️🎨 Design
[Por que existe, qual sua função, lore, identidade visual, experiência]

🏛️🛠️ Dev
[Atributos, componentes, classes, algoritmos, estrutura técnica]
```

---

## 6. Fluxo de Decisão e Iniciativa

### 6.1 Critério de Entrada

Quando um novo elemento ou sistema é proposto, as 3 bases avaliam sob sua perspectiva antes de qualquer implementação:

- 🏛️🏢 **Executiva** — faz parte do escopo? Está alinhado com a visão do projeto?
- 🏛️🎨 **Design** — como integra na identidade? Como mantém a experiência do projeto?
- 🏛️🛠️ **Dev** — como modularizar? Precisa de novo algoritmo ou estrutura?

As 3 precisam concordar. Se uma rejeita, não entra.

### 6.2 Fluxo de Iniciativa

A Executiva inicia. Design e Dev se adaptam dentro de seus domínios com autonomia.

A Executiva define **intenção**, não implementação. Quanto mais específica ela for, menos autonomia sobra para as outras bases — e mais chance de invadir um domínio alheio.

```
Executiva lança intenção
       ↓
Design resolve dentro do seu domínio
Dev resolve dentro do seu domínio
       ↓
Se necessário, devolvem para ajuste
```

**As bases podem devolver quando:**

- A Executiva invadiu o domínio delas — foi específica demais ou tomou uma decisão que não lhe pertence
- O que foi pedido é tecnicamente impossível ou inviável — limitação real de software ou hardware

**Exemplo:**

_"Quero que o jogador apareça e lute contra um dragão"_

O Design devolve — um dragão no início é impossível de vencer. O Design propõe: reduzir a força do dragão progressivamente, ou criar seres intermediários antes do confronto. O Executivo escolhe a direção. O Design implementa.

### 6.3 Limites de Escopo da Executiva

A Executiva define o teto — orçamento, prazo, intenção. Design e Dev decidem como chegar lá.

**Correto:** _"Quero um jogo acessível financeiramente para desenvolver"_ → Design escolhe Blender. Dev escolhe Godot.

**Incorreto:** _"Quero um dragão no nível 1 em 2026"_ → Executiva definiu nível — domínio do Design. Design devolve.

A Executiva que restringe demais engessa o projeto. A que define bem libera as outras bases para trabalhar com autonomia e criatividade.

---

## 7. Arsenal

Em projetos grandes, nem tudo precisa ser analisado pelas 3 bases. Forçar os 3 operários em componentes puramente técnicos, visuais ou estratégicos geraria ruído — bases sendo convocadas para opinar sobre algo fora do seu domínio, sem nada a contribuir.

O Arsenal resolve isso. Cada base possui seu próprio catálogo de componentes exclusivos — criados, mantidos e utilizados dentro do seu domínio.

**Elemento** — tudo que existe no projeto. Sempre com os 3 operários.
**Componente de Arsenal** — bloco reutilizável exclusivo de uma base. Utilizado para compor elementos.

Componentes do Arsenal são criados pela base que os possui e referenciados nos elementos quando necessário.

---

## 8. Representação Visual

O framework pode ser representado por um triângulo equilátero. Dentro dele, o **Elemento** — tudo que é analisado pelas 3 bases em conjunto. Cada vértice representa uma base. De cada vértice parte uma linha para fora do triângulo, conectando à caixa de **Arsenal** daquela base.

![[Pasted image 20260314202841.png]]