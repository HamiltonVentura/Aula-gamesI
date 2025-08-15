Linguagem Lua I - variáveis e condições
==============================

**Tempo de Aula:** 1h30min

.. rubric:: Recursos Didáticos

Projetor, quadro branco, computadores.

.. rubric:: Metodologia

- Expositiva.
- Exercícios Guiados em programação e operação da Engine.
- Estimulo a participação.
- Desafio.

.. rubric:: Objetivos

- Compreender conceitos da linguagem de programação lua e aplicar na engine.
- Operadores aritméticos
- if e else 
- variáveis
- Desenvolver curiosidade e autonomia e raciocínio lógico.

.. rubric:: Conteúdo Programático

- Programar teclas/Clicks para que o programa reconheça os comandos.
- Animar personagem. 
- Entender conceito de variável e função.

.. rubric:: Descrição

Deve-se gastar pelo menos 20 a 30 minutos reforçando os conteúdos com alguns
exercícios na linguagem lua. Essa aula pode ser utilizada para focar exclusivamente nas funções e 
conceitos da linguagem lua.

.. code-block:: lua 
    :caption: Exemplo de Entrada

        print("Digite o jogo de celular:")
        nome = io.read()
        print("Digite a nota")
        nota = io.read()
        print("digite a descricao")
        descricao = io.read()
        print("O nome do jogo e :",nome, " e a nota dele e ",nota)
        print("Descricao : ",descricao)

.. code-block:: lua 
    :caption: Exemplo de variáveis

        local idade = 20

        if idade >= 18 then
            print("Você é maior de idade.")
        else
            print("Você é menor de idade.")
        end

.. code-block:: lua 
    :caption: Exemplo operadores

        local idade = 20

        if idade ~= 18 then
            print("Você é maior de idade.")
        else
            print("Você é menor de idade.")
        end

.. code-block:: lua 
    :caption: Exemplo de operadores aritméticos

        local idade = 20
        local nome = "Seu nome"

        if idade >= 18 then
            print("Você é maior de idade.",nome)
        else
            print("Você é menor de idade.",nome)
        end

.. raw:: latex

    \newpage

.. rubric:: Bibliografia

FOUNDATION, Defold. Defold - Official Homepage - Cross platform game engine. 
Disponível em: <https://defold.com/>. Acesso em: 25 jun. 2025. 

Rabin, S. (n.d.). Introdução ao desenvolvimento de games (Cengage Le, Vol. 1).  
https://www.amazon.com.br/Introdução-desenvolvimento-games-Entendendo-universo/dp/852211143X

Rita, S. (2017). Treinamento em Lógica de Programação (R. Sandra (ed.); Universo d).  
https://br.99ebooks.net/download/treinamento-em-logica-de-programacao/

