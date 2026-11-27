---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"Customer" – a legal entity, natural person, or individual entrepreneur who has registered an Account or uses our Services.'
    type: individual
  - text: '"Customer" – a legal entity, natural person, or individual entrepreneur who has registered an Account or uses our Services.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Malware, botnets, crypto-mining from VMs
    text: use VMs for malware, spam/phishing, botnets, crypto‑mining, DDoS, command‑and‑control, unauthorized port scanning/pentesting, or to facilitate illegal content or activities
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
name: AppWizzy
provenance_date: '2026-11-09'
provider_name: AppWizzy
provider_slug: appwizzy-com
slug: appwizzy-com-eligibility
source_date: '2026-11-09'
source_filename: appwizzy-com-eligibility.yml
source_heading: Eligibility
source_page: https://appwizzy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AppWizzy\naid: appwizzy-com\nurl: https://appwizzy.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: '\"Customer\" – a legal entity, natural person, or individual entrepreneur who has registered an Account or\n    uses our Services.'\n- type: business\n  text: '\"Customer\" – a legal entity, natural person, or individual entrepreneur who has registered an Account or\n    uses our Services.'\nrestricted_uses:\n- summary: Malware, botnets, crypto-mining from VMs\n  text: use VMs for malware, spam/phishing, botnets, crypto‑mining,\
  \ DDoS, command‑and‑control, unauthorized port\n    scanning/pentesting, or to facilitate illegal content or activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/appwizzy-com/eligibility/appwizzy-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from AppWizzy's own page on 2026-11-09.
synthetic: false
tags:
- Platform
- Artificial Intelligence
- Software-as-a-Service
- Development
- Low-Code
---
