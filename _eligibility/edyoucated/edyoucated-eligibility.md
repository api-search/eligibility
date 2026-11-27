---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Als Nutzer können sich ausschließlich unbeschränkt geschäftsfähige natürliche Personen registrieren.
    type: individual
  - text: Diese AGB gelten unabhängig davon, ob Sie als Verbraucher, Unternehmer oder Kaufmann agieren.
    type: business
  minimum_age:
    text: Als Nutzer können sich ausschließlich unbeschränkt geschäftsfähige natürliche Personen registrieren.
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Wir sind berechtigt, schriftliche Nachweise zur Überprüfung der angegebenen Daten anzufordern.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Edyoucated
provenance_date: '2026-11-09'
provider_name: Edyoucated
provider_slug: edyoucated
slug: edyoucated-eligibility
source_date: '2026-11-09'
source_filename: edyoucated-eligibility.yml
source_heading: Eligibility
source_page: https://edyoucated.org/rechtliches/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Edyoucated\naid: edyoucated\nurl: https://edyoucated.org/rechtliches/agb\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Als Nutzer können sich ausschließlich unbeschränkt geschäftsfähige natürliche Personen registrieren.\n- type: business\n  text: Diese AGB gelten unabhängig davon, ob Sie als Verbraucher, Unternehmer oder Kaufmann agieren.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Wir sind berechtigt, schriftliche Nachweise zur Überprüfung der angegebenen Daten anzufordern.\n\
  minimum_age:\n  value: null\n  text: Als Nutzer können sich ausschließlich unbeschränkt geschäftsfähige natürliche Personen registrieren.\n"
source_yaml_url: https://artifacts.apis.io/edyoucated/eligibility/edyoucated-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Edyoucated's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- Learning
- LMS
- Skills Management
- Corporate Training
- Talent Development
- Software-as-a-Service
- Artificial Intelligence
---
