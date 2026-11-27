---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for use by businesses and developers building software products; it is not a consumer service and is not designed for personal or household use.
    type: business
  - text: The Service is intended for use by businesses and developers building software products
    type: developer
  minimum_age:
    text: You may use the Service only if you are at least 18 years old (or the age of majority in your jurisdiction)
    value: '18'
  restricted_uses:
  - summary: Competitors
    text: You may not access the Service if you are a competitor of MemorySync and your purpose is to copy features, copy documentation, monitor availability or performance for competitive benchmarking, or build a competing product or service, except as expressly permitted by applicable law.
  - summary: Automated significant decisions
    text: Use the Service to make automated decisions that produce legal or similarly significant effects on individuals without appropriate human oversight and safeguards required by law.
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
name: memorysync-io
provenance_date: '2026-11-10'
provider_name: memorysync-io
provider_slug: memorysync-io
slug: memorysync-io-eligibility
source_date: '2026-11-10'
source_filename: memorysync-io-eligibility.yml
source_heading: Eligibility
source_page: https://memorysync.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: memorysync-io\naid: memorysync-io\nurl: https://memorysync.io/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended for use by businesses and developers building software products; it is not a consumer\n    service and is not designed for personal or household use.\n- type: developer\n  text: The Service is intended for use by businesses and developers building software products\nrestricted_uses:\n- summary: Competitors\n  text: You may not access the Service if you are a competitor of MemorySync and your\
  \ purpose is to copy features,\n    copy documentation, monitor availability or performance for competitive benchmarking, or build a competing product\n    or service, except as expressly permitted by applicable law.\n- summary: Automated significant decisions\n  text: Use the Service to make automated decisions that produce legal or similarly significant effects on individuals\n    without appropriate human oversight and safeguards required by law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Service only if you are at least 18 years old (or the age of majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/memorysync-io/eligibility/memorysync-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from memorysync-io's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- Infrastructure
- Platform
- Developer Tools
- Company
---
