---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use Curated. If you are between 13 and the age of majority in your jurisdiction, you must have permission from a parent or guardian.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use Curated.
    value: '13'
  restricted_uses:
  - summary: Prohibited content
    text: 'You agree not to publish or transmit content that is: (a) NSFW or sexually explicit without an age gate'
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
name: Curated
provenance_date: '2026-11-09'
provider_name: Curated
provider_slug: curated-network
slug: curated-network-eligibility
source_date: '2026-11-09'
source_filename: curated-network-eligibility.yml
source_heading: Eligibility
source_page: https://curated.network/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Curated\naid: curated-network\nurl: https://curated.network/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use Curated. If you are between 13 and the age of majority in your\n    jurisdiction, you must have permission from a parent or guardian.\nrestricted_uses:\n- summary: Prohibited content\n  text: 'You agree not to publish or transmit content that is: (a) NSFW or sexually explicit without an age gate'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use Curated.\n"
source_yaml_url: https://artifacts.apis.io/curated-network/eligibility/curated-network-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Curated's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Recommendations
- Community
- List
- Curated
---
