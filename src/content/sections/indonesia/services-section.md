---
enable: true
title: "Mitra & Perusahaan Kami"

button:
  # Refer to the `sharedButton` schema in `src/sections.schema.ts` for all available configuration options (e.g., enable, label, url, hoverEffect, variant, icon, tag, rel, class, target, etc.)
  enable: false
  label: "Lihat semua produk"
  url: "/services/"
  hoverEffect: "magnetic-text-flip" # Optional: text-flip | creative-fill | magnetic | magnetic-text-flip
  variant: "fill" # Optional: fill | fill-white | outline | text | circle
  # rel: "" # Optional
  # target: "" # Optional
  # class: "" # Optional
  icon: # Optional
    enable: true
    name: "ArrowUpRight"
    position: "right" # left | right

options:
  layout: "carousel" # grid | carousel; carousel uses each service image as an overlay card background
  limit: 6
  marquee: # Used when layout is "carousel"
    elementWidthAuto: false
    elementWidth: "22rem"
    elementWidthResponsive: "18rem"
    pauseOnHover: true
    reverse: "" # reverse / ""
    duration: "22s"
---
