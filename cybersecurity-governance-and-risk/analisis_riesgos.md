# Ejemplo de análisis de riesgos

```python
# Python pseudo-código de evaluación de riesgo
activos = {"ServidorDB": 5, "AppWeb": 4, "RedInterna": 3}
amenazas = {"AccesoNoAutorizado": 0.3, "SQLInjection": 0.2, "Malware": 0.4}

for activo, impacto in activos.items():
    for amenaza, probabilidad in amenazas.items():
        riesgo = impacto * probabilidad
        print(f"Activo: {activo}, Amenaza: {amenaza}, Riesgo: {riesgo}")
```

- Muestra capacidad de **análisis y mitigación** de riesgos  
- Compatible con ISO 27001 y NIST
