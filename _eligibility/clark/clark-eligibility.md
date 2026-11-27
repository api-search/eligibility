---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - DE
    text: Allgemeine Geschäftsbedingungen für den deutschen Markt
  entity_types:
  - text: volljährige natürliche Personen
    type: individual
  - text: Personen-Gesellschaften, juristische Personen
    type: business
  minimum_age:
    text: volljährige natürliche Personen
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Wir können Lebens­versicherungen und Dienstleistungen mit Anlagezweck nur dann vermitteln, wenn du dich identifizierst.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clark
provenance_date: '2026-11-09'
provider_name: Clark
provider_slug: clark
slug: clark-eligibility
source_date: '2026-11-09'
source_filename: clark-eligibility.yml
source_heading: Eligibility
source_page: https://www.clark.de/agb/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clark\naid: clark\nurl: https://www.clark.de/agb/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - DE\n  excluded: []\n  text: Allgemeine Geschäftsbedingungen für den deutschen Markt\nentity_types:\n- type: individual\n  text: volljährige natürliche Personen\n- type: business\n  text: Personen-Gesellschaften, juristische Personen\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Wir können Lebens­versicherungen und Dienstleistungen mit Anlagezweck nur dann vermitteln, wenn du dich\n    identifizierst.\nminimum_age:\n  value: null\n  text: volljährige natürliche\
  \ Personen\n"
source_yaml_url: https://artifacts.apis.io/clark/eligibility/clark-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from Clark's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Insurance Comparison
- Personal Finance
- Financial Services
- Consumer
- Germany
- Mobile App
---
