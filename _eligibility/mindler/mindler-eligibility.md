---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Mindler registrerar endast patientavgifter om Användaren är folkbokförd i en region som är ansluten till e-frikortstjänsten.
  entity_types:
  - text: Mindler har särskilda erbjudanden för företag som vill erbjuda Tjänsterna till sina anställda.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Emergencies excluded
    text: I en akut situation, som vid självmordstankar, ska Användaren inte heller vända sig till Mindler
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: För att kunna skapa ett Användarkonto måste Användaren vara minst 18 år gammal och ha tillgång till BankID för identifiering.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mindler
provenance_date: '2026-11-10'
provider_name: Mindler
provider_slug: mindler
slug: mindler-eligibility
source_date: '2026-11-10'
source_filename: mindler-eligibility.yml
source_heading: Eligibility
source_page: https://mindler.se/allmanna-villkor/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mindler\naid: mindler\nurl: https://mindler.se/allmanna-villkor/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Mindler registrerar endast patientavgifter om Användaren är folkbokförd i en region som är ansluten till\n    e-frikortstjänsten.\nentity_types:\n- type: business\n  text: Mindler har särskilda erbjudanden för företag som vill erbjuda Tjänsterna till sina anställda.\nrestricted_uses:\n- summary: Emergencies excluded\n  text: I en akut situation, som vid självmordstankar, ska Användaren inte heller vända sig till Mindler\nverification:\n  kyc: true\n  kyb: null\n  approval_required:\
  \ null\n  text: För att kunna skapa ett Användarkonto måste Användaren vara minst 18 år gammal och ha tillgång till BankID\n    för identifiering.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mindler/eligibility/mindler-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Mindler's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mental Health
- Telehealth
- Counseling
- Sweden
---
