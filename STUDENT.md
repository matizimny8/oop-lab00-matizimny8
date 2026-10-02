# Moje wykonanie Lab00

- Login GitHub / pseudonim: matizimny8
- System i terminal (np. Windows + WSL Ubuntu): Windows + WSL Ubuntu
- Edytor / IDE: Visual Studio Code
- Wersja Git: git 2.43.0
- Wersja kompilatora C++: g++ 13.3.0
- Wersje java i javac: 17.0.20.1
- Link do pierwszego PR (uzupełnij w zadaniu 5): https://github.com/matizimny8/oop-lab00-matizimny8/pull/1

## Uruchomienie lokalne
Wynik programu C++:
```Hello from C++! Author: matizimny8
...
```
Wynik programu Java:
```Hello from Java! Author: matizimny8
...
```

## Błąd i poprawka (zadanie 5)
- Krótki fragment komunikatu błędu i numer linii: Error: Process completed with exit code 1. Linia 6
- Przyczyna oraz sposób naprawy: Brak średnika - należy go dodać na koncu linii
- Commit z błędem (SHA lub link): https://github.com/matizimny8/oop-lab00-matizimny8/pull/2/changes/a105b1c643f6d5b28e719930f49a1aca1087779c
- Czy Actions pokazały błąd, a po naprawie sukces? Tak

## Krótkie odpowiedzi
1. Co różni commit od push? Commit tworzy lokalny zapis plików, a push wysyła stworzone commity na repozytorium
2. Dlaczego po scaleniu PR wykonuję lokalnie pull? Scalenie PR odbywa sie na serwerze, aby zmiany zaszły na lokalnym komputerze trzeba użyć pull
3. Co potwierdza zielony wynik naszego CI, a czego nie potwierdza? Potwierdza, że program kompiluje sie poprawnie, nie potwierdza że program nie zawiera błędów logicznych 

## Ewentualne problemy środowiska
Brak