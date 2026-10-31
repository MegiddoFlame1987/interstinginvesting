# InterestingInvesting

Strona z wynikami eksperymentów inwestycyjnych na żywo. Na start dla Norberta, bez klientów.

| Sekcja | Źródło danych |
|---|---|
| Agenci dzienni v1.2 i v3.1 | `od0doM/data/wyniki.csv`, `od0doM/data_v3/wyniki.csv` |
| Typy z rolek vs SPY | `od0doM/strategie/typy_raport.md` |

Strona to jeden plik `index.html`. Przy każdym otwarciu czyta pliki z publicznego repo od0doM, więc nowe sesje pojawiają się same, bez wdrażania.

Wdrożenie: Vercel, import tego repo, framework "Other", bez komendy build. Każdy push do `main` wdraża się sam.

Test lokalny z innym źródłem danych: `index.html?base=/sciezka/do/od0dom/`.

To repo jest publiczne. Żadnych prywatnych finansów, kwot ani eksportów czatu.
