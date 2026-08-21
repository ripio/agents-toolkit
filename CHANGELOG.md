# Changelog - Ripio Agents Toolkit

## [Unreleased] - 2026-08-21

### Corregido
- Aclarada la decisión entre Ramps y CaaS: Ramps corresponde al flujo self-custodial; CaaS corresponde al flujo donde Ripio custodia y puede incluir rieles locales.
- Aclarado que integrar ambos productos solo aplica cuando existen flujos separados con modelos de custodia distintos.
- Reescrito el ejemplo de neobank para no presentar Ramps + CaaS como requisito para combinar rieles locales y custodia.

### Archivos afectados
- `Ripio Business - Brief for AI Assistants.md`
- `README.md`

### Decisiones técnicas
- Se mantuvo la posibilidad de combinar productos, pero se convirtió en una excepción condicionada por flujos separados, no en la recomendación por defecto.
