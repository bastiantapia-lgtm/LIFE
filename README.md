# LIFE

Sistema de desarrollo profesional con mecánicas de RPG.

## Stack actual (Sesión 1A — PWA)

- HTML estático (vanilla)
- Service Worker para offline
- PWA instalable en iOS/Android
- Deploy: Vercel

## Próximas sesiones

- **Sesión 1B**: Migración a Vite + React (en progreso)
- **Sesión 2**: Supabase (auth + DB sync)
- **Sesión 3**: Web Push notifications (pomodoro real)
- **Sesión 4**: Google Calendar OAuth + Claude API

## Stack final

- Vite + React
- Supabase (Auth + Postgres + Edge Functions)
- Vercel deploy
- Web Push notifications

---

## Deploy local (para testing)

```bash
# Servidor local cualquiera (necesario para que SW funcione)
python3 -m http.server 8000
# o
npx serve .
```

Abrir `http://localhost:8000`

## Deploy producción

Push a `main` → Vercel hace auto-deploy.
