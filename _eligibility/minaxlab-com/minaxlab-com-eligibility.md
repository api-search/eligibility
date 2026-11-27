---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old (or the age of majority where you live) and able to form a binding contract.
    type: individual
  - text: If you use the Service on behalf of an organization, you represent that you are authorized to bind it.
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority where you live)
    value: '18'
  restricted_uses:
  - summary: Deepfakes and non-consensual depictions
    text: depicts real, identifiable people in sexual, defamatory, or misleading ways without their consent
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
name: minaxlab-com
provenance_date: '2026-11-10'
provider_name: minaxlab-com
provider_slug: minaxlab-com
slug: minaxlab-com-eligibility
source_date: '2026-11-10'
source_filename: minaxlab-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.minaxlab.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: minaxlab-com\naid: minaxlab-com\nurl: https://www.minaxlab.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority where you live) and able to form a binding contract.\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you are authorized to bind it.\nrestricted_uses:\n- summary: Deepfakes and non-consensual depictions\n  text: depicts real, identifiable people in sexual, defamatory, or misleading ways without their consent\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority where you live)\n"
source_yaml_url: https://artifacts.apis.io/minaxlab-com/eligibility/minaxlab-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from minaxlab-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Creative
- Tools
- Platform
---
