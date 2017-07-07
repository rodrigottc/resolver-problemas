# resolver-problemas
Apostila com exercícios e problemas de Cálculo Numérico. Segue a ideia de George Polya.

O arquivo principal é o "livro com questões.tex", que está na pasta "Livro". 

O único pacote não usual que foi carregado é o answers. Este pacote serve para criar o apêndice com as soluções. O uso é simples: use o ambiente {ex} para criar um exercício e, dentro deste ambiente, crie o ambiente {sol} para escrever a solução.

Exemplo:

\begin{ex}
  Qual é a cor do cavalo branco de Napoleão?
  \begin{sol}
    Preto.
  \end{sol}
\end{ex}

O livro está "organizado" (aspas propositais) de modo que os exercícios estão em arquivos .tex separados, supostamente divididos por tema. Infelizmente, na maior parte das vezes, essa separação não acontece. Seja atento. Meus planos futuros envolvem organizar de fato os exercícios por tema em arquivos .tex e criar também um .tex por capítulo que contenha somente os "Exercícios Problema".
