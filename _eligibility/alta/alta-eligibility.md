---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept or agree to these Terms of Service on behalf of your employer or another legal entity, you represent and warrant that (i) you have full legal authority to bind your employer
    type: business
  minimum_age:
    text: You must be at least 13 years old to access and use the Site.
    value: '13'
  restricted_uses:
  - summary: Unlawful or discriminatory use
    text: You may not use the Services for any unlawful or discriminatory activities, including acts prohibited by laws that apply to commerce.
  - summary: Sensitive customer information
    text: Agree not to use the Services to collect, manage or process sensitive customer information
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: You must register with Alta and create an account to use the Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Alta
provenance_date: '2026-11-09'
provider_name: Alta
provider_slug: alta
slug: alta-eligibility
source_date: '2026-11-09'
source_filename: alta-eligibility.yml
source_heading: Eligibility
source_page: https://www.altadaily.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alta\naid: alta\nurl: https://www.altadaily.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept or agree to these Terms of Service on behalf of your employer or another legal entity, you\n    represent and warrant that (i) you have full legal authority to bind your employer\nrestricted_uses:\n- summary: Unlawful or discriminatory use\n  text: You may not use the Services for any unlawful or discriminatory activities, including acts prohibited by\n    laws that apply to commerce.\n- summary: Sensitive customer\
  \ information\n  text: Agree not to use the Services to collect, manage or process sensitive customer information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: You must register with Alta and create an account to use the Services\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to access and use the Site.\n"
source_yaml_url: https://artifacts.apis.io/alta/eligibility/alta-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Alta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Fashion
- Styling
- Shopping
- E-Commerce
- Consumer Applications
- Generative AI
- Agentic Commerce
---
