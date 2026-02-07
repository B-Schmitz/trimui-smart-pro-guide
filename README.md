# 🎮 Trimui Smart Pro & CrossMix OS – Guia Completo

Este repositório é um **guia prático, opinado e baseado em uso real** para quem
usa o **TrimUI Smart Pro**, com foco no sistema **CrossMix OS**.
---

## 🎯 Para quem é este repositório?

- Quem acabou de comprar um **Trimui Smart Pro**
- Quem usa ou pretende usar **CrossMix OS**
- Quem prefere **configurar bem** antes de jogar
- Quem curte handheld, retro e custom firmware
- Quem quer saber *por que algo funciona (ou não)*

---

## 🚫 O que este repositório NÃO contém

- ❌ ROMs
- ❌ BIOS proprietárias
- ❌ Conteúdo ilegal ou protegido por direitos autorais

Este repositório entrega:
- ✅ Estrutura
- ✅ Configurações
- ✅ Boas práticas
- ✅ Documentação clara

ROMs e BIOS são responsabilidade do usuário.

---

## 📦 O que você vai encontrar aqui

- ⚙️ Configurações recomendadas por **emulador**
- 🎮 Ajustes **por jogo** (per-game configs)
- 💾 Organização de **saves e save states**
- 🔋 Tweaks de **performance e bateria**
- 🎨 Ajustes visuais que não matam performance
- 🚀 Guia prático do **PortMaster**
- 🧩 Recomendações de **acessórios físicos**
- 🧠 Observações do dia a dia com o console

---

## 🗂 Estrutura do repositório

```txt
crossmix/
  ├─ emulators/
  │   ├─ saves-states/
  │   │   ├─ gba/
  │   │   ├─ snes/
  │   │   └─ ps1/
  │   ├─ configs/
  │   │   ├─ gba.md
  │   │   ├─ snes.md
  │   │   └─ ps1.md
  │   └─ per-game/
  │       ├─ gba/
  │       ├─ snes/
  │       └─ ps1/
  │
  ├─ themes/
  │   ├─ recommended.md
  │
  ├─ portmaster/
  │   ├─ README.md
  │   ├─ recommended.md
  │   ├─ problematic.md
  │   └─ tweaks.md
  │
  └─ performance-tweaks.md
```

---

## 💾 Saves no CrossMix OS

Os **saves ficam no cartão SD**, organizados principalmente **por emulador**.

### Saves normais

Caminho mais comum:
```
/roms/<EMULADOR>/saves/
```

Exemplos:
- `/roms/PS/.pcsx_rearmed_libretro`
- `/roms/SFC/.snes9x_libretro/Super Mario World.3.state`

O nome do arquivo normalmente é **igual ao nome da ROM**.

---

## 🎯 Configurações por jogo (Per-Game)

Nem todo jogo roda bem com as mesmas configs.

Este repositório inclui ajustes para jogos que:
- Têm quedas de FPS
- Sofrem com áudio picotando
- Precisam de frameskip pontual
- Funcionam melhor sem shaders

Estrutura:
```
crossmix/emulators/per-game/<emulador>/<jogo>.md
```

Cada arquivo explica **o porquê** de cada ajuste.

---

## 🎨 Visual e interface

Foco em:
- Temas compatíveis com CrossMix OS
- Boa legibilidade na tela do TrimUI
- Ajustes de brilho e contraste
- Shaders leves e úteis

Nada de estética que sacrifica bateria.

---

## 🚀 PortMaster

O PortMaster funciona, mas **não é plug and play**.

Aqui você encontra:
- Ports que rodam bem
- Ports que exigem ajustes
- Ports que não compensam
- Problemas comuns documentados

---

## 🧩 Acessórios físicos

Recomendações baseadas em uso real:
- Cartões SD confiáveis
- Capinhas e cases adequados
- Películas (quando valem a pena)
- Cabos e adaptadores úteis
- O que não vale comprar

---

## 🤝 Contribuições

Sugestões são bem-vindas:
- Recomendações de jogos
- Configurações testadas
- Ajustes por jogo
- Melhorias de performance
- Correções de documentação
- Experiências reais

---
# 🎮 Trimui Smart Pro & CrossMix OS – Complete Guide

This repository is a **practical, opinionated, real-world guide** for people using
the **TrimUI Smart Pro**, with a focus on **CrossMix OS**.
---

## 🎯 Who is this repository for?

- Anyone who just bought a **Trimui Smart Pro**
- Users of **CrossMix OS** (or those planning to use it)
- People who prefer to **configure things properly** before playing
- Handheld, retro, and custom firmware enthusiasts
- Anyone who wants to understand *why something works (or doesn’t)*

---

## 🚫 What this repository does NOT contain

- ❌ ROMs
- ❌ Proprietary BIOS files
- ❌ Illegal or copyrighted content

This repository provides:
- ✅ Structure
- ✅ Configurations
- ✅ Best practices
- ✅ Clear documentation

ROMs and BIOS files are the user’s responsibility.

---

## 📦 What you’ll find here

- ⚙️ Recommended **per-emulator configurations**
- 🎮 **Per-game tweaks** (per-game configs)
- 💾 Save and save-state organization
- 🔋 Performance and battery tweaks
- 🎨 Visual adjustments that don’t kill performance
- 🚀 Practical **PortMaster** guide
- 🧩 Physical accessory recommendations
- 🧠 Day-to-day usage notes

---

## 🗂 Repository structure

```txt
crossmix/
  ├─ emulators/
  │   ├─ saves-states/
  │   │   ├─ gba/
  │   │   ├─ snes/
  │   │   └─ ps1/
  │   ├─ configs/
  │   │   ├─ gba.md
  │   │   ├─ snes.md
  │   │   └─ ps1.md
  │   └─ per-game/
  │       ├─ gba/
  │       ├─ snes/
  │       └─ ps1/
  │
  ├─ themes/
  │   ├─ recommended.md
  │
  ├─ portmaster/
  │   ├─ README.md
  │   ├─ recommended.md
  │   ├─ problematic.md
  │   └─ tweaks.md
  │
  └─ performance-tweaks.md
```

---

## 💾 Saves in CrossMix OS

Saves are stored on the **SD card**, usually **organized by emulator**.

### Normal saves

Most common path:
```
/roms/<EMULATOR>/saves/
```

Examples:
- `/roms/PS/.pcsx_rearmed_libretro`
- `/roms/SFC/.snes9x_libretro/Super Mario World.3.state`

The save file name usually **matches the ROM name**.

---

## 🎯 Per-Game Configurations

Not every game behaves well with the same settings.

This repository includes tweaks for games that:
- Suffer from FPS drops
- Have audio stuttering
- Need occasional frameskip
- Run better without shaders

Structure:
```
crossmix/emulators/per-game/<emulator>/<game>.md
```

Each file explains **why** each tweak exists.

---

## 🎨 Visuals and interface

Focus areas:
- Themes compatible with CrossMix OS
- Good readability on the TrimUI screen
- Brightness and contrast adjustments
- Lightweight, useful shaders

No aesthetics that sacrifice battery life.

---

## 🚀 PortMaster

PortMaster works, but it’s **not plug-and-play**.

Here you’ll find:
- Ports that run well
- Ports that need tweaks
- Ports that aren’t worth the effort
- Documented common issues

---

## 🧩 Physical accessories

Recommendations based on real usage:
- Reliable SD cards
- Proper cases and sleeves
- Screen protectors (when worth it)
- Useful cables and adapters
- What’s not worth buying

---

## 🤝 Contributions

Suggestions are welcome, especially:
- Game recommendations
- Tested configurations
- Per-game tweaks
- Performance improvements
- Documentation fixes
- Real-world experiences
