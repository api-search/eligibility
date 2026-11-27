---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you have the authority to bind that entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No money laundering or sanctions evasion
    text: Use the platform to facilitate money laundering, terrorist financing, sanctions evasion, or any illegal activity.
  - summary: No surveillance or harassment
    text: Scan wallet addresses for the purpose of surveillance, harassment, stalking, or violating the privacy rights of others.
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
name: asof-xyz
provenance_date: '2026-11-09'
provider_name: asof-xyz
provider_slug: asof-xyz
slug: asof-xyz-eligibility
source_date: '2026-11-09'
source_filename: asof-xyz-eligibility.yml
source_heading: Eligibility
source_page: https://asof.xyz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: asof-xyz\naid: asof-xyz\nurl: https://asof.xyz/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you\n    have the authority to bind that entity.\nrestricted_uses:\n- summary: No money laundering or sanctions evasion\n  text: Use the platform to facilitate money laundering, terrorist financing, sanctions evasion, or any illegal\n    activity.\n- summary: No surveillance or harassment\n  text: Scan wallet addresses for the purpose\
  \ of surveillance, harassment, stalking, or violating the privacy rights\n    of others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/asof-xyz/eligibility/asof-xyz-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from asof-xyz's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Cryptocurrency
- Wallets
- Analytics
---
