---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site may include a special set of pages intended to be accessed only by physicians (“Physician Portal”)
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Physician Portal limited to physicians
    text: The Site may include a special set of pages intended to be accessed only by physicians (“Physician Portal”) that allows physicians to learn more about our products, including information on training.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: As a condition to your access to the Physician Portal, we may require that you meet certain criteria and agree to comply with additional terms and conditions.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cerene
provenance_date: '2026-11-09'
provider_name: Cerene
provider_slug: channel-medsystems
slug: channel-medsystems-eligibility
source_date: '2026-11-09'
source_filename: channel-medsystems-eligibility.yml
source_heading: Eligibility
source_page: https://www.cerene.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cerene\naid: channel-medsystems\nurl: https://www.cerene.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site may include a special set of pages intended to be accessed only by physicians (“Physician Portal”)\nrestricted_uses:\n- summary: Physician Portal limited to physicians\n  text: The Site may include a special set of pages intended to be accessed only by physicians (“Physician Portal”)\n    that allows physicians to learn more about our products, including information on training.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: As a condition to your access to the Physician Portal, we may require that you meet certain criteria and\n    agree to comply with additional terms and conditions.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/channel-medsystems/eligibility/channel-medsystems-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Cerene's own page on 2026-11-09.
synthetic: false
tags:
- Health Tech
- Cryotherapy
- Women's Health
- Medical Devices
- FDA Cleared
---
