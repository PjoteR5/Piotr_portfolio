# 📚 Baza Materiałów Studenckich - README

## 🚀 Szybki start

### Wymagania
- Python 3.6+
- pip (Python Package Manager)

### Instalacja i uruchomienie

```bash
# 1. Instalacja zależności
pip install mkdocs mkdocs-material pymdown-extensions

# 2. Uruchomienie lokalnego serwera
mkdocs serve

# 3. Otwórz w przeglądarce
# http://127.0.0.1:8000
```

Server będzie automatycznie odświeżać się przy każdej zmianie plików!

---

## 📁 Struktura projektu

```
Piotr_portfolio/
├── mkdocs.yml              # Konfiguracja strony
├── README.md               # Ten plik
├── docs/
│   ├── index.md           # Strona główna
│   ├── about.md           # O mnie
│   ├── makrdown.md        # Przykłady formatowania
│   ├── notes/             # 📖 Notatki ze studiów
│   ├── exams/             # 📝 Materiały egzaminacyjne
│   ├── presentations/     # 🎤 Moje prezentacje
│   ├── resources/         # 🔗 Przydatne zasoby
│   └── assets/            # Obrazki, logi, etc.
```

---

## 📖 Jak dodawać zawartość

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

### Format notatek

Używaj Markdown z dodatkowymi możliwościami:

- **Emotikonki** 🎓 📚 💡 ⭐
- **Pogrubienie** i *kursywa*
- `kod` i bloki kodu
- Listy, tabele
- **Diagramy Mermaid** (patrz makrdown.md)
- Linki wewnętrzne `[tekst](../notes/plik.md)`

---

## 🔧 Zaawansowane operacje

### Rebuild strony
```bash
mkdocs build
```

### Publikacja na GitHub Pages
```bash
mkdocs gh-deploy
```

### Zmiana tematu / koloru
Edytuj `mkdocs.yml` w sekcji `theme:`

---

## 💾 Dobre praktyki

✅ **DO:**
- Commituj regularnie zmiany (`git commit`)
- Pisz czytelne notatki z formatowaniem
- Organizuj materiały tematycznie
- Aktualizuj linki na GitHub Pages
- Pushuj zmiany do repozytorium

❌ **NIE RÓB:**
- Nie commituj dużych plików binarnych (PDF, zip)
- Nie edytuj bezpośrednio wygenerowanego HTML
- Nie zmieniaj struktury bez aktualizacji mkdocs.yml

---

## 🎨 Personalizacja

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

---

## 📞 Wsparcie

- 📖 [Dokumentacja MkDocs](https://www.mkdocs.org/)
- 🎨 [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
- 📊 [Mermaid Diagrams](https://mermaid.js.org/)

---

**Ostatnia aktualizacja:** 23.06.2026  
**Autor:** Piotr
