---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - ID
    text: 'KATEGORI INDIVIDU: Berusia 17 tahun atau lebih; Memiliki wewenang untuk mengambil tindakan hukum menandatangani perjanjian mengikat dengan Bank dan tidak dilarang untuk melakukannya berdasarkan hukum yang berlaku; dan Warga Negara Indonesia.'
  entity_types:
  - text: 'KATEGORI BADAN (BADAN HUKUM: PT, KOPERASI, YAYASAN) Antara lain: Memiliki Akta Pendirian. Memiliki Anggaran Dasar yang telah dilaporkan, disetujui dan disahkan oleh Menkumham.'
    type: business
  minimum_age:
    text: Berusia 17 tahun atau lebih
    value: '17'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: tidak diperuntukan untuk kegiatan lain diluar dari tujuan pembukaan Rekening, kegiatan pelanggaran hukum atau kegiatan ilegal lainnya.
  - summary: Sanctioned parties and countries
    text: 'Nasabah selanjutnya menyatakan dan menyetujui bahwa: Nasabah tidak terkait dan tidak mempunyai transaksi baik secara langsung ataupun tidak langsung, dengan pihak atau negara mana pun yang sedang dikenakan sanksi'
  verification:
    approval_required: true
    kyb: true
    kyc: true
    text: Setelah proses pendaftaran diselesaikan, Nasabah perlu melakukan aktivasi Jago melalui Video Call atau Kantor Cabang. Seluruh transaksi lainnya, termasuk penarikan dan/atau transfer keluar dari Kantong Jago hanya dapat dilakukan setelah Bank menyelesaikan proses verifikasi sesuai dengan ketentuan Bank
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bank Jago
provenance_date: '2026-11-09'
provider_name: Bank Jago
provider_slug: bank-jago
slug: bank-jago-eligibility
source_date: '2026-11-09'
source_filename: bank-jago-eligibility.yml
source_heading: Eligibility
source_page: https://www.jago.com/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bank Jago\naid: bank-jago\nurl: https://www.jago.com/en/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - ID\n  excluded: []\n  text: 'KATEGORI INDIVIDU: Berusia 17 tahun atau lebih; Memiliki wewenang untuk mengambil tindakan hukum menandatangani\n    perjanjian mengikat dengan Bank dan tidak dilarang untuk melakukannya berdasarkan hukum yang berlaku; dan Warga\n    Negara Indonesia.'\nentity_types:\n- type: business\n  text: 'KATEGORI BADAN (BADAN HUKUM: PT, KOPERASI, YAYASAN) Antara lain: Memiliki Akta Pendirian. Memiliki Anggaran\n    Dasar yang telah dilaporkan,\
  \ disetujui dan disahkan oleh Menkumham.'\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: tidak diperuntukan untuk kegiatan lain diluar dari tujuan pembukaan Rekening, kegiatan pelanggaran hukum\n    atau kegiatan ilegal lainnya.\n- summary: Sanctioned parties and countries\n  text: 'Nasabah selanjutnya menyatakan dan menyetujui bahwa: Nasabah tidak terkait dan tidak mempunyai transaksi\n    baik secara langsung ataupun tidak langsung, dengan pihak atau negara mana pun yang sedang dikenakan sanksi'\nverification:\n  kyc: true\n  kyb: true\n  approval_required: true\n  text: Setelah proses pendaftaran diselesaikan, Nasabah perlu melakukan aktivasi Jago melalui Video Call atau Kantor\n    Cabang. Seluruh transaksi lainnya, termasuk penarikan dan/atau transfer keluar dari Kantong Jago hanya dapat\n    dilakukan setelah Bank menyelesaikan proses verifikasi sesuai dengan ketentuan Bank\nminimum_age:\n  value: '17'\n  text: Berusia 17 tahun atau lebih\n"
source_yaml_url: https://artifacts.apis.io/bank-jago/eligibility/bank-jago-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Bank Jago's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Banking
- Digital Bank
- Indonesia
- Open Banking
- Payments
- SNAP
---
