---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Client: the natural person or legal entity who is the counterparty of Contents.ai.'
    type: individual
  minimum_age:
    text: The Client (if a natural person) warrants that they have reached the age of majority as defined in the country of their jurisdiction
    value: age of majority
  restricted_uses:
  - summary: Use prohibited in home country
    text: You may not use this website and receive the Services provided if this is prohibited in the Client’s home country or under any law or regulation applicable to the Client.
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
name: Contents.com
provenance_date: '2026-11-09'
provider_name: Contents.com
provider_slug: contentsdotcom
slug: contentsdotcom-eligibility
source_date: '2026-11-09'
source_filename: contentsdotcom-eligibility.yml
source_heading: Eligibility
source_page: https://www.contents.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Contents.com\naid: contentsdotcom\nurl: https://www.contents.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'Client: the natural person or legal entity who is the counterparty of Contents.ai.'\nrestricted_uses:\n- summary: Use prohibited in home country\n  text: You may not use this website and receive the Services provided if this is prohibited in the Client’s home\n    country or under any law or regulation applicable to the Client.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: age of majority\n  text: The Client (if a natural person) warrants that they have reached the age of majority as defined in the country\n    of their jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/contentsdotcom/eligibility/contentsdotcom-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Contents.com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Content
- Content Creation
- Generative AI
- Marketing
- Localization
- Translation
- Enterprise
- SEO
---
