---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Die Leistungen richten sich ausschließlich an Unternehmer (§ 14 BGB)
    type: business
  - text: juristische Personen des öffentlichen Rechts und öffentlich-rechtliche Sondervermögen
    type: government
  minimum_age:
    text: null
    value: null
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
name: Fincompare
provenance_date: '2026-11-09'
provider_name: Fincompare
provider_slug: fincompare
slug: fincompare-eligibility
source_date: '2026-11-09'
source_filename: fincompare-eligibility.yml
source_heading: Eligibility
source_page: https://fincompare.de/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fincompare\naid: fincompare\nurl: https://fincompare.de/agb\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Die Leistungen richten sich ausschließlich an Unternehmer (§ 14 BGB)\n- type: government\n  text: juristische Personen des öffentlichen Rechts und öffentlich-rechtliche Sondervermögen\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fincompare/eligibility/fincompare-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Fincompare's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financing
- SME Lending
- Fintech
- Loans
- Comparison Marketplace
- Banking
- Factoring
- Leasing
- Germany
---
