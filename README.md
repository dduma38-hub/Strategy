# Strategy

## Scopul proiectului
Acesta este un proiect minimal de exemplu, creat pentru a oferi o structură de bază (sursă + teste) care poate fi extinsă ulterior.

## Structură
- `src/` — codul sursă al aplicației.
- `tests/` — testele automate asociate codului din `src/`.

## Rulare
1. (Opțional) Creează și activează un mediu virtual Python.
2. Rulează testele:

```bash
python -m pytest -q
```

## Exemplu de utilizare
Poți importa funcția `add` astfel:

```python
from src.calculator import add

result = add(2, 3)
print(result)  # 5
```

## Pas următor recomandat
După acest bootstrap, solicită o analiză QA pentru review pe logică, design și riscuri înainte de extinderea funcționalităților.
