---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you are a legal resident of the United States. You agree not to attempt to log on to the Services from any country under sanctions by the Office of Foreign Assets Control (OFAC).
  entity_types:
  - text: We provide Services solely to businesses; we do not provide any Services to consumers.
    type: business
  - text: We are not accepting applications from individuals or sole proprietors.
    type: individual
  minimum_age:
    text: you represent and warrant that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Commercial use only
    text: You represent and certify that you intend to use the Services for commercial or business use only and not for personal use.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: For legal reasons, we also need to verify who you say you are.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Withco
provenance_date: '2026-11-10'
provider_name: Withco
provider_slug: withco
slug: withco-eligibility
source_date: '2026-11-10'
source_filename: withco-eligibility.yml
source_heading: Eligibility
source_page: https://with.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Withco\naid: withco\nurl: https://with.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you are a legal resident of the United States. You agree not to attempt to log on to the Services from any\n    country under sanctions by the Office of Foreign Assets Control (OFAC).\nentity_types:\n- type: business\n  text: We provide Services solely to businesses; we do not provide any Services to consumers.\n- type: individual\n  text: We are not accepting applications from individuals or sole proprietors.\nrestricted_uses:\n- summary: Commercial use only\n  text: You represent\
  \ and certify that you intend to use the Services for commercial or business use only and not\n    for personal use.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: For legal reasons, we also need to verify who you say you are.\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/withco/eligibility/withco-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Withco's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Small Business
- Commercial Real Estate
- Investing
- Community Ownership
- Main Street
---
