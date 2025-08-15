Lua III - Tabelas
=================================

**Tempo de Aula:** 1h30min

.. rubric:: Recursos Didáticos

Projetor, quadro branco, computadores.

.. rubric:: Metodologia

- Expositiva.
- Exercícios Guiados em programação e operação da Engine.
- Desafio - Memória Muscular

.. rubric:: Conteúdo Programático

- Navegação na plataforma.
- Aplicação do conceito de tabelas no Defold.
- Exercícios Dinãmicos.

.. rubric:: Descrição

Utilizar os conceitos das aulas anteriores para aplicar no Defold 
com exemplos mais complexos.

.. rubric:: Avaliação

Execução dos exercícios em sala de aula. 

.. code-block:: lua 
    :caption: Exemplo de tabelas

        -- Criando uma caixa vazia
        meu_bau = {}

        -- Colocando coisas dentro
        meu_bau[1] = "Bola"
        meu_bau[2] = "Carrinho"
        meu_bau[3] = "Boneca"
        print(meu_bau[1])  -- Vai mostrar: Bola
        print(meu_bau[3])  -- Vai mostrar: Boneca

.. code-blocks:: lua
    :caption: acesso a dados de tabelas

        personagem = {
            nome = "Luna",
            idade = 10,
            profissao = "Aventureira"
        }

        print(personagem.nome)   -- Luna
        print(personagem.idade)  -- 10

.. raw:: latex

    \newpage
    
.. rubric:: Bibliografia

FOUNDATION, Defold. Defold - Official Homepage - Cross platform game engine. 
Disponível em: <https://defold.com/>. Acesso em: 25 jun. 2025. 

Rabin, S. (n.d.). Introdução ao desenvolvimento de games (Cengage Le, Vol. 1).  
https://www.amazon.com.br/Introdução-desenvolvimento-games-Entendendo-universo/dp/852211143X

Rita, S. (2017). Treinamento em Lógica de Programação (R. Sandra (ed.); Universo d).  
https://br.99ebooks.net/download/treinamento-em-logica-de-programacao/
