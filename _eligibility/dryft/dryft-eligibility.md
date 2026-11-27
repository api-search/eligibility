---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Das Angebot von Dryft richtet sich ausschließlich an Unternehmer (§ 14 BGB). Verbraucher (§ 13 BGB) sind von der Nutzung ausgeschlossen.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Mit Vertragsschluss versichert der Kunde, Unternehmer zu sein und die erforderliche Vertretungsmacht zu besitzen.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dryft
provenance_date: '2026-11-09'
provider_name: Dryft
provider_slug: dryft
slug: dryft-eligibility
source_date: '2026-11-09'
source_filename: dryft-eligibility.yml
source_heading: Eligibility
source_page: https://dryft.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dryft\naid: dryft\nurl: https://dryft.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Das Angebot von Dryft richtet sich ausschließlich an Unternehmer (§ 14 BGB). Verbraucher (§ 13 BGB) sind\n    von der Nutzung ausgeschlossen.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Mit Vertragsschluss versichert der Kunde, Unternehmer zu sein und die erforderliche Vertretungsmacht zu\n    besitzen.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dryft/eligibility/dryft-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Dryft's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Manufacturing
- Supply Chain
- Procurement
- Automation
- ERP
- AI Agents
---
