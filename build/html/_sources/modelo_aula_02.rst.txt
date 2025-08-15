Introdução ao Defold
==============================

Aula sobre Engine Defold
--------------------------

**Tempo de Aula:** 1h30min

.. rubric:: Recursos Didáticos

Projetor, quadro branco, computadores.

.. rubric:: Metodologia

- Expositiva.
- Exercícios Guiados em programação e operação da Engine.
- Estimulo a participação.

.. rubric:: Objetivos

- Compreender conceitos básicos que estão por trás da criação de jogos.
- Aplicar na prática alteração e criação de partes de um projeto.
- Desenvolver curiosidade e autonomia e raciocínio lógico.

.. rubric:: Conteúdo Programático

**Ambientação**

- Estrutura de um projeto 
- Revisão conceitos(Sprites, Tilesource, TileMaps)

**Estudo de Caso**

- Analise Projeto simples

**Aplicação dos conceitos**

- Criando personagem e cenários e adicionando ao projeto.
- Momento para criar, desenhar personagens.


.. rubric:: Descrição

No decorrer dessa aula será exposto conceitos e um projeto como estudo de caso, os alunos poderão interagir
e alterar e adicionar funcionalidades ao projeto. A ideia dessa aula é deixar as crianças a vontade para 
alterar e brincar com a ferramenta. Deve-se apresentar a documentação aos alunos de uma maneira bem dinâmica,
exemplos de códigos na linguagem lua, podendo-se alternar os exemplos de código na Engine Defold e VSCODE.

.. code-block:: lua
    :caption: Exemplo exibição na tela com a função io.write.

        io.write("\nNaruto \n")
        io.write("Full Metal Alchemist \n")
        io.write("Dragon Ball \n")
       

Da mesma forma é possível utilizar a função print para poder ver no terminal alguma informaçãO

.. code-block:: lua
    :caption: Exemplo exibição na tela com a função Print.

        print("\nNaruto \n")
        print("Full Metal Alchemist \n")
        print("Dragon Ball \n")

Após os Alunos terem um entendimento básico da Engine podese aprofundar no entendimento de alguns conceitos 
ja plicando na Engine:

.. code-block:: lua 
    :caption: Exemplo de variáveis

        VIDA_PLAYER = 100
        VIDA_INIMIGO = 100

        DANO_PLAYER = 20
        DANO_INIMIGO = 15

        local ataque_player = VIDA_INIMIGO - DANO_PLAYER
        local ataque_inimigo = VIDA_PLAYER - DANO_INIMIGO

        print("Vida do Player: " .. VIDA_PLAYER)
        print("Vida do Inimigo: " .. VIDA_INIMIGO)

        print("após os ataques:")

        print("Vida do Player: " .. ataque_player)
        print("Vida do Inimigo: " .. ataque_inimigo)



.. raw:: latex

    \newpage

Exercício Aula 2 - Introdução ao Defold 
-------------------------------------------

Data: ___/___/___

**Faça os exercícios:**

- 1 – Utilize os sprites de personagem, para importar para o Defold com as devidas configurações, anime o personagem, nos modos andando e parado.
- 2 – Anime e configure o personagem com os comandos para direita e para a esquerda.
- 3 – Crie um personagem animado com libresprite salve os arquivos e importe para o seu projeto.


.. raw:: latex

    \newpage



.. rubric:: Bibliografia

FOUNDATION, Defold. Defold - Official Homepage - Cross platform game engine. 
Disponível em: <https://defold.com/>. Acesso em: 25 jun. 2025. 

Rabin, S. (n.d.). Introdução ao desenvolvimento de games (Cengage Le, Vol. 1).  
https://www.amazon.com.br/Introdução-desenvolvimento-games-Entendendo-universo/dp/852211143X

Rita, S. (2017). Treinamento em Lógica de Programação (R. Sandra (ed.); Universo d).  
https://br.99ebooks.net/download/treinamento-em-logica-de-programacao/
