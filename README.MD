
# Dev_Erp_Odoo19 🚀

Repositorio central para el desarrollo y alojamiento de módulos personalizados (custom addons) para la implementación de **Odoo 19**.

## 📂 Estructura del Proyecto
* `custom/addons/`: Directorio principal donde residen todos los módulos desarrollados a medida para adaptar el ERP a nuestras necesidades.
* *Nota:* El código fuente del motor de Odoo (Community y Enterprise) se maneja en repositorios separados y está excluido de este repositorio mediante `.gitignore` por seguridad y limpieza.

## 🛠️ Entorno de Desarrollo
* **Sistema Operativo:** Ubuntu 24.04 (Nativo o WSL2)
* **Python:** 3.12+
* **Base de Datos:** PostgreSQL 16+

## ⚙️ Configuración del Servidor
Para que Odoo reconozca los módulos de este repositorio, el archivo `odoo.conf` del servidor local debe incluir la ruta hacia la carpeta `custom/addons` en el parámetro `addons_path`.

Ejemplo de orden de rutas:
```ini
addons_path = /odoo19/odoo19-server/addons,/odoo19/enterprise,/odoo19/custom/addons

```
