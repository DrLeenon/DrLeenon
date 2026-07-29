# Jalid Díaz

**Desarrollo y Gestión de Software · Chiriquí, Panamá**

Hago software para negocios pequeños que llevan su operación en Excel o en
cuaderno y que, por eso mismo, no saben cuánto les cuesta de verdad lo que
venden.

---

## Proyectos

### [GlassBeat](https://github.com/DrLeenon/GlassBeat) · Java · JavaFX · MySQL

Reproductor de escritorio con biblioteca compartida: varios equipos inician
sesión contra una misma base MySQL y una canción subida desde un computador
suena en el otro, con presencia en vivo de quién está escuchando qué.

Contraseñas con PBKDF2-HMAC-SHA256 y salt por usuario, sin nada en claro en
la base. Se empaqueta con `jpackage` en un `.exe` que lleva su propio runtime
y corre en un equipo sin Java instalado.

El README explica por qué cada cliente habla JDBC directo con MySQL en vez de
pasar por un API REST, y qué se rompería si el proyecto creciera.

### Bonnyta's Cakes & More · PWA · Supabase · PostgreSQL

Costeo de recetas, pedidos e inventario para una repostería. **En producción y
en uso diario**: sustituyó un Excel y hoy se usa desde el celular en plena
cocina para escalar recetas.

El hallazgo que lo justificó todo: galletas y brownies aparecían con 98% de
margen. El costeo del sistema mostró que ese número era mentira — esas recetas
no tenían los ingredientes cargados. Se estaba vendiendo a ciegas.

Sin frameworks ni paso de compilación: HTML, CSS y JavaScript hablando directo
con PostgREST. Funciona sin señal mostrando la última copia conocida.
*Repositorio privado.*

### AgroGest · en curso

Gestión de una finca de café, tomate y pimentón en Tierras Altas. Antes del
software va un diagnóstico de rentabilidad por lote y por cultivo, hecho sobre
los cuadernos y recibos reales de la finca: primero se averigua qué está
perdiendo plata, después se decide qué automatizar.

---

## Herramientas

**Lenguajes** · Java · JavaScript · SQL · Python · Dart
**Bases de datos** · PostgreSQL · MySQL · Supabase
**Otros** · JavaFX · Maven · Flutter · Git

---

## Estudios

Segundo año de **Licenciatura en Desarrollo y Gestión de Software**
Universidad Tecnológica de Panamá — Centro Regional de Chiriquí

---

## Contacto

¿Tu negocio se lleva en un Excel que ya nadie entiende? Escríbeme.

**jalid26diaz@gmail.com**
