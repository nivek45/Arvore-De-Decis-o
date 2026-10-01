# Árvore de decisão

Aplicação simples em HTML, CSS e JavaScript para comparar alternativas de compra com dois cenários: sol e chuva. Os dados iniciais reproduzem o exemplo da aula.

## Como usar

Abra `dist/index.html` no navegador. Altere as chances, o custo e a receita de cada alternativa. Também é possível adicionar ou remover alternativas. O resultado muda automaticamente.

O cálculo de cada cenário é `lucro = receita - custo`. Para cada alternativa:

`valor esperado = lucro no sol × chance de sol / 100 + lucro na chuva × chance de chuva / 100`

As chances devem somar 100%. A aplicação destaca a alternativa com o maior valor esperado, inclusive quando o resultado esperado é negativo ou há empate.

No exemplo inicial, os valores esperados são R$ 28,00 (20 kg), R$ 33,60 (40 kg), R$ 22,40 (60 kg) e -R$ 14,00 (80 kg). A melhor opção é a compra de 40 kg.

Não há dependências, instalação ou servidor obrigatórios.
