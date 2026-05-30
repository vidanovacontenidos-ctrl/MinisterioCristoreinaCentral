# Ministerio Cristo Reina — Web

## Estructura del proyecto

```
WEB_CR/
├── index.html                  ← Página principal
├── pages/
│   ├── kids.html               ← Página Cristo Reina Kids
│   └── fundacion.html          ← Página Fundación (Misión La Madrid)
└── assets/
    ├── video/
    │   └── CR.mp4              ← Video de fondo del hero
    ├── images/
    │   ├── events/
    │   │   └── evento-ascenso.jpg
    │   ├── kids/
    │   │   ├── IMG05.jpg ... IMG16.jpg  (12 fotos)
    │   └── fund/
    │       ├── IMG01.jpg ... IMG25.jpg  (13 fotos)
    └── logo/
        └── logo-icon.png
```

## Para subir al servidor (cPanel / FTP)

1. Subir TODOS los archivos manteniendo esta estructura de carpetas
2. El archivo raíz es `index.html` — debe ir en `public_html/`
3. La carpeta `pages/` va dentro de `public_html/pages/`
4. La carpeta `assets/` va dentro de `public_html/assets/`

## Para agregar páginas nuevas (Jóvenes, Seminario, etc.)

1. Crear `pages/jovenes.html` copiando la estructura de `kids.html`
2. Crear `assets/images/jovenes/` con las fotos (nombrar IMG01.jpg, IMG02.jpg...)
3. Actualizar el link en `index.html` en la sección "Áreas"

## Pendiente completar

- [ ] Nombres reales de los pastores (sección Visión en index.html)
- [ ] Fotos de los pastores (reemplazar los avatares SVG)
- [ ] Número de WhatsApp real (buscar 5491100000000 y reemplazar)
- [ ] Link real de Mercado Pago (buscar mercadopago.com.ar y reemplazar)
- [ ] Página de Jóvenes
- [ ] Página de Seminario
- [ ] Ubicaciones reales de las iglesias hijas (sección Iglesias)
