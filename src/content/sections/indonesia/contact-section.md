---
enable: true # Control the visibility of this section across all pages where it is used
title: "Butuh Bantuan?"
description: "Konsultasi gratis seputar kebutuhan alat uji laboratorium teknik sipil."
officeHours: "Senin - Sabtu: 08:00 - 17:00 WIB" # Optional; remove or set empty to hide this row.

# Check config.toml file for form action related settings
# this is also used in the footer of the personal portfolio homepage
formTitle: "Formulir Kebutuhan"
formDescription: "Lengkapi data di bawah, lalu klik kirim untuk langsung mendapatkan penawaran dari tim kami."

form:
  emailSubject: "Pesan baru dari website" # Customized email subject (applicable when anyone submit form, form submission may receive by email depend on provider)
  submitButton:
    # Refer to the `sharedButton` schema in `src/sections.schema.ts` for all available configuration options (e.g., enable, label, url, hoverEffect, variant, icon, tag, rel, class, target, etc.)
    enable: true
    label: "Kirim Pesan"
    class: "w-full justify-center rounded-md"
    hoverEffect: "magnetic-text-flip" # Optional: text-flip | creative-fill | magnetic | magnetic-text-flip
    # variant: "" # Optional: fill | outline | text | circle
    # rel: "" # Optional
    # target: "" # Optional

  # This note will show at the end of form
  # note: |
  #   Your data is safe with us. We respect your privacy and never share your information. <br /> Read our [Privacy Policy](/privacy-policy/).
  inputs:
    - label: "Nama Anda"
      name: "Nama"
      placeholder: "Nama Anda"
      required: true
      halfWidth: true
    - label: "Nama Perusahaan"
      name: "Perusahaan"
      placeholder: "Nama Perusahaan"
      halfWidth: true
    - label: "Alamat"
      name: "Alamat"
      placeholder: "Alamat lengkap"
      tag: "textarea"
      rows: "2"
      required: true
    - label: "Nama Alat"
      name: "Alat"
      placeholder: "Nama alat yang dibutuhkan"
      required: true
      halfWidth: true
    - label: "Jumlah"
      name: "Jumlah"
      placeholder: "Jumlah unit"
      type: "text"
      inputmode: "numeric"
      pattern: "[0-9]*"
      halfWidth: true
    - label: "Catatan"
      name: "Catatan"
      placeholder: "Catatan tambahan untuk kami..."
      tag: "textarea"
      rows: "3"
    - note: success
      parentClass: "hidden text-sm message success"
      content: "Mengarahkan ke WhatsApp..."
    - note: deprecated
      parentClass: "hidden text-sm message error"
      content: "Mohon lengkapi semua field yang diperlukan."
---
