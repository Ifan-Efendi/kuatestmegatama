---
# Default content for `src/layouts/components/sections/CallToAction.astro`; page frontmatter can override these values.
enable: true # Control the visibility of this section across all pages where it is used
title: "Siap Memulai Proyek Anda?"
description: |
  Butuh alat uji teknik sipil berkualitas? Hubungi kami sekarang.

button:
  # Refer to the `sharedButton` schema in `src/sections.schema.ts` for all available configuration options (e.g., enable, label, url, hoverEffect, variant, icon, tag, rel, class, target, etc.)
  enable: true
  label: "Konsultasi Sekarang"
  url: "/#contact"
  hoverEffect: "magnetic-text-flip" # Optional: text-flip | creative-fill | magnetic | magnetic-text-flip
  variant: "fill" # Optional: fill | fill-white | outline | text | circle
  rel: "noopener noreferrer" # Optional
  target: "_blank" # Optional
  # class: "" # Optional

options:
  appearance: "dark" # Options: "dark" | "light" | "accent"
  centeredContent: true # true | false - dark appearance is centered to match the default CTA design
---
