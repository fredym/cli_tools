cli_tools
=========

There are some simple tasks I do very often but for which there is no command
line tool yet available so I just create one and add it here. These tools are
designed for **OS X**.


**Depends on:**

  - Xcode Command Line Tools `xcode-select --install`
  - [brew]


**Installation**

Just clone this repo and add it to your `PATH`

    $ cd
    $ git clone https://github.com/fredym/cli_tools.git
    $ echo 'PATH="$HOME/cli_tools:$PATH"' >> ~/.bash_profile




drae
----

Searches the term specified in the first argument in the _Diccionario de la Real
Academia Española_. As an Spanish native speaker this comes in handy when doing
some writing.

**Depends on:** [lynx]

    $ brew install lynx

**Usage example**

    $ drae diccionario
        diccionario.

        Del b. lat. dictionarium.

        1. m. Repertorio en forma de libro o en soporte electrónico en el que
        se recogen, según un orden determinado, las palabras o expresiones de
        una o más lenguas, o de una materia concreta, acompañadas de su
        definición, equivalencia o explicación.

        2. m. Catálogo de noticias o datos de un mismo género, ordenado
        alfabéticamente. Diccionario bibliográfico, biográfico, geográfico.

        Real Academia Española © Todos los derechos reservados




[lynx]: http://lynx.invisible-island.net/
[brew]: http://brew.sh/
