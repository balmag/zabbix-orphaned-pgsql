# zabbix-orphaned-pgsql

A pyhtonban készült script a zabbix PostgreSQL adatbázisának tisztitására szolgál. Megkeresi azokat a rekordokat amik már nem köthetők sehova (árvák) és azokat törli is.
A script használható magáról a zabbix szerverről (localhost) és távolról is (szükséges a postgresql konfigurálása)

## Előkészületek
A python script futtatásához szükség lesz a psycopg2 modulra.
Ezt a következőképpen lehet telepíteni:
```bash
pip install psycopg2
```

Amennyiben a rendszeren a pip (Python Package Installer) még nem található meg, szükséges telepíteni. 
Debian rendszeren a következőképpen néz ki:
```bash
apt install python-pip
```

