---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - SE
    text: ha ett svenskt personnummer, mobilnummer samt en mejladress
  entity_types:
  - text: 'För att kunna använda våra Tjänster måste du: vara över 18 år.'
    type: individual
  - text: Werlabs erbjuder Tjänster, såsom hälsokontroller och blodprover till privatpersoner och företag
    type: business
  minimum_age:
    text: vara över 18 år
    value: '18'
  restricted_uses:
  - summary: Protected personal data or secrecy marking
    text: För det fall du som användare har skyddade personuppgifter som innebär att ditt namn och din adress skyddas i folkbokföringsregistret, du har en sekretessmarkering eller fingerade personuppgifter kan du inte använda våra tjänster.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: ha BankID eller Freja eID+ för att kunna skapa ett konto.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Werlabs
provenance_date: '2026-11-10'
provider_name: Werlabs
provider_slug: werlabs
slug: werlabs-eligibility
source_date: '2026-11-10'
source_filename: werlabs-eligibility.yml
source_heading: Eligibility
source_page: https://werlabs.se/om-werlabs/kopvillkor/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Werlabs\naid: werlabs\nurl: https://werlabs.se/om-werlabs/kopvillkor/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - SE\n  excluded: []\n  text: ha ett svenskt personnummer, mobilnummer samt en mejladress\nentity_types:\n- type: individual\n  text: 'För att kunna använda våra Tjänster måste du: vara över 18 år.'\n- type: business\n  text: Werlabs erbjuder Tjänster, såsom hälsokontroller och blodprover till privatpersoner och företag\nrestricted_uses:\n- summary: Protected personal data or secrecy marking\n  text: För det fall du som användare har skyddade personuppgifter som innebär att ditt namn och\
  \ din adress skyddas\n    i folkbokföringsregistret, du har en sekretessmarkering eller fingerade personuppgifter kan du inte använda\n    våra tjänster.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: ha BankID eller Freja eID+ för att kunna skapa ett konto.\nminimum_age:\n  value: '18'\n  text: vara över 18 år\n"
source_yaml_url: https://artifacts.apis.io/werlabs/eligibility/werlabs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Werlabs's own page on 2026-11-10.
synthetic: false
tags:
- Health
- Preventive Care
- Lab Testing
- Sweden
- Digital Health
---
