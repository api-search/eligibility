---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: This website is intended only for United States (“US”) and Canadian residents 18 years of age and older.
  entity_types:
  - text: intended only for United States (“US”) and Canadian residents 18 years of age and older
    type: individual
  minimum_age:
    text: Canadian residents 18 years of age and older
    value: '18'
  restricted_uses:
  - summary: Not for medical diagnosis or treatment
    text: Nothing contained on this site is intended to be used for the purpose of medical diagnosis or treatment.
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
name: SPR Therapeutics
provenance_date: '2026-11-10'
provider_name: SPR Therapeutics
provider_slug: spr-therapeutics
slug: spr-therapeutics-eligibility
source_date: '2026-11-10'
source_filename: spr-therapeutics-eligibility.yml
source_heading: Eligibility
source_page: https://www.sprpainrelief.com/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SPR Therapeutics\naid: spr-therapeutics\nurl: https://www.sprpainrelief.com/terms-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: This website is intended only for United States (“US”) and Canadian residents 18 years of age and older.\nentity_types:\n- type: individual\n  text: intended only for United States (“US”) and Canadian residents 18 years of age and older\nrestricted_uses:\n- summary: Not for medical diagnosis or treatment\n  text: Nothing contained on this site is intended to be used for the purpose of medical diagnosis or treatment.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Canadian residents 18 years of age and older\n"
source_yaml_url: https://artifacts.apis.io/spr-therapeutics/eligibility/spr-therapeutics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from SPR Therapeutics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Medical Devices
- Healthcare
- Neuromodulation
- Pain Management
- Neurotechnology
- Medical Technology
---
