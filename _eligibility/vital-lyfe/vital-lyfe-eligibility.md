---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Personal use only for purchases
    text: You represent and warrant that your purchases are for your own personal or household use and not for commercial resale or export.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Vital Lyfe reserves the right to accept or decline your order for any reason at its discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Vital Lyfe
provenance_date: '2026-11-10'
provider_name: Vital Lyfe
provider_slug: vital-lyfe
slug: vital-lyfe-eligibility
source_date: '2026-11-10'
source_filename: vital-lyfe-eligibility.yml
source_heading: Eligibility
source_page: https://www.vital-lyfe.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vital Lyfe\naid: vital-lyfe\nurl: https://www.vital-lyfe.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\nrestricted_uses:\n- summary: Personal use only for purchases\n  text: You represent and warrant that your purchases are for your own personal or household use and not for commercial\n    resale or export.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n\
  \  text: Vital Lyfe reserves the right to accept or decline your order for any reason at its discretion.\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/vital-lyfe/eligibility/vital-lyfe-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Vital Lyfe's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Water Purification
- Hardware
- Consumer Products
- Clean Water
- Sustainability
- E-Commerce
---
