---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is intended for people age eighteen and older. By using our Site, you represent that you're at least 18.
    type: individual
  - text: If you are you using our Site on behalf of an entity, company or other organization (“Company”), you represent and warrant that you have the right and authority to create an Account on behalf of the Company
    type: business
  minimum_age:
    text: The Site is intended for people age eighteen and older. By using our Site, you represent that you're at least 18.
    value: '18'
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
name: QueryPal
provenance_date: '2026-11-10'
provider_name: QueryPal
provider_slug: querypal
slug: querypal-eligibility
source_date: '2026-11-10'
source_filename: querypal-eligibility.yml
source_heading: Eligibility
source_page: https://querypal.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: QueryPal\naid: querypal\nurl: https://querypal.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is intended for people age eighteen and older. By using our Site, you represent that you're at\n    least 18.\n- type: business\n  text: If you are you using our Site on behalf of an entity, company or other organization (“Company”), you represent\n    and warrant that you have the right and authority to create an Account on behalf of the Company\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for people age eighteen and older. By using our Site, you represent that you're at\n    least 18.\n"
source_yaml_url: https://artifacts.apis.io/querypal/eligibility/querypal-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from QueryPal's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Customer Service
- Enterprise
- Software-as-a-Service
---
