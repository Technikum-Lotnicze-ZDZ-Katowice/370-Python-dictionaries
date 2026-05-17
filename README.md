# 370-Python-dictionaries


1. Przykład słownika:
 
```python
auto = {
  "marka": "Ford",
  "model": "Mustang",
  "rok": 1964
}

#tworzenie słownika
auto2 = dict(marka = "Opel", model = "Corsa", rok = 2000)
```
2. dostęp do pól słownika

```python
print(auto["marka"],auto["model"],"z roku:",auto["rok"])
```

3. Odczyt z pliku
   
```python
f = open("demofile.txt")
print(f.read())
```
4. Zapis do pliku

tryby "x" - create, "a" - append, "w" - write/overwrite)

```python
with open("demofile.txt", "w") as f:
  f.write("Woops! I have deleted the content!")
```

5. Generator liczb losowych
```python
import random
---
print(random.random())   # randrange(a,b), randint(a,b), choice(), shuffle(),
```

```python
import random
---
liczby = [1,2,3,4,5,6]
liczby.shuffle()
---
```

#### ZAD37001.
Przygotuj program pobierający dane od uzytkownika i tworzący bazę danych (listę) z samochodami (użyj słowników). 

Wypisz zawartość bazy w następującej formie:
```
W naszym salonie samochodowym mamy następujące auta:
- Opel Corsa (rocznik 2006) - kolor: czerwony;
- Ford Capri (rocznik 2010) - kolor: zielony;
- Subaru Impreza (rocznik 2017) - kolor: czarny;
```
#### ZAD37002
Przygotuj bazę danych osobowych w pliku tekstowym i załaduj ją do aplikacji która wyświetla wybrany zakres informacji o osobach (zastosuj format CSV):
1. Wyświetl pełne rekordy
2. Wyświetl tylko imię i nazwiska
3. Szukaj

#### ZAD37003
Zmodyfikuj zadanie ZAD37001 tak, aby dane samochodów były zapisywane do pliku w formacie CSV

#### ZAD37004
Przygotuj program pracujący w dwóch trybach:
1. Dodawanie pytań
2. Odpytywanie z pytań
   

### Info
https://www.w3schools.com/python/python_dictionaries.asp

