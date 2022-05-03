# Zadanie 1

Do projektu ``Zoo`` dodaj klas� ``SmokWawelski``, 
klasa powinna implementowa� podobne metody do zaimplementowanych w klasie ``Wilk``.
Zaadoptuj klas� ``SmokWawelski`` (podobnie jak zrobiono to w przypadku klasy ``Wilk``) 
i dodaj do fabryki oraz menu programu g��wnego.

# Zadanie 2

Napisz klas� ``Towar`` posiadaj�c� publiczne pola: 
``Nazwa``, ``Cena`` oraz ``Ilo��`` 
i wirtualn� metod� ``Opis`` wy�wietlaj�c� na standardowym wyj�ciu wszystkie informacje 
przechowywane w obiekcie.

Zaimplementuj nast�puj�ce klasy pochodne klasy ``Towar``:
- ``Gwozdzie``: posiadaj�ca dodatkowe publiczne pola ``D�ugo��``, ``Grubo��`` i ``Rodzaj�epka``
- ``PapierScierny``: posiadaj�ca dodatkowe publiczne pola ``Ziarnisto��`` i ``Szeroko��``
- ``Mebel``: posiadaj�ca dodatkowe publiczne pole ``NazwaKolekcji``.
Wszystkie klasy pochodne klasy ``Towar`` powinny mie� przeci��on� metod� ``Opis``.

Zaimplementuj klas� ``Szafa`` pochodn� klasy ``Mebel``. 
Klasa ``Szafa`` powinna posiada� publiczne pola ``Wysoko��``, ``Szeroko��`` i ``G��boko��``. 
Metoda ``Opis`` powinna zosta� przeci��ona w taki spos�b, 
�eby wykorzysta� kod metody ``Opis`` z klas bazowych.

Przetestuj swoje rozwi�zanie.
