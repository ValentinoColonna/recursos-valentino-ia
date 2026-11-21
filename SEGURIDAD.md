# SEGURIDAD · El detector de agujeros de Cloudflare · Valentino IA

**La herramienta:** security-audit-skill, de Cloudflare, gratis y abierta (MIT), en https://github.com/cloudflare/security-audit-skill. Es el repositorio oficial.

**Qué hace, según su repositorio:** convierte a tu agente de código en un auditor de seguridad. Revisa tu app por etapas, y un segundo agente comprueba cada falla antes de reportarla.

## Qué necesitás

Claude Code u otro agente de código, y la terminal.

## Cómo instalarla

1. En la carpeta de tu proyecto, en la terminal:
   ```
   npx skills add https://github.com/cloudflare/security-audit-skill --skill security-audit
   ```
   Si la querés para todos tus proyectos, agregá `--global` al final.
2. **Abrí Claude Code** en ese proyecto y pedile: «Usá la skill security-audit para auditar este proyecto».
3. **Leé el informe:** cada falla viene comprobada, con qué hacer.

**La letra chica:**
- te dice qué arreglar, no lo arregla solo;
- no hace a tu app «segura» de golpe: encuentra lo que encuentra.

*Valentino IA · fuente: el README del repositorio, leído en noviembre de 2026*
