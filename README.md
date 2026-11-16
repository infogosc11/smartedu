# SmartEDU

Darmowe testy, egzaminy i materiały do nauki – do wydruku, dla każdego.

## Materiały

| Kod | Nazwa | Pliki |
| --- | --- | --- |
| SE-M8-01 | Próbny egzamin ósmoklasisty – Matematyka (125 min, 20 zadań, 30 pkt) | [arkusz](pdf/se-m8-01-arkusz.pdf) · [klucz](pdf/se-m8-01-klucz.pdf) |

Arkusze są wzorowane na formule egzaminów CKE, ale nie są materiałami Centralnej Komisji Egzaminacyjnej.

## Struktura repozytorium

```
index.html   – strona projektu
img/         – podglądy stron arkuszy
pdf/         – arkusze i klucze do pobrania
.nojekyll    – wyłącza przetwarzanie Jekyll na GitHub Pages
```

## Dodawanie nowego arkusza

1. Wrzuć pliki PDF do folderu `pdf/` (np. `se-m8-02-arkusz.pdf`, `se-m8-02-klucz.pdf`).
2. W `index.html` skopiuj blok `<article class="card main" ...>` i zmień kod, nazwę oraz linki.
3. Dopisz arkusz do tabeli w tym pliku README.
