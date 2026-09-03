# Mi página

Buzón de sugerencias interno: cualquiera del equipo entra, deja una idea y ve
las que ya dejaron los demás. GitHub guarda el proyecto, Netlify lo publica y
Supabase guarda lo escrito. Se armó pidiéndole todo a Claude, sin escribir
código (Sesión 7 del curso Claude for Business).

## De dónde salen los datos

Todo lo que se ve —nombres, mensajes— sale de la tabla `registros` en Supabase
(columnas `id`, `created_at`, `nombre`, `mensaje`). Nada se escribe a mano en
el HTML.

## Qué hace CLAUDE.md

El archivo que Claude lee solo en cada sesión sobre este repo: trae las reglas
para trabajar aquí (rama primero, avisar antes de tocar la base de datos, qué
llaves nunca deben quedar escritas).

## Para seguir trabajando aquí

1. Abre una sesión de Claude sobre este repositorio.
2. Pide el cambio; Claude lo hace en una rama, nunca directo sobre `main`.
3. Claude fusiona a `main` y publica solo, sin pedirlo aparte.

> Si deja de mostrar datos tras una semana sin uso, el proyecto gratuito de
> Supabase seguramente se pausó: despiértalo con **Resume project**.
