# 🔓 Bot Unlock Bootloader

Script automatizado que envía solicitudes de desbloqueo de bootloader a las 00:00 (hora de Beijing).

## 🚀 Características

- ✅ Envío automático de solicitudes a las 00:00 (hora Beijing)
- ✅ **Instalación automática de dependencias** - No requiere configuración previa
- ✅ Compatible con **Windows, Linux y macOS**
- ✅ **Compatible con Termux (Android)**
- ✅ Interfaz simple y fácil de usar
- ✅ Registro de actividades automático

## 📋 Requisitos

- **Python 3.6 o superior**
- Conexión a Internet estable

## ⚡ Instalación Rápida

### En Windows, Linux o macOS:

```bash
# Clonar el repositorio
git clone https://github.com/EJPS7/Bot-unlock-bootloader-.git
cd Bot-unlock-bootloader-

# Ejecutar el script (instala dependencias automáticamente)
python script.py
```

### En Termux (Android):

```bash
# Instalar git y python
pkg install git python -y

# Clonar el repositorio
git clone https://github.com/EJPS7/Bot-unlock-bootloader-.git
cd Bot-unlock-bootloader-

# Ejecutar el script (instala dependencias automáticamente)
python script.py
```

## 🎯 Uso

1. Ejecuta el script:
   ```bash
   python script.py
   ```

2. ¡Listo! El script se encargará automáticamente de:
   - Instalar las dependencias necesarias (solo la primera vez)
   - Enviar la solicitud de desbloqueo a las 00:00 (hora Beijing)
   - Mantener la aplicación en ejecución

## 📝 Notas Importantes

⚠️ **ADVERTENCIA:**
- Asegúrate de dejar el script en ejecución durante la hora establecida (00:00 Beijing)
- El dispositivo debe tener conexión a Internet
- Esta herramienta es solo para fines educativos y personales
- El desbloqueo de bootloader puede anular la garantía en algunos dispositivos

## 🛠️ Solución de Problemas

### El script no se inicia en Termux
```bash
# Actualizar pip
python -m pip install --upgrade pip

# Intentar ejecutar nuevamente
python script.py
```

### Error de permisos
```bash
# En Linux/macOS, dar permisos de ejecución
chmod +x script.py
python script.py
```

### La solicitud no se envía
- Verifica tu conexión a Internet
- Asegúrate de que el servidor esté disponible
- Revisa los logs de la aplicación

## 📱 Plataformas Soportadas

| Plataforma | Estado | Instrucciones |
|-----------|--------|--------------|
| Windows | ✅ Soportado | `python script.py` |
| Linux | ✅ Soportado | `python script.py` |
| macOS | ✅ Soportado | `python script.py` |
| Termux (Android) | ✅ Soportado | Ver sección Termux arriba |

## 📄 Licencia

Este proyecto está disponible bajo licencia MIT. Ver archivo LICENSE para más detalles.

## 💬 Soporte

Si tienes problemas o sugerencias, por favor abre un issue en el repositorio.

---

**Versión:** 1.0  
**Última actualización:** 2026-05-08
