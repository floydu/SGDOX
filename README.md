# SGDOX – Sistema de Gestión Documental para Ecuador

![SGDOX Logo](LOGO-SGDOX.png)

**SGDOX** es un **sistema de gestión documental** moderno, web y seguro, desarrollado en Ecuador por **Floydu S.A.S.** para instituciones públicas, GADs, municipios, prefecturas, universidades, empresas públicas y organizaciones que necesitan controlar documentos electrónicos, expedientes, firma electrónica, trazabilidad y procesos institucionales.

SGDOX nace como una alternativa tecnológica moderna frente a plataformas documentales heredadas como **Quipux**, incorporando una arquitectura web, desacoplada, escalable y preparada para operación en la nube o en infraestructura propia.

La plataforma permite gestionar el ciclo de vida completo de los documentos institucionales: creación, redacción, revisión, firma electrónica, envío, recepción, seguimiento, archivo, búsqueda y administración de expedientes con **Número Único de Trámite (NUT)**.

---

## 🚀 ¿Qué es SGDOX?

SGDOX es una plataforma de **gestión documental electrónica** diseñada para digitalizar y controlar los procesos documentales de una institución.

Permite administrar documentos oficiales, comunicaciones internas, memorandos, oficios, informes, anexos, expedientes, trámites y documentos externos, manteniendo trazabilidad completa sobre cada acción realizada dentro del sistema.

SGDOX ayuda a las instituciones a reducir el uso de papel, ordenar sus procesos documentales, mejorar el seguimiento de trámites y fortalecer la seguridad de la información.

---

## ✨ Funcionalidades principales

- 🧾 **Número Único de Trámite (NUT)**  
  Organización de documentos relacionados dentro de expedientes institucionales con identificador único de trámite.

- ✅ **Firma electrónica nativa y sin plugins**  
  Firma de documentos electrónicos desde navegador, escritorio o celular, sin instalación de componentes adicionales.

- 📄 **Redacción documental avanzada**  
  Creación, edición, revisión, envío y firma de documentos institucionales con control de versiones y validaciones previas.

- 🔐 **Gestión avanzada de usuarios y permisos**  
  Administración de usuarios, roles, áreas, cargos, subrogaciones, delegaciones, listas de distribución y permisos institucionales.

- 📬 **Bandejas documentales**  
  Gestión de documentos recibidos, enviados, en elaboración, reasignados, informados, sumillados y archivados.

- 📎 **Adjuntos configurables por política institucional**  
  Control de tipos de archivo permitidos, tamaños máximos y reglas de validación para documentos adjuntos.

- 🔍 **Búsqueda avanzada con Elasticsearch**  
  Búsqueda documental por metadatos, contenido textual, estado, fechas, remitente, destinatario, categoría y otros criterios.

- 🧩 **Campos personalizados**  
  Definición de campos adicionales para tipos documentales, expedientes o procesos específicos de la institución.

- 🕵️ **Auditoría y trazabilidad completa**  
  Registro de usuario, fecha, hora, IP, navegador, acción realizada, documento asociado y recorrido documental.

- 🏢 **Ventanilla virtual para ciudadanos**  
  Registro y gestión de documentos externos o ciudadanos, integrados al flujo documental interno de la institución.

- 📱 **Interfaz web responsive**  
  Uso desde navegador web en computadoras, tablets y teléfonos celulares.

- 📤 **Descarga externa controlada**  
  Acceso seguro a documentos para destinatarios externos mediante mecanismos controlados.

- 🔄 **API REST**  
  Arquitectura preparada para integraciones con otros sistemas institucionales, plataformas externas o servicios complementarios.

---

![SGDOX Demo](SGDOX.gif)

---

## SGDOX como alternativa a Quipux

Durante años, muchas instituciones ecuatorianas han utilizado sistemas documentales heredados para gestionar comunicaciones oficiales. Sin embargo, las necesidades actuales exigen plataformas más modernas, flexibles, seguras y adaptables.

SGDOX fue diseñado para ofrecer una alternativa moderna a **Quipux** y otros sistemas de gestión documental tradicionales, manteniendo el enfoque institucional, pero incorporando mejoras en arquitectura, usabilidad, firma electrónica, trazabilidad, despliegue, soporte y evolución funcional.

SGDOX no es una adaptación de Quipux. Es una plataforma desarrollada con una arquitectura moderna, orientada a instituciones que necesitan mayor control sobre sus documentos, expedientes y procesos internos.

---

## Gestión documental para instituciones públicas

SGDOX está orientado a instituciones que necesitan administrar documentos oficiales, comunicaciones internas, memorandos, oficios, informes, anexos, expedientes y trámites documentales.

Casos de uso principales:

- Gobiernos Autónomos Descentralizados.
- Municipios.
- Prefecturas.
- Empresas públicas.
- Universidades.
- Hospitales y entidades de salud.
- Instituciones del Gobierno Central.
- Entidades de control.
- Organizaciones privadas con procesos documentales formales.
- Instituciones que buscan modernizar o reemplazar plataformas documentales heredadas.
- Organizaciones que requieren trazabilidad documental, firma electrónica y control institucional.

---

## 💡 Beneficios de SGDOX

- Plataforma 100 % web.
- Firma electrónica sin plugins.
- Gestión documental centralizada.
- Expedientes institucionales con NUT.
- Trazabilidad completa de documentos.
- Auditoría de acciones.
- Control de usuarios, roles y permisos.
- Bandejas documentales organizadas.
- Búsqueda avanzada de documentos.
- Ventanilla virtual para documentos externos.
- Despliegue en nube o infraestructura institucional.
- Soporte técnico especializado desde Ecuador.
- Evolución constante del producto.
- Arquitectura moderna y desacoplada.

---

## 🧠 Tecnología y arquitectura

SGDOX utiliza una arquitectura moderna compuesta por frontend web, backend API REST, base de datos relacional, motor de búsqueda documental y servicios especializados para generación de documentos, firma electrónica y almacenamiento seguro.

| Componente | Tecnología |
|---|---|
| Frontend | React.js / Vite |
| Backend | Symfony / PHP |
| Base de datos | MySQL / MariaDB |
| Búsqueda documental | Elasticsearch |
| Documentos PDF | TCPDF |
| Despliegue | Docker / Docker Compose / Traefik |
| Seguridad | 2FA, SHA-256, auditoría y control de roles |

---

## 🐳 Modalidades de implementación

SGDOX puede implementarse según las necesidades técnicas, operativas y contractuales de cada institución.

### Modalidad SaaS

La institución accede al sistema como servicio administrado, incluyendo hosting, soporte, actualizaciones y mantenimiento según el contrato correspondiente.

### Implementación en infraestructura institucional

SGDOX puede desplegarse en infraestructura propia de la institución, servidores institucionales, nube privada o centro de datos autorizado.

### Nube privada o pública

SGDOX también puede desplegarse en ambientes cloud, manteniendo separación de componentes y control de infraestructura.

---

## 🔒 Seguridad de la información

SGDOX incorpora controles orientados a proteger la información documental y mantener evidencia de las acciones realizadas dentro de la plataforma.

Entre sus capacidades se incluyen:

- Autenticación de usuarios.
- Autenticación de doble factor.
- Control de roles y permisos.
- Auditoría de acciones.
- Registro de trazabilidad documental.
- Control de adjuntos.
- Hash SHA-256 para integridad documental.
- Protección adicional en inicio de sesión.
- Separación de usuarios internos y externos.
- Administración institucional de accesos.

---

## Firma electrónica y FirmaEC

SGDOX permite firmar documentos electrónicamente dentro de la plataforma, sin necesidad de instalar plugins o componentes adicionales en el equipo del usuario.

Los documentos generados y firmados desde SGDOX están orientados a procesos de verificación compatibles con **FirmaEC**, facilitando la adopción institucional de documentos electrónicos firmados.

---

## SGDOX y transformación digital

La gestión documental es uno de los componentes principales de la transformación digital institucional. SGDOX permite que las entidades reduzcan procesos manuales, mejoren la trazabilidad, organicen documentos electrónicos y fortalezcan la gestión administrativa.

Con SGDOX, una institución puede avanzar hacia una gestión documental más ordenada, segura y transparente, manteniendo control sobre sus documentos, usuarios, expedientes y procesos.

---

## Licenciamiento y propiedad intelectual

SGDOX es una plataforma propietaria desarrollada por **Floydu S.A.S.**

Su uso, implementación, soporte, capacitación, mantenimiento y actualizaciones se realizan bajo condiciones comerciales acordadas con cada institución u organización.

La contratación o autorización de uso de SGDOX no implica cesión de código fuente ni transferencia de derechos de propiedad intelectual.

El código fuente del frontend, backend, servicios internos, configuraciones de despliegue y componentes propietarios se mantiene en repositorios privados protegidos.

El uso, copia, modificación, distribución, despliegue o comercialización de SGDOX requiere autorización expresa de **Floydu S.A.S.** o contrato vigente.

---

## 🌐 Sitio oficial y contacto

**Sitio oficial:** [https://sgdox.com](https://sgdox.com)  
**Correo:** [info@floydu.com](mailto:info@floydu.com)

---

## SGDOX – Gestión documental moderna para Ecuador

SGDOX es una solución de **gestión documental electrónica** diseñada para instituciones que necesitan trazabilidad, firma electrónica, seguridad, expedientes, ventanilla virtual y control formal de documentos.

Una plataforma desarrollada en Ecuador para modernizar la gestión documental institucional.
