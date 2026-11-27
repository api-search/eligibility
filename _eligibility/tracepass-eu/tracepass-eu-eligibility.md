---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is offered only to businesses.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or infringing passport content
    text: You must not publish content that is illegal under EU or Member State law, or that infringes the rights of others, such as intellectual-property or personal-data rights.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'By registering you: Confirm that you register on behalf of a business, for the purposes of its trade, business or profession, and not as a consumer'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: tracepass-eu
provenance_date: '2026-11-10'
provider_name: tracepass-eu
provider_slug: tracepass-eu
slug: tracepass-eu-eligibility
source_date: '2026-11-10'
source_filename: tracepass-eu-eligibility.yml
source_heading: Eligibility
source_page: https://www.tracepass.eu/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tracepass-eu\naid: tracepass-eu\nurl: https://www.tracepass.eu/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is offered only to businesses.\nrestricted_uses:\n- summary: Illegal or infringing passport content\n  text: You must not publish content that is illegal under EU or Member State law, or that infringes the rights\n    of others, such as intellectual-property or personal-data rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'By registering you: Confirm that you register on\
  \ behalf of a business, for the purposes of its trade, business\n    or profession, and not as a consumer'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tracepass-eu/eligibility/tracepass-eu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from tracepass-eu's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Digital Product Passport
- EU-Regulation
- Sustainability
---
