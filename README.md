# Happy-Paws 
Proyecto de mascotas Happy Paws 
 
 ![Badge en Desarollo](https://img.shields.io/badge/STATUS-EN%20DESAROLLO-green)


 ##Índice

*[Índice](#índice)

*[Install](#Install)

*[Frontend](#FRONTEND:)

*[Backend](#BACKEND:)

*[Herramientas](#Herramientas:)



#Install
-bun
-tailwind
-vite con vue
-laravel


#FRONTEND:

-Bun:
<pre>
<code>
curl -fsSL https://bun.sh/install | bash
</code>
</pre>


-Tailwind:
//Primero esto
npm install tailwindcss @tailwindcss/vite

//Segundo esto
esto es en vite.config.js

import { defineConfig } from 'vite'

import tailwindcss from '@tailwindcss/vite'/<-esta

export default defineConfig({
  plugins: [
    tailwindcss(),/<-esta
  ],
})

//Tercero esto

Añadir un @import a su archivo CSS que importa Tailwind CSS.

@import "tailwindcss";


//Cuarto esto

Ejecute su proceso de construcción con npm run dev o cualquier comando que esté configurado en su archivo. package.json

npm run dev



//Quinto 

Asegúrese de que su CSS compilado esté incluido en el <head> (su marco podría manejar esto por usted), luego comience a usar las clases de utilidad de Tailwindics para diseñar su contenido.


<head>
  <link href="/dist/styles.css" rel="stylesheet"> /<- asi queda 
</head>
  <h1 class="text-3xl font-bold underline"> /<-ejemplo de que funciona
    Hello world!
  </h1>

-Vite/Vue:

$ bun create vite



#BACKEND:

-Laravel:

//Primero 
laravel new example-app

//Segundo

cd example-app
npm install && npm run build
composer run dev



#Herramientas:

-Git
-GitHub
-Supabase
-Vercel
