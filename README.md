<p align="center">
  <a href="README.md">Español</a> · <a href="README.en.md">English</a>
</p>

<h1 align="center">ICFES Master</h1>

<p align="center">
  <img src="src/assets/images/screenshot.png" alt="Captura de la portada de ICFES Master" width="800">
</p>

<p align="center">Práctica y temas del ICFES Saber 11, en Colombia.</p>

La web de estudiantes está en [icfes-master.vercel.app](https://icfes-master.vercel.app/). El panel es [WEB-ICFES-Admin](https://github.com/ICFES-Master/WEB-ICFES-Admin) y la app es [app-icfes-master](https://github.com/ICFES-Master/app-icfes-master).

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/licencia-Apache--2.0-blue" alt="Licencia Apache 2.0"></a>
  <a href="https://github.com/ICFES-Master/WEB-ICFES-Master/actions/workflows/ci.yml"><img src="https://github.com/ICFES-Master/WEB-ICFES-Master/actions/workflows/ci.yml/badge.svg" alt="Estado de CI"></a>
</p>

<p align="center">
  <a href="https://skillicons.dev">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,supabase,pnpm&theme=dark&perline=6">
      <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,supabase,pnpm&theme=light&perline=6">
      <img alt="Next.js, React, TypeScript, Tailwind, Supabase, pnpm" src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,supabase,pnpm&perline=6">
    </picture>
  </a>
</p>

## ✨ Características

- Preguntas y temas del Saber 11.
- Supabase compartido con el admin y la app.
- Licencia Apache-2.0, CI y `pnpm test`.

> [!NOTE]
> El alcance es Colombia. Cada país arma el examen de otra forma, y este repo no lo generaliza.

## 🛠️ Tecnologías

- **Next.js 15, React 19 y Tailwind 4** — la plataforma.
- **Supabase** — datos y sesión.
- **pnpm 9.15.9** — scripts del repo.

## 🚀 Inicio rápido

```bash
cp .env.example .env.local
pnpm install
pnpm dev
```

> [!IMPORTANT]
> Copia `.env.example` a `.env.local` antes de `pnpm dev`. CI usa `ci.yml`.

## 📖 Uso

`pnpm test` corre la suite. El cobro de planes Free, Pro y Premium está apagado en 2026.

La decisión está en [docs/es/decisions/billing-no-2026.md](docs/es/decisions/billing-no-2026.md).

> [!TIP]
> La guía larga está en `docs/es/`. La portada solo deja el arranque.

## 🤝 Contribuir

> [!CAUTION]
> No actives el billing de 2026. `BILLING_ENABLED` queda en false a propósito.

Repositorio de [ICFES Master](https://github.com/ICFES-Master).

> [!WARNING]
> No subas `.env.local`. Las claves de Supabase se quedan en local.

## 📄 Licencia

Apache-2.0. El texto está en [LICENSE](LICENSE).

## 📚 Documentación

La documentación de producto está en `docs/es/`: setup, frontend, backend y decisiones.
