---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is intended solely for businesses and the institutional, governmental, and professional participants Company approves for access; it is not directed to consumers.
    type: business
  - text: If you access the Site on behalf of a governmental body or in connection with a government procurement, you are responsible for compliance with all applicable procurement, ethics, and public-contracting rules.
    type: government
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons or jurisdictions
    text: you, and any entity on whose behalf you act, are not (a) located in, organized under the laws of, or ordinarily resident in any country or territory subject to comprehensive U.S. or other applicable sanctions
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The Site is intended solely for businesses and the institutional, governmental, and professional participants Company approves for access
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nebex
provenance_date: '2026-11-10'
provider_name: Nebex
provider_slug: nebex
slug: nebex-eligibility
source_date: '2026-11-10'
source_filename: nebex-eligibility.yml
source_heading: Eligibility
source_page: https://www.nebex.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nebex\naid: nebex\nurl: https://www.nebex.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Site is intended solely for businesses and the institutional, governmental, and professional participants\n    Company approves for access; it is not directed to consumers.\n- type: government\n  text: If you access the Site on behalf of a governmental body or in connection with a government procurement,\n    you are responsible for compliance with all applicable procurement, ethics, and public-contracting rules.\nrestricted_uses:\n\
  - summary: Sanctioned persons or jurisdictions\n  text: you, and any entity on whose behalf you act, are not (a) located in, organized under the laws of, or ordinarily\n    resident in any country or territory subject to comprehensive U.S. or other applicable sanctions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The Site is intended solely for businesses and the institutional, governmental, and professional participants\n    Company approves for access\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/nebex/eligibility/nebex-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Nebex's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Frontier Tech
- Space Economy
- Space Commerce
- Marketplace
- Exchange
- Settlement
- GV Portfolio
---
