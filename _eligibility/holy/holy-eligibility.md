---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - DE
    - AT
    - CH
    - FR
    - PL
    - BE
    text: Die Teilnahme steht Privatpersonen ab 16 Jahren mit Wohnsitz in Deutschland, Österreich, der Schweiz, Frankreich oder Polen offen.
  entity_types:
  - text: Verbraucher ist jede natürliche Person, die ein Rechtsgeschäft zu Zwecken abschließt
    type: individual
  - text: Unternehmern i. S. d. § 14 BGB, juristischen Personen des öffentlichen Rechts
    type: business
  minimum_age:
    text: Unsere Energy-Produkte (mit Koffein) werden nur an Personen ab 18 Jahren verkauft.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Wir behalten uns eine Altersprüfung vor (Ident-Check oder durch Versanddienstleister).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HOLY
provenance_date: '2026-11-09'
provider_name: HOLY
provider_slug: holy
slug: holy-eligibility
source_date: '2026-11-09'
source_filename: holy-eligibility.yml
source_heading: Eligibility
source_page: https://de.holy.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HOLY\naid: holy\nurl: https://de.holy.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - DE\n  - AT\n  - CH\n  - FR\n  - PL\n  - BE\n  excluded: []\n  text: Die Teilnahme steht Privatpersonen ab 16 Jahren mit Wohnsitz in Deutschland, Österreich, der Schweiz, Frankreich\n    oder Polen offen.\nentity_types:\n- type: individual\n  text: Verbraucher ist jede natürliche Person, die ein Rechtsgeschäft zu Zwecken abschließt\n- type: business\n  text: Unternehmern i. S. d. § 14 BGB, juristischen Personen des öffentlichen Rechts\nrestricted_uses: []\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: Wir behalten uns eine Altersprüfung vor (Ident-Check oder durch Versanddienstleister).\nminimum_age:\n  value: '18'\n  text: Unsere Energy-Produkte (mit Koffein) werden nur an Personen ab 18 Jahren verkauft.\n"
source_yaml_url: https://artifacts.apis.io/holy/eligibility/holy-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from HOLY's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Beverages
- Direct to Consumer
- E-Commerce
- Agentic Commerce
- Shopify
- Germany
---
