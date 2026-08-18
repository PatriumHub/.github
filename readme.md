# PatriumHub

**Centro de comando patrimonial** personal y multiempresa.

PatriumHub concentra en una sola app lo que tenés, lo que debés, lo que cobrás y cómo evoluciona — personas, empresas, cuentas, presupuestos, proyecciones e integraciones (WooCommerce / Mercado Pago).

## Repositorios

| Repo | Contenido |
|------|-----------|
| **PatriumHub** | App PHP (front + back) |
| **databases** | `patriumhub.sql` — instalación única de la BD |
| **Arquitectura** | Documentación técnica |
| **Guia_De_Uso** | Manual de usuario en español |

## Stack

- PHP 8+ · MySQL/MariaDB · Apache  
- Una sola base `patriumhub`  
- Deploy en carpeta `/patrium` (rutas `index.php?r=/...`)  
- Credenciales de integraciones en pantallas (tokens cifrados en BD)

## Principios

1. **Patrimonio, no contabilidad** — valor y liquidez, no libros fiscales.  
2. **Una sola fuente de verdad** — cada activo o deuda una vez, asociado a su entidad.  
3. **Sin duplicar** — participaciones y co-titulares no inflan el consolidado.  
4. **Manual siempre posible** — las integraciones son optativas.

## Empezar

1. Importar **solo** `databases/patriumhub.sql` en phpMyAdmin.  
2. Copiar la app a `/patrium` y configurar `.env` (DB + `APP_URL`).  
3. Login seed: `admin@patriumhub.local` / `admin123` (cambiar al entrar).  
4. Ver `Arquitectura/guia-deploy.md` y `Guia_De_Uso/`.

## Licencia / uso

Proyecto privado de uso interno / patrimonial.  
Sin datos de producción ni secretos en los repos.
