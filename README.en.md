<p align="center">
  <a href="README.md">Español</a> · <a href="README.en.md">English</a>
</p>

<h1 align="center">ICFES Master</h1>

<p align="center">
  <img src="src/assets/images/screenshot.png" alt="Screenshot of the ICFES Master homepage" width="800">
</p>

<p align="center">Practice and topics for the ICFES Saber 11, in Colombia.</p>

The student site is at [icfes-master.vercel.app](https://icfes-master.vercel.app/). The panel is [WEB-ICFES-Admin](https://github.com/ICFES-Master/WEB-ICFES-Admin) and the app is [app-icfes-master](https://github.com/ICFES-Master/app-icfes-master).

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/licencia-Apache--2.0-blue" alt="Licencia Apache 2.0"></a>
  <a href="https://github.com/ICFES-Master/WEB-ICFES-Master/actions/workflows/ci.yml"><img src="https://github.com/ICFES-Master/WEB-ICFES-Master/actions/workflows/ci.yml/badge.svg" alt="CI status"></a>
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

## Features

- Saber 11 questions and topics.
- Supabase shared with the admin and the app.
- Apache-2.0 license, CI, and `pnpm test`.

> [!NOTE]
> The scope is Colombia. Each country builds the exam differently, and this repo does not generalize
> that.

## Tech stack

- **Next.js 15, React 19, and Tailwind 4** — the platform.
- **Supabase** — data and session.
- **pnpm 9.15.9** — repo scripts.

## Quick start

```bash
cp .env.example .env.local
pnpm install
pnpm dev
```

> [!IMPORTANT]
> Copy `.env.example` to `.env.local` before `pnpm dev`. CI uses `ci.yml`.

## Usage

`pnpm test` runs the suite. Free, Pro, and Premium billing is off in 2026.

The decision is in [docs/es/decisions/billing-no-2026.md](docs/es/decisions/billing-no-2026.md).

> [!TIP]
> The long guide is in `docs/es/`. This page only keeps the startup.

## Contributing

> [!CAUTION]
> Do not turn on 2026 billing. `BILLING_ENABLED` stays false on purpose.

Repository of [ICFES Master](https://github.com/ICFES-Master).

> [!WARNING]
> Do not commit `.env.local`. Supabase keys stay local.

## License

Apache-2.0. The text is in [LICENSE](LICENSE).

## Documentation

Product documentation is in `docs/es/`: setup, frontend, backend, and decisions.
