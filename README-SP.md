# SummonLib

SummonLib es una librería *asset-driven* para invocaciones/minions en mods de servidor para Hytale.  
Permite definir invocaciones mediante assets JSON y luego invocarlas o eliminarlas usando interacciones e ítems sin tener que codear lógica por cada summon.

## ¿Qué hace?

- **Invocaciones por assets**: define comportamiento y parámetros con assets `SummonConfig`.
- **Dos tipos de invocaciones** (por ahora):
  - **MODEL**: un modelo no-NPC que sigue al jugador con lógica de formación (sin navegación real; ignora bloques).
  - **NPC_ROLE**: una invocación basada en NPC (por ahora enfocada en aliados voladores) que se mueve con navegación real y colisiona con bloques.
- **Invocar y remover fácil**: conecta las acciones a través de Interactions y RootInteractions para que los ítems las usen.

## Links

- CurseForge: **[PON EL LINK AQUÍ]**
- Wiki / Documentación: **[PON EL LINK AQUÍ]**
- Issues / Reporte de bugs: usa GitHub Issues.

## Estado

Proyecto en desarrollo activo. Pueden haber cambios mientras se agregan nuevas features (formaciones, comportamientos adicionales, tuning más completo, etc.).

## Licencia

Ver `LICENSE`.
