# Cadastre

**Greek cadastre tools for AutoCAD, Civil 3D, ZWCAD and GstarCAD**

Cadastre adds a ribbon tab that brings Greek open data straight into your drawing: cadastral parcels with their ΚΑΕΚ,
forest maps, a satellite background, ΕΓΣΑ87 ↔ WGS84 coordinates and coordinate grids.

## ⬇ [Download Cadastre-Setup.exe](https://github.com/iliasmachairas/Cadastre-CAD-Plugin/releases/latest/download/Cadastre-Setup.exe)

Free · English manual included · no administrator rights needed · [all versions](https://github.com/iliasmachairas/Cadastre-CAD-Plugin/releases)

---

## What it does

| Button | Command | |
|---|---|---|
| Φόρτωση όμορων | `KDOMORA` | Loads the parcels under your property and their neighbours (όμορα) with ΚΑΕΚ from data.gov.gr, or from an official κτηματογραφικό απόσπασμα |
| Δασικός χάρτης | `KDDASIKA` | Forest map (ratified, posted or 1945) around the property, with the area of the property in each category (ΔΔ, ΑΔ, ΔΑ, ΑΑ …) |
| Δορυφόρος ON / OFF | `KDMAPON` / `KDMAPOFF` | Satellite image behind the drawing that follows the view. No account needed |
| ΕΓΣΑ87 ↔ WGS84 | `KDGRT` | Coordinates of a point in both systems, or a point placed from φ,λ |
| Κλίμακα | `KDSCALE` | Drawing scale for text height and linetypes |
| Κάνναβος | `KDGRID` | Coordinate grid crosses at the drawing scale |
| Οδηγίες | `KDHELP` | Opens the manual |

## Supported programs

- AutoCAD / Civil 3D **2021 – 2026**
- ZWCAD **2026** (Professional)
- GstarCAD **2027** (Professional)

LT editions cannot load plugins. Drawings must be in **ΕΓΣΑ87** (EPSG:2100), in metres.

## Install

1. Close AutoCAD / Civil 3D / ZWCAD / GstarCAD.
2. Run **Cadastre-Setup.exe**. It finds the programs on your computer and sets Cadastre up for each of them.
   - If Windows shows *"Windows protected your PC"*, click **More info → Run anyway**. The setup is not yet digitally
     signed, so Windows does not recognise it.
3. Start your CAD program and open the **Cadastre** tab.

To remove it: Windows **Settings → Apps → Cadastre → Uninstall**.

## Manual

[Cadastre-Manual.pdf](docs/Cadastre-Manual.pdf). It is also installed with the plugin and opened by the **Οδηγίες** button.

## Good to know

- Parcels and forest maps come from the **open data of data.gov.gr**. They are **not an official extract** and can
  differ by a few centimetres. Some areas are not yet published. For submissions use the official κτηματογραφικό απόσπασμα.
- The satellite image is for orientation only. Imagery © Esri, Vantor, Earthstar Geographics and the GIS User Community.
- Internet is needed the first time a region is used. The files are then kept on your computer.

## Feedback

Found a problem or have an idea? Open an [issue](https://github.com/iliasmachairas/Cadastre-CAD-Plugin/issues).

---

Free to use under the [terms of use](TERMS.md). Provided without warranty.
