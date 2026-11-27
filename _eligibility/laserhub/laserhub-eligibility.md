---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Die AGB gelten nur, wenn der Kunde Unternehmer (§ 14 BGB), eine juristische Person des öffentlichen Rechts oder ein öffentlich-rechtliches Sondervermögen ist.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Bestellungen bei Laserhub können erst nach Log-in, Registrierung und Bestätigung der AGB von Laserhub abgegeben werden.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Laserhub
provenance_date: '2026-11-09'
provider_name: Laserhub
provider_slug: laserhub
slug: laserhub-eligibility
source_date: '2026-11-09'
source_filename: laserhub-eligibility.yml
source_heading: Eligibility
source_page: https://laserhub.com/agb/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Laserhub\naid: laserhub\nurl: https://laserhub.com/agb/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Die AGB gelten nur, wenn der Kunde Unternehmer (§ 14 BGB), eine juristische Person des öffentlichen Rechts\n    oder ein öffentlich-rechtliches Sondervermögen ist.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Bestellungen bei Laserhub können erst nach Log-in, Registrierung und Bestätigung der AGB von Laserhub abgegeben\n    werden.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/laserhub/eligibility/laserhub-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Laserhub's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Manufacturing
- Metal Fabrication
- Procurement
- Laser Cutting
- CNC Machining
- Sheet Metal
- Supply Chain
- Marketplace
- Industrial
- Germany
---
