# Procedimientos de Operaciones IT

## Ejemplo: Reinicio seguro de servidor Linux

```bash
# Notificar usuarios
wall "El servidor se reiniciará en 5 minutos"

# Guardar logs
cp /var/log/syslog /var/log/syslog.backup

# Reiniciar servicios críticos
systemctl restart apache2
systemctl restart mysql

# Reiniciar servidor
shutdown -r +5 "Reinicio programado por mantenimiento"
```

## Checklist diario de infraestructura

- [x] Comprobar estado de servidores
- [x] Monitorización Nagios y alertas
- [x] Revisar backups diarios
- [x] Validar disponibilidad de servicios críticos
