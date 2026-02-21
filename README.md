# BetProLatam 🎯

Sitio web de guías de apuestas deportivas y comparativa de casas para Latinoamérica.

---

## 📁 Estructura del proyecto

```
betprolatam/
├── index.html              ← Página principal
├── README.md               ← Este archivo
└── legal/
    ├── aviso-legal.html
    ├── politica-privacidad.html
    ├── juego-responsable.html
    └── sobre-nosotros.html
```

---

## 🚀 Cómo subir a GitHub + Vercel (paso a paso)

### PASO 1 — Instala Git (si no lo tienes)
Descarga desde: **https://git-scm.com/downloads**  
Instala con todas las opciones por defecto. En Windows elige "Git Bash".

### PASO 2 — Crea cuenta en GitHub
Ve a **https://github.com** → Sign up → cuenta gratuita.

### PASO 3 — Crea un repositorio nuevo
1. En GitHub clic en **"New"** (botón verde arriba a la izquierda)
2. Nombre: `betprolatam`
3. Visibilidad: **Public**
4. ❌ NO marques ningún checkbox (sin README, sin gitignore)
5. Clic en **"Create repository"**
6. Copia la URL que aparece: `https://github.com/TUNOMBRE/betprolatam.git`

### PASO 4 — Sube los archivos

Organiza los archivos en tu PC así:
```
📂 betprolatam/
├── index.html
└── 📂 legal/
    ├── aviso-legal.html
    ├── politica-privacidad.html
    ├── juego-responsable.html
    └── sobre-nosotros.html
```

Abre **Git Bash** (o Terminal en Mac) y escribe:

```bash
# Entra a la carpeta (cambia la ruta según donde la guardaste)
cd C:/Users/TuNombre/Downloads/betprolatam

# Inicia el repositorio
git init

# Agrega todos los archivos
git add .

# Crea el primer commit
git commit -m "Lanzamiento inicial BetProLatam"

# Conecta con GitHub (reemplaza TUNOMBRE con tu usuario real)
git remote add origin https://github.com/TUNOMBRE/betprolatam.git

# Sube todo a GitHub
git branch -M main
git push -u origin main
```

Si te pide usuario y contraseña: usa tu email y contraseña de GitHub.  
Si da error de contraseña: GitHub pide "Personal Access Token" — ve a GitHub → Settings → Developer settings → Tokens → New token.

### PASO 5 — Despliega en Vercel

1. Ve a **https://vercel.com**
2. Clic en **"Sign Up"** → **"Continue with GitHub"**
3. Clic en **"Add New Project"**
4. Selecciona tu repositorio `betprolatam`
5. En la pantalla de configuración NO cambies nada → clic **"Deploy"**
6. Espera ~30 segundos → ¡Tu sitio estará en vivo en `betprolatam.vercel.app`!

### PASO 6 — (Recomendado) Dominio propio
Un dominio `.com` da mucha más credibilidad a los programas de afiliados.
1. Compra `betprolatam.com` en **Namecheap.com** (~$12 USD/año)
2. En Vercel → tu proyecto → **Settings → Domains**
3. Escribe tu dominio → Vercel te da los DNS a configurar
4. En Namecheap → Domain → DNS → pon los valores que da Vercel
5. En 24h tu dominio estará activo

---

## 🔄 Actualizar el sitio (después del primer deploy)

Cada vez que edites archivos localmente:

```bash
# Desde la carpeta del proyecto
git add .
git commit -m "Descripción breve del cambio"
git push
```

Vercel detecta el push automáticamente y actualiza el sitio en ~20 segundos.

---

## 🔗 Insertar links de afiliado cuando te aprueben

Abre `index.html` con cualquier editor de texto (Notepad, VS Code, etc.) y busca y reemplaza:

| Buscar | Reemplazar con |
|--------|----------------|
| `#bet365` | Tu link real de Bet365 |
| `#betano` | Tu link real de Betano |
| `#betsson` | Tu link real de Betsson |
| `#inkabet` | Tu link real de Inkabet |
| `#telegram` | El link de tu canal de Telegram |

Luego vuelve a hacer `git add . && git commit -m "Links afiliados" && git push`

---

## 📋 Programas de afiliados — Dónde registrarte

| Casa | Programa | URL para registrarse |
|------|----------|---------------------|
| **Bet365** | Bet365 Affiliates | bet365affiliates.com |
| **Betano** | Betano Partners | betanopartners.com |
| **Betsson** | Betsson Affiliates | betssonaffiliates.com |
| **Inkabet** | Inkabet Afiliados | inkabet.pe → pie de página → Afiliados |

**Documentos que te pedirán:**
- DNI escaneado (ambos lados)
- Selfie sosteniendo el DNI
- URL de tu sitio web (la de Vercel)
- Número de cuenta o Payoneer para cobrar
- Formulario con tus datos personales

---

## ✅ Checklist antes de postular

- [ ] Sitio publicado y accesible en Vercel
- [ ] `/legal/aviso-legal.html` accesible
- [ ] `/legal/politica-privacidad.html` accesible
- [ ] `/legal/juego-responsable.html` accesible
- [ ] `/legal/sobre-nosotros.html` accesible
- [ ] Advertencias +18 visibles en la web
- [ ] Email de contacto creado y funcionando
- [ ] Cuenta en Payoneer creada (payoneer.com)

---

© 2025 BetProLatam
