# Baza Materiałów - README


---

## Struktura projektu

```
Piotr_portfolio/
├── mkdocs.yml              # Konfiguracja strony
├── README.md               # Ten plik
├── docs/
│   ├── index.md           # Strona główna
│   ├── about.md           # O mnie
│   ├── makrdown.md        # Przykłady formatowania
│   ├── notes/             # Notatki ze studiów
│   ├── exams/             # Materiały egzaminacyjne
│   ├── presentations/     # Moje prezentacje
│   └── assets/            # Obrazki, logi, etc.
```

---

## Jak dodawać zawartość

### Dodawanie nowej notatki

```bash
# 1. Stwórz plik w folderze notes/
docs/notes/moj_przedmiot.md

# 2. Dodaj nagłówek i treść
# # Nazwa Przedmiotu
# ## Rozdział 1
# ...zawartość...

# 3. (Opcjonalnie) Zaktualizuj mkdocs.yml aby dodać do menu
```

## Zaawansowane operacje

### Rebuild strony
```bash
mkdocs build
```

### Publikacja na GitHub Pages
```bash
mkdocs gh-deploy
```

---

## Personalizacja

### Zmiana koloru motywu

W `mkdocs.yml` dodaj w sekcji `theme`:
```yaml
theme:
  name: material
  palette:
    primary: blue
    accent: red
```

### Dodanie logo

Umieść logo w `docs/assets/logo.png` i dodaj do `mkdocs.yml`:
```yaml
theme:
  logo: assets/logo.png
  favicon: assets/favicon.ico
```

**Ostatnia aktualizacja:** 23.06.2026  
**Autor:** Piotr
