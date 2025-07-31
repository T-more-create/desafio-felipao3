## Escrevendo as classes de um Jogo


### O que foi utilizado

- Variáveis  
- Operadores  
- Laços de repetição  
- Estruturas de decisões  
- Funções  
- Classes e Objetos  

---

## Objetivo

Crie uma **classe genérica** que represente um herói de uma aventura, com as seguintes propriedades:

- `nome`  
- `idade`  
- `tipo` (ex: guerreiro, mago, monge, ninja)  

Além disso, a classe deve ter um método chamado `atacar` que atenda aos seguintes requisitos:

- Exibir a mensagem:  
  `"o {tipo} atacou usando {ataque}"`  
- Onde:  
  - `{tipo}` é o valor da propriedade `tipo` da classe.  
  - `{ataque}` deve ser uma descrição diferente conforme o tipo, seguindo a tabela abaixo:

| Tipo       | Ataque                 |
|------------|------------------------|
| mago       | usou magia             |
| guerreiro  | usou espada            |
| monge      | usou artes marciais    |
| ninja      | usou shuriken          |

---

## Saída esperada:

Ao final da execução do método `atacar`, deve ser exibida a mensagem:


Exemplos:  
- `mago atacou usando usou magia`  
- `guerreiro atacou usando usou espada`  

