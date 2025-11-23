# UZPR - semestrální práce
## Skupina B - Analýza výstavby dopravní infrastruktury v zemích Evropské Unie
### Členové:
- František Gurecký
- Veronika Ciencialová

---

### Cíle práce
- zjistit, jak se daří České republice budovat dálnice a železnice ve srovnání s ostatními státy Evropské Unie
- jak se daří jednotlivým státům EU
- jaké jsou průměrné hodnoty roční výstavby infrastruktury
- jaký je vývoj celkové délky infrastruktury v čase

---

### Spuštění prostředí

#### 1. Instalace závislostí
V hlavním adresáři repositáře spusťte příkaz:
```python -m venv .venv```

Tím vytvoříme nové virtuální prostředí pro tento projekt, dále jej aktivujeme příkazem:
```.venv\Scripts\activate```

Nyní bychom měli být ve virtuálním prostředí. Dále do něj nainstalujeme potřebné balíčky:
```pip install -r requirements.txt```

#### 2. Spuštění Jupyter Serveru
Jupyter Server spusťte příkazem:
```python -m notebook```
V prohlížeči se po spuštění otevře rozhraní.
Pokud se neotevře automaticky, server běží na adrese:
```http://localhost:8888/tree```
Nyní již můžeme s notebookem pracovat obvyklým způsobem.