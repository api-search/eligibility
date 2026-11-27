---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may only register as a driver if you are 18 years or older.
    type: individual
  minimum_age:
    text: You may only register as a driver if you are 18 years or older.
    value: '18'
  restricted_uses:
  - summary: Relocation requests without intent to complete
    text: Requesting vehicles from Transfercar's website without having any intention of completing the relocation is considered a serious breach of Transfercar's terms and conditions.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: As part of registering with Transfercar, you must provide true, accurate and current information to Transfercar including full name, date of birth and contact details. Transfercar may call or email to verify these details.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Transfercar
provenance_date: '2026-11-10'
provider_name: Transfercar
provider_slug: transfercar
slug: transfercar-eligibility
source_date: '2026-11-10'
source_filename: transfercar-eligibility.yml
source_heading: Eligibility
source_page: https://www.transfercar.co.nz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Transfercar\naid: transfercar\nurl: https://www.transfercar.co.nz/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may only register as a driver if you are 18 years or older.\nrestricted_uses:\n- summary: Relocation requests without intent to complete\n  text: Requesting vehicles from Transfercar's website without having any intention of completing the relocation\n    is considered a serious breach of Transfercar's terms and conditions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: As part of\
  \ registering with Transfercar, you must provide true, accurate and current information to Transfercar\n    including full name, date of birth and contact details. Transfercar may call or email to verify these details.\nminimum_age:\n  value: '18'\n  text: You may only register as a driver if you are 18 years or older.\n"
source_yaml_url: https://artifacts.apis.io/transfercar/eligibility/transfercar-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Transfercar's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Travel
- Car Rental
- Vehicle Relocation
- Motorhome
- Campervan
- Marketplace
- Mobility
- New Zealand
- Australia
---
