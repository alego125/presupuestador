# NovaPrint 3D – Generador de Presupuestos

App web progresiva (PWA) para generar presupuestos profesionales.  
Instalable en Android · Funciona offline · Genera PDF

🔗 **[Abrir la app →](https://TU_USUARIO.github.io/novaprint-app/)**

---

## ✨ Funcionalidades

- Presupuestos completos con datos de cliente, emisor e ítems
- Cálculo automático de subtotal, IVA configurable y total
- Condiciones de pago, tiempo de entrega, observaciones
- Generación de PDF / impresión directa
- Instalable como app en Android (PWA)
- Funciona sin internet una vez instalada
- Cambio de logo desde la misma app

## 🖼️ Cambiar el logo

**Opción 1 – Desde la app** (solo en tu dispositivo):  
Tocá el botón ✏️ sobre el logo en la barra superior.

**Opción 2 – Para todos los dispositivos**:  
Reemplazá el archivo `logo/logo.png` en este repositorio.  
En 30 segundos se actualiza en la versión online.

## 📁 Estructura

```
novaprint-app/
├── index.html              ← App completa
├── manifest.json           ← Config PWA
├── sw.js                   ← Service Worker (offline)
├── logo/
│   └── logo.png            ← Logo de la empresa ★
├── assets/
│   └── icons/              ← Íconos para Android
└── .github/
    └── workflows/
        └── deploy.yml      ← Deploy automático
```

## 🚀 Deploy en GitHub Pages

1. Subí este repositorio a GitHub
2. Andá a **Settings → Pages**
3. En *Source* seleccioná **GitHub Actions**
4. Hacé un push a `main` → se deploya automáticamente

## 📲 Instalar en Android

1. Abrí Chrome en tu celular
2. Navegá a la URL de GitHub Pages
3. Tocá el banner *"Instalar app"* o el menú → *"Agregar a pantalla de inicio"*

---

*NovaPrint 3D · Neuquén, Argentina*
