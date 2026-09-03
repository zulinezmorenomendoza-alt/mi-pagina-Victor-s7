# Mi página

Una página pública con un formulario que guarda lo que la gente escribe, y una
lista que muestra lo guardado.

Construida en la **Sesión 7 del curso Claude for Business**, sin escribir código:
todo se le pidió a Claude en español.

## Cómo está armado

| Pieza | Qué hace |
|---|---|
| **GitHub** | Guarda este proyecto y su historial |
| **Netlify** | Publica lo que hay aquí como página web |
| **Supabase** | Guarda lo que la gente escribe en el formulario |

## Cómo se cambia

1. Se abre una sesión de Claude sobre este repositorio.
2. Se le pide el cambio **en una rama**, no en `main`.
3. Claude fusiona la rama a `main` y publica automáticamente — no hace falta
   pedirlo aparte ni revisarlo antes.

> **Cada fusión cuenta como una publicación.** El plan gratuito de Netlify
> alcanza para unas veinte al mes, así que conviene juntar cambios pequeños en
> una sola rama antes de pedir el siguiente.

## Qué NO va en este repositorio

La llave `sb_publishable_` sí puede estar aquí: está hecha para andar a la vista.
La que empieza con `sb_secret_` o dice `service_role`, **nunca**.
