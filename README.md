# Intro

Bootstrap 4 z małymi modyfikacjami na potrzeby serwisu Moja Ostrołęka.

# Kompilacja

1. W folderze z projektem: `git clone https://github.com/twbs/bootstrap.git`
1. Utworzony zostanie folder `bootstrap`, po wejściu w niego wykonujemy `yarn install` lub `npm`
1. Zmieniamy zmienne w `bootstrap/scss/_viariables.scss`.
1. W konsoli w folderze `bootstrap` wykonujemy `npm run dist`.
1. Cofamy się do katalogu wyżej i wykonujemy `npm run mo`, dzięki temu skrypt skopiuje wygenerowane pliki Bootstrapa do folderu `./dist/`.
1. Dodajemy tagi i publikujemy w npm.

### Info
Aby git nie wykazywał zmian można usunąć z folderu `boostrap` katalog `.git`.

# Ustawienia

```
$blue: #0073bd;
$enable-rounded: false;
```
