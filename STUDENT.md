# Moje wykonanie Lab00

- Login GitHub / pseudonim: dzemkwas
- System i terminal (np. Windows + WSL Ubuntu): Arch linux, zsh
- Edytor / IDE: neovim
- Wersja Git: 2.55
- Wersja kompilatora C++: 16.2.1
- Wersje java i javac: 21.0.12.1
- Link do pierwszego PR (uzupełnij w zadaniu 5): https://github.com/dzemkwas/oop-lab00-Kacper_Zacharek/pull/1

## Uruchomienie lokalne
Wynik programu C++:
```text
Hello from C++! Author: Kacper Zacharek
```
Wynik programu Java:
```text
Hello from Java! Author: Kacper Zacharek
```

## Błąd i poprawka (zadanie 5)
- Krótki fragment komunikatu błędu i numer linii: cpp/main.cpp:5:67: error: expected ‘;’ before ‘return’
                                                  5 |     std::cout << "Hello from C++! Author: Kacper Zacharek" << '\n' return 0;
- Przyczyna oraz sposób naprawy: Dodanie średnika na końcu linijki 5
- Commit z błędem (SHA lub link): https://github.com/dzemkwas/oop-lab00-Kacper_Zacharek/commit/2ff94b8d6ff33d9a451c70ac567fe965dc9df76b
- Czy Actions pokazały błąd, a po naprawie sukces? Tak

## Krótkie odpowiedzi
1. Co różni commit od push? Commit zapisuje zmiany lokalnie a push przerzuca obecny commit history do repozytorium zdalnego
2. Dlaczego po scaleniu PR wykonuję lokalnie pull? Ponieważ scalenie dzieje sie tylko na zdalnym repozytorium i trzeba wykonać pull by zaktualizować lokalne stan z zdalnego repozytorium
3. Co potwierdza zielony wynik naszego CI, a czego nie potwierdza? Potwierdza czy program sie skompilował, nie potwierdza czy program działa tak jak należy

## Ewentualne problemy środowiska
Brak / opis problemu i sposób rozwiązania: brak
