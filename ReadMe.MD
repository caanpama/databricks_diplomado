# Procesamiento de Datos desde APIs

Este ejercicio muestra cómo *procesar datos desde APIs* utilizando *Apache Spark* en *Databricks*.

---

## ✅ Objetivo

- Conectarse a dos APIs públicas de datos abiertos en Colombia.
- Descargar archivos CSV directamente desde las URLs.
- Cargarlos en DataFrames de Spark.
- Visualizar los datos en Databricks.
- Dejar los datos listos para futuras transformaciones o análisis.

---

## 🔗 APIs Utilizadas

### SECOP

- URL CSV: [https://www.datos.gov.co/resource/rpmr-utcd.csv](https://www.datos.gov.co/resource/rpmr-utcd.csv)

### MEN

- URL CSV: [https://www.datos.gov.co/resource/nudc-7mev.csv](https://www.datos.gov.co/resource/nudc-7mev.csv)

---

## ✅ Consideraciones

- Los archivos pueden ser grandes, por lo que se debe verificar la capacidad del cluster antes de cargarlos.
- Las URLs deben estar accesibles públicamente.
- Se recomienda adaptar la lectura a otros formatos o APIs si el caso de uso lo requiere.
- Es importante validar los esquemas de los datos para asegurar que las lecturas se realicen correctamente.

---

## 👩‍💻 Autor

- Camilo Pachón
- Contacto: camilopachon@usantotomas.edu.co 