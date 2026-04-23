# Marketing Multiagentes — DaemonCraft

Repo central para todos los activos de marketing, contenido y growth de DaemonCraft.

## Estructura

```
content/
  redes-sociales/     # Posts para X, Instagram, TikTok
  email-funnel/       # Emails de onboarding y nutrición
  blog/               # Artículos técnicos y de marca
  video/              # Scripts, storyboards, assets de video
  pr/                 # Press releases, kit de prensa
  influencers/        # Investigación, pitches, seguimiento

assets/
  imagenes/           # Imágenes generadas, screenshots
  videos/             # Videos exportados
  brand/              # Logos, paletas, guías de marca

data/
  metrics/            # Métricas de growth
  experiments/        # Resultados de experimentos A/B
```

## Agentes

Cada carpeta tiene un "dueño" (agente) responsable:

| Carpeta | Agente | Estado |
|---------|--------|--------|
| content/redes-sociales | Agente Marca | 🟡 Activo |
| content/email-funnel | Agente Growth | 🟡 Activo |
| content/blog | Agente Marca + Tech | 🔴 Pendiente |
| content/video | Agente Marca | 🟡 Activo |
| content/pr | Agente Growth | 🔴 Pendiente |
| content/influencers | Agente Growth | 🟡 Activo |
| assets/ | Agente Marca | 🟡 Activo |
| data/ | Agente Growth | 🔴 Pendiente |

## Cómo trabajar

1. Cada agente trabaja en su branch: `agente/[nombre]`
2. PRs a `main` para integrar
3. La memoria vive en Obsidian: `~/Documents/Obsidian Vault/DaemonCraft/`
4. Daily sync automático entre agentes
