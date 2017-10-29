=========================
Kooperativní multitasking
=========================

.. |_| unicode:: 0xA0
   :trim:

Kooperativní multitasking je založen na dostatečně rychlém volání jednotlivých úloh za sebou. Každá úloha je nucena po malé chvíli předat kontrolu systému a ten zase spustí jinou úlohu, která se musí spustit atd. Výhodou je jednodušší implementace systému a nižší požadavky na hardware. Nevýhodou je, že chybně naprogramovaná úloha způsobí úplné zastavení systému i |_| ostatních úloh. 
