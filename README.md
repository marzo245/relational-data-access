# Relational Data Access

Este proyecto fue desarrollado siguiendo la guía oficial de Spring: [Accessing Relational Data using JDBC with Spring](https://spring.io/guides/gs/relational-data-access). El objetivo es proporcionar una base para el acceso a datos relacionales en aplicaciones Java, empleando buenas prácticas y estándares recomendados por la comunidad Spring.

## Características

- Abstracción para el acceso a bases de datos relacionales.
- Soporte para múltiples motores SQL (ejemplo: H2, MySQL, PostgreSQL).
- Uso de JDBC y Spring JDBC Template.
- Ejemplos de operaciones CRUD (Crear, Leer, Actualizar, Eliminar).
- Código modular y fácil de extender.

## Instalación

Clona este repositorio en tu entorno local:

```bash
git clone https://github.com/marzo245/relational-data-access.git
cd relational-data-access
```

Importa el proyecto en tu IDE favorito como un proyecto Maven o Gradle.

## Uso

Ejecuta la aplicación principal desde tu IDE o usando Maven:

```bash
./mvnw spring-boot:run
```

## Estructura del Proyecto

- `/src`: Código fuente principal de la aplicación.
- `/test`: Pruebas unitarias y de integración.

## Pruebas

Para ejecutar las pruebas:

```bash
./mvnw test
```

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o pull request para discutir cambios mayores antes de proponerlos.

1. Haz un fork del proyecto.
2. Crea una rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -am 'Agrega nueva funcionalidad'`).
4. Push a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más información.

## Contacto

Para dudas o sugerencias, abre un Issue en el repositorio o contacta a [marzo245](https://github.com/marzo245).
