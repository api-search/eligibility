---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the service on behalf of an organization, you confirm that you are allowed to accept these terms for it.
    type: business
  minimum_age:
    text: You must be old enough to enter a binding contract where you live.
    value: null
  restricted_uses:
  - summary: Infringing, unlawful or deceptive use
    text: use the service to infringe copyright or privacy rights, or for unlawful, harassing or deceptive purposes
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
name: tubetranscript-io
provenance_date: '2026-11-10'
provider_name: tubetranscript-io
provider_slug: tubetranscript-io
slug: tubetranscript-io-eligibility
source_date: '2026-11-10'
source_filename: tubetranscript-io-eligibility.yml
source_heading: Eligibility
source_page: https://tubetranscript.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tubetranscript-io\naid: tubetranscript-io\nurl: https://tubetranscript.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the service on behalf of an organization, you confirm that you are allowed to accept these terms\n    for it.\nrestricted_uses:\n- summary: Infringing, unlawful or deceptive use\n  text: use the service to infringe copyright or privacy rights, or for unlawful, harassing or deceptive purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: You must be old enough to enter a binding contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/tubetranscript-io/eligibility/tubetranscript-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from tubetranscript-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- YouTube
- Transcript
---
