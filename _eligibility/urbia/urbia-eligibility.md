---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Der Service richtet sich ausschließlich an private Personen bzw. Personenvereinigungen.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use
    text: Jede gewerbliche Nutzung auf bzw. innerhalb der Plattform sowie von Inhalten außerhalb der Plattform ist untersagt.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Für die Nutzung des Forums von www.URBIA.de ist eine Registrierung erforderlich.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Urbia
provenance_date: '2026-11-10'
provider_name: Urbia
provider_slug: urbia
slug: urbia-eligibility
source_date: '2026-11-10'
source_filename: urbia-eligibility.yml
source_heading: Eligibility
source_page: https://www.eltern.de/services/urbia-community-nutzungsbedingungen-13857662.html?has_header=0
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Urbia\naid: urbia\nurl: https://www.eltern.de/services/urbia-community-nutzungsbedingungen-13857662.html?has_header=0\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Der Service richtet sich ausschließlich an private Personen bzw. Personenvereinigungen.\nrestricted_uses:\n- summary: Commercial use\n  text: Jede gewerbliche Nutzung auf bzw. innerhalb der Plattform sowie von Inhalten außerhalb der Plattform ist\n    untersagt.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Für die Nutzung des Forums von\
  \ www.URBIA.de ist eine Registrierung erforderlich.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/urbia/eligibility/urbia-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Urbia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Parenting
- Family
- Community
- Forums
- Pregnancy
- Media
- Germany
---
