# 🚵 Příručka přežití: Začínáme s horským kolem

*Aneb jak přežít první sjezd a nerozbít si u toho kolo ani kolena.*

## 📖 Úvod

Horské kolo je **skvělý sport**, ale první jízdy jsou drsné. Tahle příručka shrnuje, co jsem se naučil ~~po pár pádech~~ díky zkušenostem. *(Ano, pády jsou součást procesu.)*

![Sjezd z kopce na horském kole](images/mtb-trail.jpg)
*Obrázek 1: Moje oblíbená trasa v lese*

## 🎒 Základní výbava

### Co si vzít s sebou

- **Helma** – bez ní nejezdím ani ke krámu
- Rukavice a brýle
- Duše, hustilka a multitool
- Voda a něco na zub

### Postup před jízdou

1. Zkontroluj tlak v pneumatikách
2. Ověř brzdy
3. Namaž řetěz
4. Řekni někomu, kam jedeš

### Můj tréninkový plán

- [x] Koupit helmu
- [x] Naučit se vyměnit duši
- [ ] Zvládnout první černou trasu
- [ ] Najet 500 km za sezónu

## 🔗 Užitečné odkazy

- [Trailforks](https://www.trailforks.com/) – mapa tras a komunita bikerů
- [Průvodce Markdownem na GitHubu](https://docs.github.com/en/get-started/writing-on-github) – odkud jsem čerpal při psaní tohoto README

## 💻 Ukázka kódu

*Malý skript, který mi doporučí tlak v pneumatikách podle váhy jezdce:*

```python
def doporuceny_tlak(vaha_kg):
    """Orientační tlak v pneumatikách (bar) pro MTB."""
    return round(1.2 + (vaha_kg - 60) * 0.015, 2)

for vaha in (60, 75, 90):
    print(f"{vaha} kg -> {doporuceny_tlak(vaha)} bar")
```

## 📊 Porovnání typů kol

| Typ kola | Odpružení | Vhodné pro | Cena |
|----------|-----------|------------|------|
| Hardtail | Přední vidlice | Začátečníci, XC | $ |
| Full-suspension | Přední i zadní | Trailové a enduro jízdy | $$$ |
| Gravel | Žádné / minimální | Silnice a lehký terén | $$ |

## 🏁 Závěr

**Nejdůležitější rada:** jezdi často, jezdi bezpečně a užívej si to! 🌲
