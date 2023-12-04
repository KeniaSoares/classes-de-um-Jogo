# Heroi - Jogo de Aventura

Este é um simples código em JavaScript que implementa a classe Heroi para representar um herói em um jogo de aventura. A classe possui propriedades como **nome**, **idade** e **tipo**, além do método **atacar** que simula um ataque do herói com base no seu tipo.

# Funcionalidades

Construtor:
  
   constructor(nome, idade, tipo): Inicializa um novo herói com um nome, idade e tipo específicos.

# Método de Ataque:

atacar(): 
   
   Simula um ataque do herói, exibindo uma mensagem de acordo com o tipo do herói e o tipo de ataque.

# Tipos de Heróis e Ataques

A tabela a seguir mostra os tipos de heróis disponíveis e os tipos de ataques associados:

Mago: usa magia

Guerreiro: usa espada

Monge: usa artes marciais

Ninja: usa shuriken

Se o tipo do herói não estiver entre os mencionados, ele usará um ataque genérico.

# Exemplo de Uso

  ```const guerreiro = new Heroi('Arthur', 30, 'guerreiro');  ```
  ```guerreiro.atacar();  ```  

Este exemplo cria um herói guerreiro chamado Arthur, com 30 anos de idade, e realiza um ataque exibindo a mensagem correspondente.

# Saída Esperada

A saída esperada para o exemplo acima seria algo como:

    . O guerreiro Arthur atacou usando espada

Isso demonstra como a classe Heroi pode ser utilizada para representar heróis em um jogo de aventura, exibindo mensagens de ataque personalizadas com base no tipo do herói.
