
# Recupera valor UF por fecha desdes SII.cl

Este script recibe como parametro una fecha dd-mm-aaaa consulta a la web de servicio impuestos internos y guarda los resultados por año en formato .csv.

ademas devuelve el resultado en formato JSON

{"data": { "dia": "1", "mes": "Enero","anio": "2021","UF": "29.069,39"}}



## API Reference

#### Get UF por fecha

```https
  GET /api/01-02_2022
```


