# 🌌 ModderUI — Deep Blue Liquid Glass UI Framework  
**Version:** 3.0  
**Theme:** macOS/iOS Native Dark Mode • 3D Interactive UI • Liquid Glass  
**Author:** @modderboy  

ModderUI is a fully custom, ultra-modern UI framework designed to bring **liquid glass**, **macOS-inspired components**, and **electric blue gradients** into any web project.  
It is lightweight, powerful, and highly visual — perfect for dashboards, super apps, authentication systems, and ModderOS ecosystem projects.

---

# 🇬🇧 English Version

## ✨ Features
- Liquid Glass UI (blur, glass, glow, gradients)  
- Fully interactive 3D Components (cards, hover zones, tilt effects)  
- macOS/iOS-inspired Menubar, Sidebar, Context Menu  
- Dynamic Electric Blue color palette  
- Responsive layout grid system  
- Modal system with smooth scaling animations  
- Floating Dock (iOS/macOS style)  
- Calendar widget (v3)  
- Loading components (WiFi Loader v2)  
- Full Dark Mode by default  
- Strict variable-driven theming  
- Auto-adaptive shadows & glow  

---

## 📦 Folder Structure
```
modderui/
│
├── modderui.css      # Full UI Framework (this file)
├── README.md
└── demo/
    └── index.html     # Example usage
```

---

## 🚀 Installation

### Option 1 — Direct Link
```html
<link rel="stylesheet" href="modderui.css">
```

### Option 2 — Import into Django / Flask
```
static/
 └── css/
      └── modderui.css
```

Then:

```django
<link href="{% static 'css/modderui.css' %}" rel="stylesheet">
```

---

## 🧪 Usage Example

### Basic Glass Card
```html
<section class="card">
    <h1>Welcome to ModderUI</h1>
    <p>Liquid glass interface activated.</p>
</section>
```

### Button
```html
<button class="primary">Continue</button>
```

### Sidebar Item
```html
<div class="nav-item active">
    <span>Dashboard</span>
</div>
```

### Modal
```html
<div class="modal-overlay" id="modal">
    <div class="modal-content">
        <h2>Modal Title</h2>
        <p>Some text inside modal.</p>
    </div>
</div>
```

---

## 🎨 Color Variables
ModderUI uses a strict palette system:

```
--c-black: #02010a;
--c-prussian: #04052e;
--c-twilight: #140152;
--c-navy: #22007c;
--c-electric: #0d00a4;
```

Glass engine:

```
--glass-bg-base
--glass-bg-hover
--glass-border
--glass-shadow
--glass-blur
```

---

## 🧩 Components Included
| Component | Status | Description |
|----------|--------|-------------|
| macOS Menubar | ✔️ | Fully dynamic top menu |
| Liquid Sidebar | ✔️ | iPadOS/MacOS style |
| 3D Card Engine | ✔️ | 25-zone rotation grid |
| WiFi Loader | ✔️ | Liquid animated loader |
| Modal System | ✔️ | Scale-in glass modal |
| Calendar Widget | ✔️ | Customizable |
| Floating Dock | ✔️ | iOS bottom dock |
| Context Menu | ✔️ | Glass context panel |

---

## 🔥 Why ModderUI?
- Built for **high-end dashboards**  
- Designed for **ModderOS ecosystem**  
- Next-gen UI feeling without heavy JS  
- Perfect for:  
  - Admin panels  
  - SaaS dashboards  
  - Super apps  
  - Authentication UIs  
  - Web apps & mini apps  

---

# 🇺🇿 O‘zbekcha Versiya

## ✨ Xususiyatlari
- Liquid Glass UI (blur + shaffof + gradient)  
- 3D hover effektlar (kartalar, konteynerlar)  
- macOS/iOS uslubidagi menyu bar & sidebar  
- Electric Blue palitra (Modder-style)  
- Grid systema (auto responsive)  
- Modal tizimi (smooth scale animation)  
- WiFi Loader — animatsion yuklovchi  
- Floating Dock — iOS style  
- Kalendar widget  
- To‘liq Dark Mode  
- CSS o‘zgaruvchilar orqali boshqariladi  

---

## 📦 Loyihaning Tuzilishi
```
modderui/
│
├── modderui.css
└── demo/
    └── index.html
```

---

## 🚀 O‘rnatish

### Variant 1 — HTML orqali ulash:
```html
<link rel="stylesheet" href="modderui.css">
```

### Variant 2 — Django Static:
```django
<link href="{% static 'css/modderui.css' %}" rel="stylesheet">
```

---

## 🧪 Oddiy Foydalanish

### Glass Card:
```html
<section class="card">
    <h1>ModderUI ishga tushdi</h1>
</section>
```

### Tugma:
```html
<button class="primary">Davom etish</button>
```

### Sidebar item:
```html
<div class="nav-item active">Bosh sahifa</div>
```

### Modal:
```html
<div class="modal-overlay active">
    <div class="modal-content">
        <h2>Sarlavha</h2>
    </div>
</div>
```

---

## 🔥 Nega ModderUI?
- Juda chiroyli, zamonaviy, premium UI  
- ModderOS tizimlari uchun mos  
- Kam kod bilan katta effekt  
- Dashboard, admin panel, super app — hammasiga to‘g‘ri keladi  

---

# 👨‍💻 Developer
**Created by:** @modderboy  
**Framework:** ModderUI v3.0  
**License:** All rights reserved.

