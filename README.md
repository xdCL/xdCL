<div align="center">

# xdCL

**[← Volver al inicio · xdCL](https://xdcl.github.io/)**

### Herramientas pequeñas para problemas concretos.

Software, utilidades web y experimentos desarrollados desde Chile.  
Me interesa hacer cosas **simples, ligeras, portables y útiles**.

[![Josts](https://img.shields.io/badge/Josts-Windows_Hosts_Manager-1f6feb?style=flat-square)](https://github.com/xdCL/Josts)
![Windows](https://img.shields.io/badge/Windows-10%2F11-0078D4?style=flat-square&logo=windows11&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-14-00599C?style=flat-square&logo=cplusplus&logoColor=white)

</div>

---

## Proyectos

<table>
<tr>
<td width="50%" valign="top">

### 🧱 Josts

**Administrador portable del archivo hosts para Windows.**

Pensado especialmente para equipos compartidos y entornos educativos. Permite aplicar y retirar baterías de bloqueo sin reemplazar silenciosamente configuraciones externas.

**Estado:** 🟡 Release Candidate / v1.3 en desarrollo

[**Descargar Josts**](https://github.com/xdCL/Josts/releases) · [Código fuente](https://github.com/xdCL/Josts) · [v1.3 Josts Sync](https://github.com/xdCL/Josts/pull/3)

</td>
<td width="50%" valign="top">

### 🗺️ GeoSVG

**Generador de mapas SVG de Chile.**

Herramienta para seleccionar comunas, aplicar paletas de color y obtener mapas vectoriales listos para utilizar en diseño, visualización y comunicación.

**Estado:** 🟠 En desarrollo

Próximamente: **usar online** · **código fuente**

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🖨️ Cosito

**Mosaicos de impresión directamente en el navegador.**

Divide imágenes en hojas Carta, A4 u Oficio, incorpora marcas de corte y permite preparar piezas de gran formato sin instalar software adicional.

**Estado:** 🟠 En desarrollo

Próximamente: **usar online** · **código fuente**

</td>
<td width="50%" valign="top">

### 📺 PCC

**Para proyectar o presentar cualquier cosa.**

Una herramienta pensada para llevar contenido a una pantalla de forma simple: imágenes, avisos, material visual, presentaciones y otros contenidos que necesiten mostrarse sin complicar el flujo.

**Estado:** 🟠 En desarrollo

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 📰 Telacuento

**Proyecto web de orientación periodística.**

Una exploración de producto digital, contenidos y herramientas pensadas desde la comunicación.

**Estado:** 🟠 En desarrollo

Próximamente: **sitio** · **repositorio**

</td>
<td width="50%" valign="top">

### 🧪 Laboratorio

Pequeños experimentos, prototipos y herramientas que nacen porque había algo que resolver.

Algunos se transforman en aplicaciones. Otros simplemente quedan como buenas ideas que funcionaron.

</td>
</tr>
</table>

---

## Josts Sync

Actualmente estoy trabajando en **Josts v1.3**, una evolución del proyecto que permite mantener una batería central de dominios y distribuir sus actualizaciones de forma silenciosa y verificable.

La arquitectura mantiene la filosofía de Josts:

- un solo ejecutable;
- sin administración remota genérica;
- sin credenciales almacenadas;
- actualizaciones de la batería mediante HTTPS;
- verificación SHA-256 + firma RSA;
- compatibilidad con cuentas estándar de Windows mediante UAC cuando corresponde.

> **v1.2.x:** estabilidad y compatibilidad.  
> **v1.3.x:** sincronización segura de baterías de bloqueo.

[Ver desarrollo de Josts Sync →](https://github.com/xdCL/Josts/pull/3)

---

## En qué estoy trabajando

```text
Josts      █████████████████░░░  v1.3 / piloto
GeoSVG     ███████████░░░░░░░░░  en desarrollo
Cosito     ██████████░░░░░░░░░░  en desarrollo
Telacuento ████████░░░░░░░░░░░░  en desarrollo
```

---

## Principios

**Portable cuando se pueda.**  
Prefiero herramientas que puedas abrir y usar sin montar una infraestructura innecesaria.

**El usuario debe entender qué está pasando.**  
Nada de cambios silenciosos difíciles de revertir, credenciales guardadas o comportamientos ocultos.

**Resolver primero. Adornar después.**  
La interfaz importa, pero la herramienta tiene que solucionar el problema que la hizo existir.

---

<div align="center">

### xdCL

**Windows · web · educación · diseño · datos**

_Hecho desde Chile._

</div>
