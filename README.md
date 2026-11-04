# Proyecto NER Nueva Alianza

Copia independiente de la interfaz de gestión escolar configurada para mostrar únicamente el NER **NUEVA ALIANZA**.

## Escuelas incluidas

- CENTRO ESCOLAR HUGO CHAVEZ FRIAS — 39183
- CENTRO ESCOLAR SECTOR DE LIMON — 37038
- LA ESPERANZA — 17751
- LA UNIÓN Nº 3 — 17858
- NUEVA ALIANZA — 17683
- NUEVA JERUSALEN — 30870
- ROSA SARMIENTO — 29271
- SANTA LUCIA — 17880

La lista también está en `escuelas.json`. Los nombres y códigos corresponden a los datos del sistema consultados el 3 de noviembre de 2026.

## Archivos

- `index.html`: portada y acceso a los módulos.
- `REGISTRO_NOTAS.html`: ingreso de calificaciones y seguimiento; limita el núcleo y sus escuelas.
- `RETIROS_REPROBADOS.html`: registro y consulta de retiros y reprobados filtrados a Nueva Alianza.
- `tema.css`: estilos compartidos.
- `escuelas.json`: lista de las ocho escuelas y sus códigos.

## Uso

Abra `index.html` en un navegador con conexión a internet. Para consultar escuelas, grupos y calificaciones, use el código de acceso de Nueva Alianza que entrega la dirección del núcleo. No se incluyen claves en este proyecto.

La interfaz utiliza el servicio de datos del sistema original; este proyecto separa la presentación y el filtro del NER, pero no crea una base de datos independiente.

Fuente de la interfaz original: https://github.com/KENIERGT/GESTION-ESCOLAR---EL-CUA