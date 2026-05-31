# XML Practice

![XML](https://img.shields.io/badge/XML-1.0-e65100?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyem0wIDE4Yy00LjQxIDAtOC0zLjU5LTgtOHMzLjU5LTggOC04IDggMy41OSA4IDgtMy41OSA4LTggOHoiLz48L3N2Zz4=)&nbsp;![W3C](https://img.shields.io/badge/W3C-Standard-005a9c?style=for-the-badge)&nbsp;![Well-Formed](https://img.shields.io/badge/Well--Formed-Documents-388e3c?style=for-the-badge)&nbsp;![VS Code](https://img.shields.io/badge/VS_Code-XML_Extension-007acc?style=for-the-badge&logo=visualstudiocode)&nbsp;![Lenguajes de Marca](https://img.shields.io/badge/Lenguajes_de_Marca-LMSGI-c62828?style=for-the-badge)

> **XML Practice** es una colección de documentos XML bien formados y con estructura jerárquica, desarrollada como práctica de la asignatura **Lenguajes de Marca y Sistemas de Gestión de Información** del Grado Superior de DAW — IES Augustóbriga.

---

## 📋 Descripción

Este repositorio contiene dos ejercicios prácticos de modelado y escritura de documentos **XML 1.0** a partir de enunciados reales. Los documentos trabajan con:

- **Estructura jerárquica** de elementos padre/hijo con datos reales.
- **Atributos** para metadatos e identificadores de nodos.
- **Documentos bien formados** siguiendo las reglas del estándar W3C.
- **Prólogo XML** con declaración de versión y codificación `UTF-8`.
- **Modelado semántico** de entidades del mundo real: empleados y productos de tienda.

---

## 🏗️ Estructura del Proyecto

```txt
XML_Practice/
├── empleados.xml     # Documento XML con estructura de empleados de una empresa
├── Empleados.pdf     # Enunciado del ejercicio de empleados
├── tienda.xml        # Documento XML con catálogo de productos de una tienda
└── Tienda.pdf        # Enunciado del ejercicio de tienda
```

---

## ⚙️ Uso

Clona el repositorio:
```txt
git clone https://github.com/sorgazb/XML_Practice.git
cd XML_Practice
```

### Abrir y visualizar

Abre cualquier `.xml` directamente en el **navegador** para visualizar su estructura en árbol, o en **VS Code** con la extensión XML de Red Hat para obtener resaltado de sintaxis y validación de bien formado.

### Verificar bien formado con xmllint

```txt
xmllint --noout empleados.xml
xmllint --noout tienda.xml
```

Si no hay salida, el documento está bien formado.

---

## 🤝 Contribución

Haz fork del repositorio.

Crea una rama de trabajo:

```txt
git checkout -b feature/nuevo-documento
```

Realiza tus cambios y haz commit.

Abre un Pull Request describiendo tus mejoras.

---

<p align="center">Práctica LMSGI &ndash; GS DAW &ndash; IES Augustóbriga &ndash; Sergio Orgaz Bravo</p>
