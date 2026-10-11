# IC-JIS

**A Technical Proposal for the Evolution of the Japanese Keyboard Layout**

IC-JIS explores how the Japanese JIS keyboard layout can be reinterpreted for modern programmable keyboards.

Rather than inventing an entirely new keyboard standard, IC-JIS connects design elements already present in the Japanese keyboard architecture with contemporary practices such as split spacebars, Mod-Tap, VIA/QMK, and compact keyboard layouts.

The focus is especially on the keys surrounding the spacebar, an area where the history of Japanese input and modern programmable keyboard design unexpectedly converge.

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

The English version is intended as the primary reference for international keyboard manufacturers, designers, and developers.

## Repository Structure

```text
IC-JIS-Keyboard/
├── README.md
├── docs/
├── images/
├── layouts/
└── examples/
```

### `docs/`

Technical proposals and supporting documents.

See docs/.

### `images/`

Figures, keyboard diagrams, historical references, and visual materials used to explain the concept.

See images/.

### `layouts/`

Reference layouts and future IC-JIS layout variations.

See layouts/.

### `examples/`

Experimental implementations demonstrating how IC-JIS concepts can be tested with existing programmable keyboard technologies.

See examples/.

## Step 0: Try the Concept

IC-JIS does not require a manufacturer to design new hardware before evaluating the idea.

A useful first step is simply to reproduce selected IC-JIS concepts on an existing programmable keyboard.

For example:

- assign thumb-accessible keys around the spacebar,
- experiment with Japanese input switching,
- combine these positions with Mod-Tap,
- evaluate the concept with layers,
- and test equivalent arrangements on compact keyboards.

This repository is intended to gradually provide practical examples for such experiments.

See examples/ for implementations as they become available.

## Project Status

IC-JIS is currently a technical proposal and experimental design project.

The project is intended to encourage discussion, prototyping, and evaluation rather than to present a finalized keyboard standard.

Feedback from keyboard manufacturers, firmware developers, keyboard designers, and users is welcome.

## About the Name

**IC-JIS** is the name of the project.

The GitHub repository is named **IC-JIS-Keyboard** so that its subject can be recognized more easily when encountered through search results or external links.

## Author

T. KAZAMA
Japan

## License

Unless otherwise noted, the original documentation and diagrams in this repository, including this README and the IC-JIS Technical Proposal, are licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

Third-party images, product photographs, trademarks, and other third-party materials are excluded from this license and remain subject to the rights of their respective owners.

Licensing terms for hardware design files and software are specified separately where applicable. Until such terms are explicitly stated, no additional license is granted for those materials.
