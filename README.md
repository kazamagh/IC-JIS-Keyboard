# IC-JIS

**A Technical Proposal for the Evolution of the Japanese Keyboard Layout**

IC-JIS is a technical proposal that explores how the Japanese JIS keyboard layout can be reinterpreted for modern programmable keyboards.

Rather than inventing an entirely new keyboard standard, IC-JIS looks at the existing Japanese keyboard architecture, especially the keys surrounding the spacebar, and asks how those accumulated design elements can be connected with contemporary practices such as split spacebars, Mod-Tap, VIA/QMK, and compact keyboard layouts.

## Why IC-JIS?

The Japanese JIS keyboard has evolved around the requirements of Japanese text input.

As a result, it provides several dedicated keys around the spacebar that do not normally exist on ANSI or ISO keyboards. These keys are often discussed only in the context of Japanese input.

However, programmable keyboards have changed the way we can think about these physical key positions.

With technologies and practices such as VIA, QMK, Mod-Tap, layers, and split spacebars, the keys surrounding the spacebar can serve more general purposes while continuing to support efficient Japanese input.

IC-JIS explores this connection.

The goal is not simply to preserve the traditional JIS layout, nor to replace ANSI, ISO, or JIS with another standard.

The goal is to identify useful design principles already present in Japanese keyboard history and reconnect them with modern keyboard design.

## Core Idea

IC-JIS focuses particularly on the area around the spacebar.

This area provides an interesting point of convergence between:

- traditional Japanese input keys,
- split-spacebar designs,
- thumb-operated modifiers,
- Mod-Tap techniques,
- programmable layers,
- compact keyboard layouts,
- and multilingual input environments.

From this perspective, Japanese input keys can be considered not only as language-specific legacy keys, but also as physical resources that may be reassigned or extended in modern programmable keyboards.

## Design Principles

IC-JIS is based on several principles:

1. **Evolution rather than replacement**  
   Build upon existing keyboard conventions rather than introducing an entirely unrelated layout.

2. **Connection rather than invention**  
   Connect useful ideas that already exist in JIS keyboards, programmable keyboards, and enthusiast keyboard design.

3. **Preserve familiar typing where possible**  
   New functionality should not unnecessarily disrupt established typing habits.

4. **Use programmability before changing hardware**  
   Many ideas can first be explored through firmware and key mapping.

5. **Allow multiple implementations**  
   IC-JIS is a design approach, not necessarily one fixed physical keyboard.

## Technical Proposal

The detailed rationale, historical background, layout analysis, and implementation approach are described in the IC-JIS Technical Proposal.

- docs/IC-JIS_Technical_Proposal_EN.pdf
- docs/IC-JIS_Technical_Proposal_JA.pdf

The English version is intended as the primary reference for international keyboard manufacturers, designers, and developers.

## Repository Structure

```text
IC-JIS-Keyboard/
├── README.md
├── docs/
├── images/
├── layouts/
└── examples/
