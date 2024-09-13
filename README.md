# Base para blog estático

1. clonar repositorio
2. instalar paquetes
```
npm intall
```
3. abrir en local
```
npm run dev
```
4. agregar nuevo-post en formato `.md` o `mdx` dentro de carpeta `blog` con formato expresado en `config.ts`
```
src/
├── content/
│   ├── blog/
│   │   └── nuevo-post.md
│   └── config.ts
```
5. crear build para subir
```
npm run build
```
6. ver version build
```
npm run preview
```