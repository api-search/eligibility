---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you must be at least 18 years of age, or of the legal age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Uses prohibited by law
    text: You are not allowed to use this website and/or receive services if doing so is prohibited in your country or under any law or regulation applicable to you.
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
name: NeuroTherapia
provenance_date: '2026-11-10'
provider_name: NeuroTherapia
provider_slug: neurotherapia
slug: neurotherapia-eligibility
source_date: '2026-11-10'
source_filename: neurotherapia-eligibility.yml
source_heading: Eligibility
source_page: https://www.neurotherapia.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NeuroTherapia\naid: neurotherapia\nurl: https://www.neurotherapia.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Uses prohibited by law\n  text: You are not allowed to use this website and/or receive services if doing so is prohibited in your country\n    or under any law or regulation applicable to you.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years of age, or of the legal age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/neurotherapia/eligibility/neurotherapia-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from NeuroTherapia's own page on 2026-11-10.
synthetic: false
tags:
- Biotechnology
- Pharmaceuticals
- Life Sciences
- Health
- Clinical Trials
- Neuroscience
- Drug Discovery
- Alzheimers Disease
- Company
---
