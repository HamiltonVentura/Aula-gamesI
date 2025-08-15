Linguagem Lua II - laços de repetição
================================

**Tempo de Aula:** 1h30min

.. rubric:: Recursos Didáticos

Projetor, quadro branco, computadores.

.. rubric:: Metodologia

- Expositiva.
- Exercícios Guiados em programação e operação da Engine.
- Desafio - Memória Muscular

.. rubric:: Conteúdo Programático

- Utilização de funções da Linguagem Lua.
- Utilização de variáveis, laços e condições.
- Utilização de Tabelas.

.. rubric:: Descrição

Para Os Alunos internalizarem bem como é fluxo de funcionamento do Defold com relação aos
escripts, Serão entregues exercícios que ja utilizam de determinadas funções do próprio Defold.

.. Nesse caso vou ter que desenvolver os exercíciso de maneira gradual para não assustar.

.. code-block:: lua 
    :caption: Exemplo de laço for

        for i=0, 10 do 
        print("status",i)
        end

.. code-block:: lua 
    :caption: Exemplo de laço while

        local i = 1

        while i <= 5 do
            print(i)
            i = i + 1
        end

.. code-block:: lua 
    :caption: Exemplo de função

        function idade(d)
            print(d)
        end
        idade(20)

.. raw:: latex

    \newpage

.. rubric:: Bibliografia

SCIRRA, L. (2022). Manual Construct.  
https://www.construct.net/en/make-games/manuals/construct-3

Rabin, S. (n.d.). Introdução ao desenvolvimento de games (Cengage Le, Vol. 1).  
https://www.amazon.com.br/Introdução-desenvolvimento-games-Entendendo-universo/dp/852211143X

Rita, S. (2017). Treinamento em Lógica de Programação (R. Sandra (ed.); Universo d).  
https://br.99ebooks.net/download/treinamento-em-logica-de-programacao/
