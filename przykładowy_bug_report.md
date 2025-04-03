# Raport o blędzie

## Numer / identyfikator błędu
1. 03041001
2.0304002
3.0304003
4.0304004
## Tytuł błędu
1. literówka
2.błędna zmienna number
3.błędne łączenie zmiennych (numbers)

## Priorytet
1.critical
2.critical
3.critical


## Platforma / środowisko
1.Pycharm
2.Pycharm
3.Pycharm

## Opis
1. powinno byc random.sample a nie random.samplef
2. powinno byc numbers bo tak wczesniej zostala zadeklarowana ta zmienna
3. powinno byc all=lower + upper + numbers + symbols czyli poprawne wpisanie numbers zamiast number

## Kroki do reprodukcji
1. wpisac  random.samplef zamiast random_sample
2. wpisac number zamiast numbers w dalszym etapie kodu (nie mowimy o deklaracji)
3.wpisac all=lower + upper + number + symbols czyli number zamiast numbers

## Oczekiwany i rzeczywisty wynik
powinien dac losowo wygenerowane haslo

## Zrzut ekranu
