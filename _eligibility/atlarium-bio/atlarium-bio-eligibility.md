---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful, deceptive or harmful use
    text: Use Atlarium lawfully and in a way that respects other people, animals, and the service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Some features require an Atlarium account. Provide accurate information, keep your credentials private, and tell us promptly if you suspect unauthorized access.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Atlarium
provenance_date: '2026-11-09'
provider_name: Atlarium
provider_slug: atlarium-bio
slug: atlarium-bio-eligibility
source_date: '2026-11-09'
source_filename: atlarium-bio-eligibility.yml
source_heading: Eligibility
source_page: https://atlarium.bio/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atlarium\naid: atlarium-bio\nurl: https://atlarium.bio/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful, deceptive or harmful use\n  text: Use Atlarium lawfully and in a way that respects other people, animals, and the service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Some features require an Atlarium account. Provide accurate information, keep your credentials private,\n    and tell us promptly if you suspect unauthorized access.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/atlarium-bio/eligibility/atlarium-bio-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Atlarium's own page on 2026-11-09.
synthetic: false
tags:
- Aquariums
- Terrariums
- Species
- Guides
- Community
---
