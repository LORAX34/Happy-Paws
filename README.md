# Happy-Paws 
Proyecto de mascotas Happy Paws 
 
 ![Badge en Desarollo](https://img.shields.io/badge/STATUS-EN%20DESAROLLO-green)



Install
-bun
-tailwind
-vite con vue
-laravel


FRONTEND:

-Bun:
<pre>
<code>
curl -fsSL https://bun.sh/install | bash
</code>
</pre>


-Tailwind:

Instalar 

<pre>
<code>
npm install tailwindcss @tailwindcss/vite
</code>
</pre>

```javascript
esto es en vite.config.js

import { defineConfig } from 'vite'

import tailwindcss from '@tailwindcss/vite'/<-esta

export default defineConfig({
  plugins: [
    tailwindcss(),/<-esta
  ],
})
```




Añadir un @import a su archivo CSS que importa Tailwind CSS.

```css
@import "tailwindcss";
```



Ejecute su proceso de construcción con npm run dev o cualquier comando que esté configurado en su archivo. package.json

<pre>
<code>
npm run dev
</code>
</pre>

Asegúrese de que su CSS compilado esté incluido en el <head> (su marco podría manejar esto por usted), luego comience a usar las clases de utilidad de Tailwindics para diseñar su contenido.

```HTML
<head>
  <link href="/dist/styles.css" rel="stylesheet"> /<- asi queda 
</head>
  <h1 class="text-3xl font-bold underline"> /<-ejemplo de que funciona
    Hello world!
  </h1>
```


-Vite/Vue:

<pre>
<code>
$ bun create vite
</code>
</pre>

BACKEND:

-Laravel:

Crear proyecto 
<pre>
<code>
laravel new example-app
</code>
</pre>

Luego de creado dirigirce a la carpeta e inicializarlo 

<pre>
<code>
cd example-app
npm install && npm run build
composer run dev
</code>
</pre>

Herramientas:

-Git
-GitHub
-Supabase
-Vercel
