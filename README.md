## Desafio

Anagramas Um anagrama é uma palavra ou frase formada com o re-arranjo de todas as letras de uma outra palavra ou frase (sem sobra ou falta). Exemplos:
- A palavra barco é um anagrama da palavra cobra (todas as letras de “cobra” usadas em “barco).
- A palavra mar não é um anagrama da palavra roma (a letra “o” em “roma” não foi usada).
- A palavra sal não é um anagrama da palavra mal (a letra “s” de “sal” não existe em “mal”).

------

#### Exemplos de busca por anagramas

Busca | Resultados | Anagramas
--------- | ------ | ------
amor      | 5 anagramas | a, am, or, ramo, mao
vermelho  | 6 anagramas | he, hee, heel, helm, holm, or
alexa     | 3 anagramas | a, ale, alex
oh        | 0 anagramas | Não foram encontrados anagramas correspondentes... 

------

### Como o algoritmo funciona

O algoritmo é muito simples!<br>
As palavras <i>marca</i> e <i>carma</i> são anagramas, ordenadas de forma alfabética se tornam iguais:

Palavra   | Chave ordenada
---------  | ------ 
marca      | aacmr
carma      | aacmr 

Ou seja, cria-se um dicionário tratando as palavras que são anagramas pertencendo a mesma chave e na busca por um anagrama, o algoritmo se torna extremamente rápido por procurar apenas pelo seu anagrama ordenado.


### Contribuições

Contribuições são sempre muito bem vindas!