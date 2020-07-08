---
id: 56533eb9ac21ba0edf2244b7
title: Concatenating Strings with Plus Operator
challengeType: 1
videoUrl: ''
localeTitle: Concatenando Strings com Operador Plus
---

## Description
<section id="description"> Em JavaScript, quando o operador <code>+</code> é usado com um valor <code>String</code>, ele é chamado de operador de <dfn>concatenação</dfn>. Você pode construir uma nova string a partir de outras strings, <dfn>concatenando-as</dfn>. <strong>Exemplo</strong> <blockquote> &#39;Meu nome é Alan,&#39; concordo &#39;. </blockquote> <strong>Nota</strong> <br> Cuidado com os espaços. A concatenação não adiciona espaços entre as sequências concatenadas, portanto, você mesmo precisará adicioná-las. </section>

## Instructions
<section id="instructions"> Construa <code>myStr</code> partir das strings <code>&quot;This is the start. &quot;</code> E <code>&quot;This is the end.&quot;</code> usando o operador <code>+</code>. </section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>myStr</code> deve ter um valor igual a este <code>This is the start. This is the end.</code>
    testString: 'assert(myStr === "This is the start. This is the end.", "<code>myStr</code> deve ter um valor igual a este <code>This is the start. This is the end.</code>");'
  - text: Use o operador <code>+</code> para contatenar <code>myStr</code>
    testString: 'assert(code.match(/([""]).*([""])\s*\+\s*([""]).*([""])/g).length > 1, "Use the <code>+</code> operator to build <code>myStr</code>");'
  - text: <code>myStr</code> deve ser criado usando a keyword <code>var</code> .
    testString: 'assert(/var\s+myStr/.test(code), "<code>myStr</code> deve ser declarada usando a <code>var</code> keyword.");'
  - text: Certifique-se de atribuir um resultado à variável <code>myStr</code> .
    testString: 'assert(/myStr\s*=/.test(code), "Certifique-se de atribuir um resultado à variável <code>myStr</code>.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
// Example
var ourStr = "I come first. " + "I come second.";

// Only change code below this line

var myStr;

```

</div>


### After Test
<div id='js-teardown'>

```js
console.info('after the test');
```

</div>

</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
