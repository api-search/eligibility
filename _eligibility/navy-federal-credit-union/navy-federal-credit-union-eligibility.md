---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may not use the API Exchange and Developer Portal unless you are at least 18 years old.
    type: individual
  - text: If you are agreeing to the terms of this Agreement on behalf of an organization or entity, you represent and warrant that you are so authorized to agree on behalf of that organization or entity.
    type: business
  minimum_age:
    text: You may not use the API Exchange and Developer Portal unless you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No fraudulent or illegal use
    text: Access or use the API Exchange, Developer Portal, Documentation or Services for any purpose or in any manner other than expressly permitted in this Agreement or the Documentation, including but not limited to any unlawful, fraudulent, infringing, abusive, threatening, defamatory, disparaging, or obscene purpose
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
name: Navy Federal Credit Union
provenance_date: '2026-11-10'
provider_name: Navy Federal Credit Union
provider_slug: navy-federal-credit-union
slug: navy-federal-credit-union-eligibility
source_date: '2026-11-10'
source_filename: navy-federal-credit-union-eligibility.yml
source_heading: Eligibility
source_page: https://developer.navyfederal.org/terms-and-conditions.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Navy Federal Credit Union\naid: navy-federal-credit-union\nurl: https://developer.navyfederal.org/terms-and-conditions.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may not use the API Exchange and Developer Portal unless you are at least 18 years old.\n- type: business\n  text: If you are agreeing to the terms of this Agreement on behalf of an organization or entity, you represent\n    and warrant that you are so authorized to agree on behalf of that organization or entity.\nrestricted_uses:\n- summary: No fraudulent or\
  \ illegal use\n  text: Access or use the API Exchange, Developer Portal, Documentation or Services for any purpose or in any manner\n    other than expressly permitted in this Agreement or the Documentation, including but not limited to any unlawful,\n    fraudulent, infringing, abusive, threatening, defamatory, disparaging, or obscene purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not use the API Exchange and Developer Portal unless you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/navy-federal-credit-union/eligibility/navy-federal-credit-union-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Navy Federal Credit Union's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- Credit Union
- Open Finance
- Open Banking
- Payments
---
