# Evidencia técnica pública

Revisión de los seis repositorios públicos disponibles el 30 de octubre de 2026. No se inspeccionaron contenidos privados. Este inventario describe código, no años de experiencia ni calidad productiva.

| Área | Evidencia verificable |
| --- | --- |
| Java / Spring Boot / Maven | [pom.xml de tutorías](https://github.com/CristhianStorm/Curso-sincronico/blob/main/pom.xml), Java 17 y Boot 3.5.6; [API de productos](https://github.com/CristhianStorm/java/blob/main/CrusoJava/curso_java-main/productoapi/pom.xml), Java 21 y Boot 3.4.5. |
| Security / JWT | [Configuración y filtro](https://github.com/CristhianStorm/Curso-sincronico/tree/main/src/main/java/com/gestion/emprendedora/config). La existencia de autenticación no equivale a una auditoría de seguridad. |
| Capas / JPA / Oracle | [Paquetes de tutorías](https://github.com/CristhianStorm/Curso-sincronico/tree/main/src/main/java/com/gestion/emprendedora), con accesos directos desde algunos controladores. Oracle JDBC declarado en Maven. |
| REST / H2 | [Controlador de productos](https://github.com/CristhianStorm/java/blob/main/CrusoJava/curso_java-main/productoapi/src/main/java/com/cristhianstorm/productoapi/controller/cristhianstormProductoController.java); usa ProductoRepository directamente. H2 configurado en memoria. |
| Python / Flask / MySQL / SQL / Docker | [clase5](https://github.com/CristhianStorm/Python/tree/main/Python/clase5): aplicación Flask, blueprint, SQL, Dockerfile y Compose. |
| HTML / CSS / JavaScript | [Interfaces web](https://github.com/CristhianStorm/CristhianStorm.github.io), página Neo Jumper e interfaz de acceso. |
| PHP / POO | [Ejercicios](https://github.com/CristhianStorm/PHP): array.php, poo.php y poo2.php. No constituyen una aplicación PHP completa. |
| Git / GitHub | Historial y organización de los repositorios públicos. |

## Conocimientos declarados sin evidencia pública suficiente

C#, Unity, ASP.NET MVC, Node.js, Express, SQL Server, SQLite, TypeScript, Tailwind CSS, Bootstrap y JasperReports no se presentan como experiencia demostrada por estos repositorios. Tampoco se afirma arquitectura distribuida. Visual Studio y VS Code no se usan como prueba de experiencia técnica.

## Criterio editorial

Se conservan los recursos anteriores sin borrarlos. El README usa SVG locales, texto nativo y enlaces relativos; no depende de tarjetas de estadísticas externas ni de listas de insignias. Las variantes claras, oscuras y móviles usan picture. Se eligió una composición estática: el movimiento no agrega información a este recorrido. La web admite una transición breve y respeta reduced-motion.

Referencias: [imágenes y picture en GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images).
