# Zadanie 1

Dodaj do klasy ``Punkt`` z projektu ``01Punkt``:
- metod� klasy ``Punkt`` wyliczaj�c� odleg�o�� punktu od pocz�tku uk�adu wsp�rz�dnych
- metod� klasy ``Punkt`` z parametrem typu ``Punkt`` wyliczaj�c� odleg�o�� punktu posiadaj�cego 
metod� od punktu, kt�ry jest parametrem metody
- metod� klasy ``Punkt`` z dwoma parametrami typu ``Punkt``, sprawdzaj�c� czy punkty tworz� tr�jk�t

# Zadanie 2

Twoja firma opracowuje program dla banku. Twoim zadaniem jest stworzenie i przetestowanie klasy ``Konto``. 
Klasa ``Konto`` posiada nast�puj�ce pola:
- ``wlasciciel``: typu ``Osoba`` (Imie i Nazwisko)
- ``saldo``: typu ``decimal``
- ``pin``: typu ``int``

## Wskaz�wki
1. Pola ``saldo`` i ``pin`` powinny by� zainicjalizowane warto�ci� zero. 
2. Pole ``pin`` mo�na zmieni� tylko podaj�c obecn� warto�� pola. 
3. Wyp�at� z konta (zmniejszenie warto�ci pola ``saldo``) mo�na uzyska� tylko po podaniu prawid�owego pinu. 
4. Na koncie nie wolno zrobi� debetu. 
5. Dodaj metod�, kt�ra zwraca informacje o koncie, oczywi�cie pod warunkiem, �e zosta� podany prawid�owy pin.
