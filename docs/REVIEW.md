# Identidad y organización del perfil

## Dirección visual

**CS // SOFTWARE LAB** representa una práctica de ingeniería: interfaz, servicios y datos conectados. El nombre ocupa el primer plano; las conexiones y capas explican el enfoque Full Stack. El monograma CS se dibuja con trazos abiertos y un conector ámbar.

| Token | Oscuro | Claro |
| --- | --- | --- |
| Fondo | #10262F | #F1F5F3 |
| Superficie | #17333D | #E4EEEB |
| Texto | #EFF5F4 | #16343E |
| Secundario | #ADBEC2 | #506970 |
| Conexión | #8BD8D0 | #226F70 |
| Acento | #EDB574 | #94602B |

Tipografía de sistema Segoe UI/Arial para SVG y web; Georgia aporta un contraste editorial a la frase de la web. No se necesitan fuentes externas. Los gráficos del README tienen tema claro/oscuro; hero y mapa tienen además composiciones móviles. Las ilustraciones representan conceptos, no capturas reales de las aplicaciones.

Se conservaron todos los recursos gráficos anteriores. Los banners raster pesados y las insignias externas dejan de participar del README. No se agregan tarjetas de estadísticas: las contribuciones nativas de GitHub siguen disponibles sin duplicar métricas ni introducir proveedores visuales.

## Auditoría editorial

El perfil anterior ya tenía una selección razonable de proyectos y resumen en inglés; se conservan esas decisiones. Su identidad dependía de un banner raster, iconos de un proveedor y una tabla de proyectos; faltaban un recorrido visual propio, contacto verificable y distinción explícita entre tecnologías probadas e intereses.

Los README existentes eran breves y no explicaban suficientemente ejecución, arquitectura o límites. La API de productos no aplica el servicio desde el controlador. Las prácticas Python usan rutas locales, configuración de ejemplo y dependencias antiguas. PHP reúne ejercicios independientes; no debe venderse como un sistema completo. Pages conservaba Neo Jumper, mientras su descripción pública decía “Cifrador Cristhian”; esa descripción no corresponde al contenido inspeccionado.

## Pins recomendados

En [el perfil](https://github.com/CristhianStorm), elegir **Customize your pins**:

1. Curso-sincronico: aplicación con mayor amplitud funcional y técnica.
2. java: API pequeña y fácil de recorrer para evaluar backend.
3. Python: servicios y contenedores como evidencia complementaria.
4. CristhianStorm.github.io: presentación visual e interfaces.
5. PHP: prácticas; opcional si se quiere priorizar sólo trabajos más completos.

## Descripciones y topics sugeridos

Aplicar en cada repositorio: **About → engranaje → Description / Topics**. Son propuestas, no cambios de configuración ya aplicados.

| Repositorio | Descripción | Topics |
| --- | --- | --- |
| Curso-sincronico | Aplicación académica de tutorías: consultas, foros e informes con Java, Spring Boot y Oracle. | java, spring-boot, spring-security, jpa, oracle, academic-project |
| java | API REST educativa de productos con Spring Boot, validaciones y H2. | java, spring-boot, rest-api, spring-data-jpa, h2-database, learning-project |
| Python | Prácticas de Python, Flask, MySQL y Docker: fundamentos y servicios web. | python, flask, mysql, docker, learning-project |
| PHP | Ejercicios de PHP, arreglos, orientación a objetos e interfaces web. | php, oop, html, css, learning-project |
| CristhianStorm.github.io | Portafolio de Cristhian Storm · Full Stack Developer · CS // Software Lab. | portfolio, github-pages, html, css, javascript |
| CristhianStorm | Perfil de Cristhian Storm: proyectos, ingeniería y tecnologías verificables. | github-profile, profile-readme, software-engineering |

## Tareas manuales tras la revisión

- Revisar y fusionar el PR del perfil; la portada pública cambia al fusionarse, no al crear el PR.
- Revisar y fusionar los PR de documentación.
- Revisar y fusionar el PR web; comprobar **Settings → Pages → Build and deployment** sin alterar el origen existente. Si se sirve desde rama: main, /(root).
- En **Edit profile**, considerar bio: “Full Stack Developer · Java y Spring Boot · Interfaces, servicios y datos.” y Website: https://cristhianstorm.github.io/ una vez publicada la nueva portada.
- Elegir pins y aplicar las descripciones/topics propuestos.
- Agregar LinkedIn o correo sólo después de confirmar el canal que se desea hacer público. No se reutiliza automáticamente el correo de la cuenta conectada.
- Antes de presentar tutorías como demo pública, realizar una revisión separada de configuración, credenciales, permisos y datos de prueba.

## Límites de la revisión

La auditoría técnica se basa en los seis repositorios públicos. No se ejecutaron sistemas conectados a bases de datos, correo o servicios institucionales. Los cambios de documentación no certifican funcionamiento ni seguridad. Las pruebas visuales cubren presentación, imágenes, temas y tamaños de pantalla; los detalles y capturas se entregan con los PR.
