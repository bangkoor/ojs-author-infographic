# DESIGN.md: OJS Author Infographic

Direction supplied by the owner (transcribed as given):

- **Identitas:** Tool ini dikembangkan oleh Media Konservasi dan JPSL.
- **Kepribadian:** akademik, hangat, praktis, terpercaya.
- **Palet:** hijau, biru, oranye.
- **Tipografi:** hindari tipe serif.
- **Nuansa:** sederhana dan informatif, modern.

Dial: ENERGY 1 / RHYTHM 2 / MOTION 1

Design Read: utility web tool for OJS journal managers, in a calm academic workbench style, dial ENERGY 1 / RHYTHM 2 / MOTION 1.

## Decisions and their reasons

| Decision | Reason |
|---|---|
| Plus Jakarta Sans for all UI text | Sans serif as asked; drawn by an Indonesian foundry (Tokotype) for Jakarta, which fits two Indonesian journals, and its open shapes read warm without looking playful. |
| IBM Plex Mono, 12px, only inside the code box | The code is real code that people copy; mono keeps tags and properties aligned. Never used for headings or labels. |
| Green `#1d6b55` as the main colour | Conservation and environment journals; it marks progress (step markers, selected options, success). |
| Blue `#1f5f99` for information | Privacy note, "where to paste" help, links and the keyboard focus ring: things that explain, never things that act. |
| Orange `#b45309` as the single accent | Marks what needs the user: the Copy button, the "Example data" label and author rows to check. Nowhere else. |
| Red `#b42318` only for errors | Error text always comes with an icon and a sentence, never colour alone. |
| Two panes on wide screens (settings left, result right) | The work is "change a setting, see the result"; side by side removes scrolling between cause and effect. |
| Pin-shaped step markers (filled circle with a soft ring) | Identity motif: echoes the country markers on the generated map, so the tool and its output look related. |
| Cards with 1px borders, no shadows | Each step is a separate task; borders group without making the page float. The only shadow is on the preview page, because it stands for a web page. |
| Radius 14px cards, 8px inputs and buttons, round chips | Large containers, small controls; chips are round because they toggle filters. |
| Light theme by default, working dark theme and toggle | No product reason for a fixed theme; follows the system setting and lets the user switch. |
| Motion: hover and focus states, copy confirmation fade | MOTION 1. The generated infographic has its own entrance animations; the tool itself stays still. |
