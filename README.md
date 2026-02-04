# Codex Skills Repository

Este repositorio sirve como catálogo y plantilla para **skills de Codex**. Aquí encontrarás convenciones, estructura recomendada y un ejemplo listo para clonar cuando quieras crear nuevas skills.

## Objetivo
- Centralizar skills reutilizables para Codex.
- Mantener un formato consistente en la documentación de cada skill.
- Facilitar el versionado, revisión y contribución de nuevas skills.

## Estructura sugerida
```
skills/
  <nombre-skill>/
    SKILL.md
    references/
    scripts/
    assets/
```

- **SKILL.md**: Documento principal con propósito, activación, flujo y salida esperada.
- **references/**: Material de apoyo (APIs, docs internas, glosarios).
- **scripts/**: Scripts opcionales que automatizan pasos del workflow.
- **assets/**: Plantillas o recursos reutilizables.

## Convenciones
- Usa nombres en `kebab-case` para las carpetas de skills.
- Mantén el contenido en español, excepto comandos o snippets técnicos.
- Especifica claramente cuándo se debe activar la skill.
- Describe entradas, salidas y pasos mínimos del workflow.

## Plantilla
Clona la plantilla en `skills/skill-template/` para crear una nueva skill:
```
cp -R skills/skill-template skills/mi-nueva-skill
```

Luego actualiza los campos dentro de `SKILL.md`.

## Contribuir
1. Crea una rama por skill o ajuste.
2. Valida que la skill tenga un propósito claro y pasos concretos.
3. Abre un PR describiendo el valor agregado.

---

Si necesitas que ajustemos el formato a un flujo específico de Codex, abre un issue o propone cambios en la plantilla.
