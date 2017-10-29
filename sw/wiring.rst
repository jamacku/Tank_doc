*******************
Wiring
*******************

Arduino lze programovat v jazyce C nebo C++. Výborným zdrojem informací o programování v jazyce C je :cite:`1989:brodsko` nebo :cite:`2006:kernritch`. Nejjednodušší je ale používat knihovnu :index:`Wiring`. Tato knihovna je při programování Arduina tak rozšířená, že se o ní přestává mluvit jako o knihovně, ale začíná se říkat, že je to vlastní programovací jazyk.

Jako příklad se dají uvést dvě nejdůležitější funkce.

..  code-block:: c

    void setup() {
      //Inicializace
    }

Funkce void `setup()` se volá pouze jednou, a to při připojení napájení k Arduinu. Do této funkce se píší většinou deklarace a nastavení.

..  code-block:: c

    void loop() {
      //Hlavní smyčka
    }

Funkce void `loop()` je funkce, která se volá hned po void `setup()`. Tato funkce běží pořát dokola, dokud má arduino napájení.

Obě výše uvedené funkce musí obsahovat každý program napsaný v jazyce Wiring.
