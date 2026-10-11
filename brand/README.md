# Identidad visual

Esta carpeta reúne los colores y tokens de diseño compartidos por los proyectos de Open UCSH. Su propósito es mantener una apariencia consistente y facilitar su implementación.

Estos archivos son una referencia de la comunidad y no sustituyen las normas de identidad institucional de la universidad.

## Archivos

| Archivo | Contenido |
| --- | --- |
| `colors.json` | Paleta de colores y colores semánticos |
| `colors.schema.json` | Esquema para validar los colores |
| `tokens.json` | Tipografía, radios y sombras |
| `tokens.schema.json` | Esquema para validar los tokens |

Los logos, banners y otros recursos gráficos se encuentran en [`../assets/`](../assets/). Sus condiciones de uso se describen en el [README de assets](../assets/README.md) y en [LICENSING.md](../LICENSING.md).

## Uso

Importa estos valores o asígnalos a las variables de diseño del proyecto, como variables CSS o la configuración de Tailwind.

Cada proyecto puede adaptar los tokens a sus necesidades. Cuando un cambio sea útil para varios proyectos, propón incorporarlo aquí mediante una pull request.

Evita repetir valores de la paleta en distintos componentes si ya existe un token equivalente.

## Cambios

Antes de modificar los archivos compartidos:

- Explica el motivo del cambio y qué proyectos podría afectar.
- Valida el JSON con su esquema correspondiente.
- Actualiza los esquemas si cambia la estructura.
- Documenta los nuevos tokens y su uso.

## Accesibilidad

Comprueba que los textos, controles y estados sean legibles sobre sus fondos, incluyendo los temas y estados interactivos disponibles.

Acompaña los colores de estado con texto, iconos u otras señales. La información debe poder entenderse sin depender únicamente del color.
