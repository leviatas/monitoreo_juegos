# Monitor de precios de juegos

## Procesos que corren

### Cada 30 minutos

- monitoreo_juegos.py 1

### Cada 60 minutos

- monitoreo_juegos.py 2
- ofertas_reposiciones.py
- genera_csv.py

### Cada 120 minutos

- monitoreo_juegos.py 3

### Cada 1 día

- backup.sh
- baja_cotizacion.py
- actualiza_prioridades.py

### Cada 7 días

- baja_ranking.py

## Corto plazo

- Mudar a Heroku

## Agregar sitios

- planeton
- miniaturemarket
