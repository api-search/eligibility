---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Auftraggeberin können sowohl „Verbraucher“ im Sinne von § 13 BGB als auch „Unternehmer“ i.S.v. § 14 BGB sein.
    type: individual
  - text: Das Angebot von heykantine! richtet sich ausschließlich an Unternehmer i.S.v. § 14 BGB
    type: business
  minimum_age:
    text: Anmelden können sich nur volljährige natürliche Personen, die die Voraussetzung des § 2 erfüllen.
    value: adult
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
name: Hey
provenance_date: '2026-11-09'
provider_name: Hey
provider_slug: hey
slug: hey-eligibility
source_date: '2026-11-09'
source_filename: hey-eligibility.yml
source_heading: Eligibility
source_page: https://www.heycater.com/de/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hey\naid: hey\nurl: https://www.heycater.com/de/agb\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Auftraggeberin können sowohl „Verbraucher“ im Sinne von § 13 BGB als auch „Unternehmer“ i.S.v. § 14 BGB\n    sein.\n- type: business\n  text: Das Angebot von heykantine! richtet sich ausschließlich an Unternehmer i.S.v. § 14 BGB\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: adult\n  text: Anmelden können sich nur volljährige natürliche\
  \ Personen, die die Voraussetzung des § 2 erfüllen.\n"
source_yaml_url: https://artifacts.apis.io/hey/eligibility/hey-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Hey's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Catering
- Marketplace
- Food
- Event
- Corporate Catering
- B2B
- Germany
---
