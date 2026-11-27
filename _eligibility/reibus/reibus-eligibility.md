---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally capable of entering into binding contracts to use our Site and Services.
    type: individual
  - text: This Site is intended for use by our actual and potential customers, vendors, and employees.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally capable of entering into binding contracts to use our Site and Services.
    value: '18'
  restricted_uses:
  - summary: Fraudulent or unlawful activity
    text: Refrain from engaging in fraudulent, unlawful, or abusive activity
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Reibus
provenance_date: '2026-11-10'
provider_name: Reibus
provider_slug: reibus
slug: reibus-eligibility
source_date: '2026-11-10'
source_filename: reibus-eligibility.yml
source_heading: Eligibility
source_page: https://www.reibus.com/terms-conditions.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reibus\naid: reibus\nurl: https://www.reibus.com/terms-conditions.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally capable of entering into binding contracts to use our Site\n    and Services.\n- type: business\n  text: This Site is intended for use by our actual and potential customers, vendors, and employees.\nrestricted_uses:\n- summary: Fraudulent or unlawful activity\n  text: Refrain from engaging in fraudulent, unlawful, or abusive activity\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally capable of entering into binding contracts to use our Site\n    and Services.\n"
source_yaml_url: https://artifacts.apis.io/reibus/eligibility/reibus-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Reibus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Freight
- Metals
- Steel
- Supply Chain
- Transportation
- Marketplace
---
