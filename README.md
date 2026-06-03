# Invita Studio

Constructor estático de invitaciones digitales con:

- Entrada animada.
- Fondo, colores, música e iconos editables.
- Itinerario con iconos por punto.
- Pase personalizado por familia.
- QR por invitado/familia.
- Lista CSV de invitados.
- Exportación ZIP lista para Netlify, Vercel, Hostinger o GitHub Pages.

## Invitados por familia

En el constructor pega un CSV con columnas:

```csv
id,nombre,pases,mesa,ninos
franco-ortiz,Familia Franco Ortiz,2,5,no
lopez-garcia,Familia López García,4,12,si
```

El proyecto exportado usa enlaces como:

```text
index.html?guest=franco-ortiz
```

La misma invitación cambia automáticamente el nombre, pases, mesa, política de niños y QR.

## Publicación

Es un proyecto estático. Puedes subir `index.html` a Netlify, Vercel, Hostinger o GitHub Pages.
