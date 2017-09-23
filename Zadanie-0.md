# Rozpoczęcie pracy

## Przygotowanie repozytorium

1. Skorzystamy z [https://pages.github.com/](https://pages.github.com/) które umożliwi nam uruchomienie naszej strony bezpośrednio z repozytorium GitHuba
2. Zapoznaj się z opisem oraz krokami które prowadzą do konfiguracji repozytorium
3. Wykonaj opisane kroki, postępuj zgodnie z opisem na stronie
4. Stwórz plik **.gitignore** z wpisem o folderze **.idea**
5. Stwórz plik **README.md**; WebStorm posiada [plugin do obsługi Markdown](https://plugins.jetbrains.com/plugin/7793-markdown-support)) który możesz pobrać na stronie lub dodać w **Settings->Plugins**
6. Korzystając ze składni [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) stwórz opis repozytorium. Opis powinien zawierać:
  * Nagłówek, np: {Imię nazwisko} - portfolio
  * Krótki opis i założenia projektu
  * Link do działającego projektu

------

## Konfiguracja środowiska

1. Instalujesz GITa:
  * Najszybciej zacząc tu: [https://git-scm.com/downloads](https://git-scm.com/downloads)
  * Wybierz swoj OS (system operacyjny) i postępuj zgodnie z instrukcjami na stronie
2. Po instalacji konfigurujesz (tak jak na zajęciach z narzędzi deweloperskich)
```
git config --global user.name "Imię nazwisko"
git config --global user.email "twoj-adres@email.pl"
git config --global color.status auto
git config --global color.branch auto
```
3. Klonujesz swoje repozytorium:
  * git clone https://github.com/{USERNAME}/{USERNAME}.github.io i otwierasz folder {USERNAME}.github.io w WebStormie
  * lub od razu z poziomu WebStorma (Checkout from Version Control->GitHub)
4. WebStorm zapyta o login i hasło do GitHuba
5. Środowisko gotowe, możesz zaczać pracę

