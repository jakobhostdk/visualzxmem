# visualzxmem

Phosphor-lab visualization of the ZX Spectrum 48K memory map — 16 KB
ROM + 48 KB RAM shown as a 64 KB address ribbon with coloured zones
(display file, attributes, printer buffer, system variables, BASIC
area, stack). Live PC/SP markers, flashes on ULA reads from the
contended `$4000-$7FFF` region, synthetic boot/BASIC trace.

Companion to [visualz80](https://visualz80.traeck.it) and
[visualula](https://visualula.traeck.it); appears in
[visualzx](https://visualzx.traeck.it) as the MEM component.

## Deploy

Pushes to `main` build and deploy to the Hetzner swarm at
[visualzxmem.traeck.it](https://visualzxmem.traeck.it) via
`.github/workflows/deploy.yml`.
