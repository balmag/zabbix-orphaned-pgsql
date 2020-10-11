# zabbix-orphaned-pgsql

A pyhtonban készült script a zabbix PostgreSQL adatbázisának tisztitására szolgál. Megkeresi azokat a rekordokat amik már nem köthetők sehova (árvák) és azokat törli is.
A script használható magáról a zabbix szerverről (localhost) és távolról is (szükséges a postgresql konfigurálása)
