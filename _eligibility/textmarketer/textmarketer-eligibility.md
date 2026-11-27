---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the ‘Customer’ means the entity purchasing business communication services from the Supplier.
    type: business
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
name: Text Marketer
provenance_date: '2026-11-10'
provider_name: Text Marketer
provider_slug: textmarketer
slug: textmarketer-eligibility
source_date: '2026-11-10'
source_filename: textmarketer-eligibility.yml
source_heading: Eligibility
source_page: https://www.textmarketer.co.uk/termsandconditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Text Marketer\naid: textmarketer\nurl: https://www.textmarketer.co.uk/termsandconditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the ‘Customer’ means the entity purchasing business communication services from the Supplier.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/textmarketer/eligibility/textmarketer-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Text Marketer's own page on 2026-11-10.
synthetic: false
tags:
- SMS
- Marketing
- United Kingdom
- Business
- Communications
---
