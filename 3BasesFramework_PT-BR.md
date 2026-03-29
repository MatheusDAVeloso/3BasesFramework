## Sumário

1. As 3 Bases
    - 1.1 Base Executiva
    - 1.2 Base Design
    - 1.3 Base Dev
2. Estrutura Operacional
    - 2.1 Hierarquia
    - 2.2 Sistema de ícones
    - 2.3 Filosofia de Base e Operário
    - 2.4 Protocolo de comunicação
    - 2.5 Escalabilidade
3. Modelo de Elemento
4. Fluxo de Decisão e Iniciativa
    - 4.1 Critério de Entrada
    - 4.2 Fluxo de Iniciativa
    - 4.3 Limites de Escopo da Executiva
5. Arsenal


---

## 1. As 3 Bases

Cada base possui **soberania absoluta** sobre seu domínio. Nenhuma tem autoridade sobre o domínio da outra. Algo só entra no projeto se atender às 3.

O veto de uma base não é um ato de conflito, é um ato de proteção. Se o Dev veta, está salvando o projeto de um colapso técnico. Se a Executiva veta, está salvando do escopo incontrolável. Se o Design veta, está salvando da perda de identidade.

Cada base trabalha com uma linguagem própria de documentação: a Executiva documenta em **Filosofias**, definindo intenção e não implementação. Design e Dev documentam em **Pilares e Diretrizes**, definindo como implementar. Quanto mais próximo da execução, mais concreto e mensurável.

Quando as bases são bem definidas, tendem a chegar nos mesmos princípios de forma independente, cada uma dentro do seu domínio, sem precisar referenciar as outras. Isso não é coincidência, é sinal de que o projeto tem uma visão central coerente. As bases são sócias, não subordinadas.

Quando não chegam, ou seja, quando o conflito não se resolve, isso é um sinal, não um fracasso. Ou a intenção da Executiva foi mal definida e precisa ser revisada, ou há um desalinhamento estrutural que precisa ser resolvido antes de qualquer implementação. O framework não garante consenso automático. Ele garante que o conflito apareça cedo, quando ainda é barato resolver.

### 1.1 Base Executiva 🏛️🏢

Responsável pelo que o projeto deve ser, ter e quando. Cuida de tudo que é estrutural, burocrático e estratégico: escopo, distribuição, idiomas, RH, relações externas, custos. É a base que separa a organização do público e protege as outras duas do caos operacional.

Documenta em **Filosofias**: define intenção, não implementação.

### 1.2 Base Design 🏛️🎨

Responsável por tudo que guia o usuário e define a experiência: direção de arte, direção de produto, roteiro, modelagem, música, marketing, identidade visual, modelagem, animação. Define a identidade e a sensação que o projeto transmite.

Documenta em **Pilares e Diretrizes**: define como implementar dentro do domínio criativo.

### 1.3 Base Dev 🏛️🛠️

Responsável por toda a infraestrutura técnica do projeto: linguagens, engines, frameworks, arquitetura, design patterns, algoritmos, banco de dados, APIs, plataformas e versionamento. Metodologias ágeis como Scrum vivem dentro desta base, no subdomínio de gerenciamento de projeto. Não substitui o Scrum, complementa.

Documenta em **Pilares e Diretrizes**: define como implementar dentro do domínio técnico.

---

## 2. Estrutura Operacional

### 2.1 Hierarquia
Cada base possui uma liderança e operários. Os operários são especialistas dentro do domínio de sua base: UX, roteiristas e animadores são operários do Design; front-end, back-end e QA são operários do Dev; RH e administrativo são operários da Executiva.

**Liderança**: toma decisões de base, representa a perspectiva nos conflitos entre bases.

**Operário**: aplica os princípios da sua base dentro dos elementos do projeto sem questionamento. Onde a base não especifica, o operário tem liberdade criativa.

O framework assume líderes competentes como pré-requisito. Não porque seja ingênuo, mas porque nenhum sistema resolve incompetência estrutural. O que o framework faz é dividir o poder em 3, reduzindo o impacto de um líder ruim e impedindo que uma perspectiva domine as outras. Um líder fraco numa base enfraquece aquela base. Três bases independentes são mais resilientes que uma hierarquia centralizada.

### 2.2 Sistema de ícones
O 🏛️ indica que algo é um princípio de base, uma decisão que governa e não é questionada pelos operários.

```
🏛️🏢 — princípio da Base Executiva
🏛️🎨 — princípio da Base Design
🏛️🛠️ — princípio da Base Dev
```

Sem 🏛️, significa decisão de operário. Liberdade criativa dentro do domínio da sua base.

### 2.3 Filosofia de Base e Operário

**Base não é cargo, é filosofia**

A Base não é uma pessoa, não é um título, não é um departamento. É uma filosofia que governa um domínio e pode ser composta por quantas pessoas forem necessárias.

Em um time pequeno, Dev Júnior, Dev Pleno e Tech Lead fazem de tudo um pouco, e não há nada de errado nisso, todos fazem parte da Base Dev. Os operários são as subseparações de responsabilidade, escopo e conhecimento dentro da base. Um PO, apesar de trabalhar como ponte entre produto e tecnologia, é operário da Base Dev, pois o Scrum vive dentro do Dev, não da Executiva. A estrutura organizacional e a estrutura do framework são camadas independentes e não se contradizem.

Quando vai para a hierarquia da empresa, Tech Lead é superior a Dev Pleno, que é superior a Dev Júnior. No framework, todos são operários da mesma base. Não há contradição, já que são sistemas diferentes operando em paralelo.

**A Base como consciência, não como chefe**

As 3 Bases funcionam como uma mente única dividida em três. Em uma mente saudável, o lado lógico não manda no criativo. Eles negociam. Quando as 3 Bases travam e não chegam a um acordo, isso não é um problema de poder, é um sinal de que a intenção da Executiva foi mal definida. Ela volta para redefinir, não para impor. O framework não tem desempatador hierárquico porque não precisa: bases que compartilham a mesma visão central chegam ao mesmo lugar por caminhos diferentes.

Cada base é suficientemente inteligente para entender a visão do projeto e se adaptar dentro do seu domínio sem precisar de instrução constante. sem precisar referenciar as outras. Sócias compartilham visão, não dependência.

**Por que o operário segue a base**

Os operários seguem a base não por obediência cega, mas por confiança estrutural. A base foi construída com as 3 perspectivas em mente, não só a do próprio domínio. Quando um operário olha para a documentação da sua base, está olhando para algo que já passou pelo crivo das outras duas. Ele não precisa ler a documentação do RH. Ele só precisa seguir a sua base, porque a base já fez esse trabalho por ele.

**Imunidade diplomática do operário**

Nenhuma base tem autoridade sobre o operário de outra base. A Base Executiva não pode chegar em um Dev Júnior e dizer "isso está demorando demais", porque ela não sabe se aquela demora é um débito técnico sendo pago ou algo que está salvando a infraestrutura do projeto. Ela pode elogiar um débito técnico irrevogável ou vetar algo que está salvando o projeto.

Conflito cross-domain sobe. Sempre. Um operário Dev não responde à Base Executiva. O problema vai ao Líder Dev, que leva às bases, que resolvem com visão geral.

As bases são o sistema nervoso central. Os operários são os membros. O cérebro não tenta fazer o trabalho do membro e o membro não questiona o cérebro. Cada um no seu domínio, todos movendo o mesmo corpo.

### 2.4 Protocolo de Comunicação

Operários não se comunicam diretamente com operários de outras bases. Todo conflito ou necessidade de alinhamento sobe ao líder da própria base.

```
Operário A (Design) → Líder Design → Líder Executiva → Operário B (Executiva)
```

Isso não é burocracia, é um mecanismo de propagação. Quando um problema sobe de um operário até os líderes, ele automaticamente passa pelas 3 perspectivas. A solução não volta só para quem reportou, ela é redistribuída para toda a infraestrutura. Cada base se adapta dentro do seu domínio.

Um problema que nasce num operário nunca deve morrer nele. Se chegou aos líderes, todas as bases já sabem.

Em times pequenos, onde as mesmas pessoas acumulam responsabilidades de bases diferentes, comunicação direta é natural e esperada. O que não muda é o princípio: decisões que afetam mais de uma base sobem. Na prática, isso não exige documentação formal, basta avisar quem trabalha junto sobre a mudança. O que importa é que a informação chegue, não o canal pelo qual chegou.

**Exemplo real:**

O RH percebe que o dev front-end está demorando muito para entregar telas e reporta ao Líder Executivo.

O Líder Executivo conversa com o Líder Dev. O Líder Dev já conhece a situação internamente: o front-end está sobrecarregado, o QA mal consegue acompanhar o volume de testes por causa da quantidade de rotas e fluxos. O problema não está no front-end. Está em outro lugar.

O Líder Dev convoca os 3 líderes.

Com as 3 perspectivas na mesa:

- **Executiva** — o prazo está comprometendo o escopo?
- **Design** — o fluxo de rotas e UX está complexo demais?
- **Dev** — o front-end tem suporte de QA suficiente?

A causa raiz emerge: o Design havia criado um fluxo de rotas com complexidade desnecessária, sobrecarregando front-end e QA em cascata.

A solução exigiu reestruturação no Design com a simplificação do fluxo, e ajuste no Dev com a redistribuição dos testes. A Executiva atualizou o prazo.

Sem o protocolo, o Dev teria sido culpado por um problema que nasceu no Design.

### **2.5 Escalabilidade**

O framework é um guia, não uma ditadura. Nem o Scrum é seguido à risca e ele funciona. A estrutura de liderança se adapta ao tamanho e ao contexto do time. O que não muda são os princípios: soberania de domínio, veto como proteção, comunicação que sobe e solução que desce distribuída.


---

## 3. Modelo de Elemento

**Elemento** é tudo que existe no projeto: sistemas, personagens, lugares, facções, mecânicas, conceitos, funcionalidades.

Todo elemento possui 3 operários obrigatórios, cada um representando sua base, garantindo que todas as bases conheçam e tenham perspectiva sobre todos os elementos. Mesmo que não haja nada a documentar no momento o operário está presente com `N/A`, para quando o elemento evoluir, o operário já tem seu lugar reservado.

```markdown
## Elemento: [Nome]

🏛️🏢 Executiva
[Relevância para o escopo — faz parte do core? É essencial? É secundário?]

🏛️🎨 Design
[Por que existe, onde existe, qual sua função, lore, identidade visual, experiência]

🏛️🛠️ Dev
[Atributos, componentes, classes, algoritmos, estrutura técnica]
```

---

## 4. Fluxo de Decisão e Iniciativa

### 4.1 Critério de Entrada

Quando um novo elemento ou sistema é proposto, as 3 bases avaliam sob sua perspectiva antes de qualquer implementação:

- 🏛️🏢 **Executiva** — faz parte do escopo? Está alinhado com a visão do projeto?
- 🏛️🎨 **Design** — como integra na identidade? Como mantém a experiência do projeto?
- 🏛️🛠️ **Dev** — como modularizar? Precisa de novo algoritmo ou estrutura?

As 3 precisam concordar. Se uma rejeita, não entra.

### 4.2 Fluxo de Iniciativa

A Executiva inicia. Design e Dev se adaptam dentro de seus domínios com autonomia.

A Executiva define **intenção**, não implementação. Quanto mais específica ela for, menos autonomia sobra para as outras bases e mais chance de invadir um domínio alheio.

Design e Dev não são apenas receptores, são sócias. Dentro do espaço definido pela Executiva, podem propor, explorar e até desafiar a intenção inicial. Se uma proposta de Dev ou Design exige revisão do escopo, ela sobe para as bases como qualquer outro conflito. A Executiva avalia, redefine se necessário, e o fluxo continua.
	
```
Executiva lança intenção
       ↓
Design resolve dentro do seu domínio
Dev resolve dentro do seu domínio
       ↓
Se necessário, devolvem para ajuste
```

**As bases podem devolver quando:**

- A Executiva invadiu o domínio delas, foi específica demais ou tomou uma decisão que não lhe pertence
- O que foi pedido é tecnicamente impossível ou inviável: limitação real de software ou hardware

**Exemplo:**

_"Quero que o jogador apareça e lute contra um dragão"_

O Design devolve: um dragão no início é impossível de vencer. O Design propõe: reduzir a força do dragão progressivamente, ou criar seres intermediários antes do confronto. O Executivo escolhe a direção. O Design implementa.

### 4.3 Limites de Escopo da Executiva

A Executiva define o teto: orçamento, prazo, intenção. Design e Dev decidem como chegar lá.

**Correto:** _"Quero um jogo acessível financeiramente para desenvolver"_ → Design escolhe Blender. Dev escolhe Godot.

**Incorreto:** _"Quero um dragão no nível 1 em 2026"_ → Executiva definiu nível, domínio do Design. Design devolve.

A Executiva que restringe demais engessa o projeto. A que define bem libera as outras bases para trabalhar com autonomia e criatividade.

---

## 5. Arsenal

Em projetos grandes, nem tudo precisa ser analisado pelas 3 bases. Forçar os 3 operários em componentes puramente técnicos, visuais ou estratégicos geraria ruído, bases sendo convocadas para opinar sobre algo fora do seu domínio, sem nada a contribuir.

O Arsenal resolve isso. Cada base possui seu próprio catálogo de componentes exclusivos, criados, mantidos e utilizados dentro do seu domínio.

**Elemento**: tudo que existe no projeto. Sempre com os 3 operários.

**Componente de Arsenal**: bloco reutilizável exclusivo de uma base. Utilizado para compor elementos.

Componentes do Arsenal são criados pela base que os possui e referenciados nos elementos quando necessário.
