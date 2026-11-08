# Créditos de modelos

Modelos de terceros (descargados de Sketchfab, convertidos al formato del mod). Confirmado por el autor (1 nov 2026): eran modelos **libres de uso, sin obligación de atribución**. Desde el 3 nov **ninguno se usa ya**: todos se rehicieron como modelos propios. Se dejan aquí como historial.

| Uso en el mod | Modelo original (carpeta) | Autor | Licencia |
|---|---|---|---|
| ~~Mazo del juez (`judge_gavel`)~~ | ~~minecraft-gavel~~ | — | **ya no se usa**: modelo propio desde el 3 nov (`tools/arte/gen_*.py`) |
| ~~Katana de Yuta y Espada de Kusakabe~~ | ~~katanasword-for-minecraft-weapons~~ | — | **ya no se usa**: modelo propio desde el 3 nov (`tools/arte/gen_*.py`) |
| ~~Hoja y Lanza construidas~~ | ~~iron-tools-minecraft~~ | — | **ya no se usa**: modelo propio desde el 3 nov (`tools/arte/gen_*.py`) |
| ~~Espada del Verdugo~~ | ~~minecraft-sword~~ | — | **ya no se usa**: modelo propio desde el 3 nov (`tools/arte/gen_*.py`) |
| ~~Buey Perforante (shikigami)~~ | ~~buffalo-minecraft~~ | — | **ya no se usa**: modelo propio desde el 1 nov (`tools/arte/`) |
| ~~Elefante Máximo (shikigami)~~ | ~~elephant-minecraft~~ | — | **ya no se usa**: modelo propio desde el 1 nov (`tools/arte/`) |
| ~~Ciervo Redondo (shikigami)~~ | ~~irish-elk-minecraft-mob~~ | — | **ya no se usa**: modelo propio desde el 1 nov (`tools/arte/`) |
| Mahoraga (shikigami) y su rueda (`fx_mahoraga_wheel`) | `mahoraga.glb` del autor, convertido con `tools/mahoraga_glb/` | Megambit | propio (la Espada de la Extinción, inventada, la añadió la conversión) |

**Texturas de objetos y armaduras:** las de los objetos añadidos del 22 al 24 oct (cobre y amatista, comida maldita, rituales, equipo y pergaminos) y las capas de armadura de cobre, uniforme, ropa de renegado y coraza maldita eran recoloreados de vanilla; desde el 31 oct son **propias**, dibujadas por código con `tools/arte/gen_objetos.py` (igual que los 6 objetos que usaban textura vanilla). Las texturas de bloque de `textures/block/` (altar, tanque de CE, geoda, pararrayos, mesa del titiritero, marca de tiza, velo) también son propias desde el 31 oct (`tools/arte/gen_bloques.py`).

## Sonidos

Todos de **[Freesound](https://freesound.org)** (archivos de `sonidos/`, copiados al mod en `assets/jjk/sounds/`). Cada sonido de Freesound tiene su licencia: **CC0** (sin atribución), **CC-BY** (citar al autor: va en esta tabla) o **CC-BY-NC** (sin uso comercial: aceptable en un mod gratuito, pero mejor evitarlo). La licencia y el autor salen en la página de cada sonido; tus descargas están en Freesound → tu perfil → *Downloaded sounds*.

| Sonido | Archivo(s) | Fuente | Autor | Licencia |
|---|---|---|---|---|
| Palmada (Boogie Woogie) | `clap_1…4` | Freesound | unfa (según los metadatos del archivo) | por confirmar |
| Cortes del Santuario | `slash_1`, `slash_2` | Freesound | por confirmar | por confirmar |
| Destello Negro | `black_flash_1`, `black_flash_2` | Freesound | por confirmar | por confirmar |
| Azul | `blue` | Freesound | por confirmar («Reverse Wind A») | por confirmar |
| Rojo | `red` | Freesound | por confirmar | por confirmar |
| Vacío Púrpura | `purple` | Freesound | qubodup («Ion Cannon», según los metadatos) | por confirmar |
| Dominios | `domain_open`, `domain_seal`, `domain_clash`, `domain_break` | Freesound | por confirmar | por confirmar |

## Librerías incluidas
- **Player Animation Library** (PAL) de ZigyTheBird (licencia MIT): https://github.com/ZigyTheBird/PlayerAnimationLibrary — animaciones del jugador.

## Compatibilidad opcional (no va dentro del mod)
- **EMI** de emilyploszaj (licencia MIT): https://github.com/emilyploszaj/emi — visor de recetas; si está instalado, muestra la Mesa del Titiritero y el yunque de herramientas malditas.
- **Mod Menu** de TerraformersMC (licencia MIT) — botón de configuración.
