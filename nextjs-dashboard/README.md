# Next.js Dashboard Project

Een moderne dashboard applicatie gebouwd met Next.js 15, React, TypeScript en Tailwind CSS.

## 🚀 Features

- **Modern Dashboard Interface**: Overzichtelijke dashboard met verschillende secties
- **Invoices Management**: Volledige CRUD functionaliteit voor facturen
- **Customer Management**: Klantbeheer met zoekfunctionaliteit
- **Responsive Design**: Werkt perfect op desktop en mobiel
- **TypeScript**: Volledige type safety
- **Tailwind CSS**: Moderne styling met utility-first CSS

## 📋 Pagina's

- **Dashboard Overview** (`/dashboard`) - Hoofdpagina met overzicht
- **Invoices** (`/dashboard/invoices`) - Factuurbeheer met zoeken en paginatie
- **Customers** (`/dashboard/customers`) - Klantbeheer

## 🛠️ Technologieën

- **Next.js 15.3.2** - React framework met App Router
- **React 19** - UI library
- **TypeScript 5.7.3** - Type safety
- **Tailwind CSS 3.4.17** - Styling
- **NextAuth.js 5.0.0-beta.25** - Authenticatie
- **PostgreSQL** - Database
- **pnpm** - Package manager

## 🚀 Installatie & Starten

### Vereisten
- Node.js (versie 18 of hoger)
- pnpm (package manager)

### Stappen

1. **Clone het project**
   ```bash
   git clone <repository-url>
   cd nextjs-dashboard
   ```

2. **Installeer dependencies**
   ```bash
   pnpm install
   ```

3. **Start de development server**
   ```bash
   pnpm dev
   ```

4. **Open je browser**
   - Ga naar: `http://localhost:3000` (of de poort die wordt getoond in de terminal)
   - Voor de invoices pagina: `http://localhost:3000/dashboard/invoices`

## 📁 Project Structuur

```
nextjs-dashboard/
├── app/
│   ├── dashboard/          # Dashboard routes
│   │   ├── (overview)/     # Dashboard overview pagina
│   │   ├── customers/      # Klanten pagina
│   │   └── invoices/       # Facturen pagina
│   ├── ui/                 # Herbruikbare UI componenten
│   ├── lib/                # Utility functies en data
│   └── globals.css         # Global styles
├── public/                 # Statische bestanden
└── package.json           # Dependencies en scripts
```

## 🔧 Available Scripts

- `pnpm dev` - Start development server
- `pnpm build` - Build voor productie
- `pnpm start` - Start productie server

## 🎨 UI Componenten

Het project bevat verschillende herbruikbare componenten:
- **Button** - Styled buttons
- **Search** - Zoekfunctionaliteit
- **Table** - Data tabellen
- **Skeletons** - Loading states
- **Forms** - Formulier componenten

## 📚 Meer Informatie

Voor meer informatie over Next.js App Router, zie de [Next.js Learn Course](https://nextjs.org/learn).

## 🤝 Bijdragen

Pull requests zijn welkom! Voor grote wijzigingen, open eerst een issue om te bespreken wat je wilt veranderen.

## 📄 Licentie

Dit project is onderdeel van de Next.js Learn Course.
