---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: In the case of an individual, the individual must be at least 18 years of age or have valid authorization from his/her legal representative or custodian.
    type: individual
  - text: In the case of a legal entity, the entity must be duly incorporated and in good standing.
    type: business
  minimum_age:
    text: the individual must be at least 18 years of age or have valid authorization from his/her legal representative or custodian.
    value: '18'
  restricted_uses:
  - summary: No competitor access or benchmarking
    text: (ii) if you are a competitor of Almost Apps LLC, (iii) to monitor the availability, performance or functionality of the Almost Apps LLC Services or (iv) for other benchmarking or competitive purposes.
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
name: AlmostApps
provenance_date: '2026-11-09'
provider_name: AlmostApps
provider_slug: almostapps
slug: almostapps-eligibility
source_date: '2026-11-09'
source_filename: almostapps-eligibility.yml
source_heading: Eligibility
source_page: https://almostapps.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AlmostApps\naid: almostapps\nurl: https://almostapps.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: In the case of an individual, the individual must be at least 18 years of age or have valid authorization\n    from his/her legal representative or custodian.\n- type: business\n  text: In the case of a legal entity, the entity must be duly incorporated and in good standing.\nrestricted_uses:\n- summary: No competitor access or benchmarking\n  text: (ii) if you are a competitor of Almost Apps LLC, (iii) to monitor\
  \ the availability, performance or functionality\n    of the Almost Apps LLC Services or (iv) for other benchmarking or competitive purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the individual must be at least 18 years of age or have valid authorization from his/her legal representative\n    or custodian.\n"
source_yaml_url: https://artifacts.apis.io/almostapps/eligibility/almostapps-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AlmostApps's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gaming
- Sports
- Mobile
- Entertainment
- Consumer App
---
