# Deploy Neocities

Ejemplo de despliegue continuo en Neocities usando GitHub Actions.

## Uso

1. Clona este repositorio.
2. Crea una cuenta en [Neocities](https://neocities.org/).
3. Ve a `https://neocities.org/settings/tu_nombre_de_usuario#api_key` y copia tu API key.
4. Ve a la configuración de tu repositorio en GitHub, luego a "Secrets and variables" > "Actions" y crea un nuevo secret llamado `NEOCITIES_API_KEY` con el valor de tu API key.
5. Haz un commit y push a la rama `main` (o la rama que hayas configurado en el workflow).
6. GitHub Actions se encargará de desplegar tu sitio automáticamente en Neocities.