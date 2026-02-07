# 🎮 Trimui Smart Pro & CrossMix OS – Guia Completo

Este repositório é um **guia prático, opinado e baseado em uso real** para quem
usa o **Trimui Smart Pro**, com foco no sistema **CrossMix OS**.
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
│
├─ HARDWARE.md
│
├─ crossmix/
│   ├─ emulators/
│   │   ├─ gba/
│   │   │   ├─ README.md
│   │   │   ├─ recommended-games.md
│   │   │   └─ per-game/
│   │   │
│   │   ├─ snes/
│   │   │   ├─ README.md
│   │   │   ├─ recommended-games.md
│   │   │   └─ per-game/
│   │   │
│   │   └─ ps1/
│   │       ├─ README.md
│   │       ├─ recommended-games.md
│   │       └─ per-game/
│   │
│   ├─ saves-states/   
│   │   └─ README.md
|   |   └─ per-game/
│   │
│   ├─ themes/
│   │   └─ recommended.md
|   |
|   ├─ apps/
|   |   └─ README.md
│   │   └─ recommended.md
│   │
│   ├─ portmaster/
│   │   ├─ README.md
│   │   ├─ recommended.md
│   │   ├─ problematic.md
│   │
│   └─ performance-tweaks.md

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
