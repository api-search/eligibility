---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity (such as a trust or limited liability company of which you are a member), you represent and warrant that you have the authority on behalf of such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competing products
    text: Customer will not use or reference the Services to develop or offer a competing service or product
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
name: Lula (maintenance)
provenance_date: '2026-11-09'
provider_name: Lula (maintenance)
provider_slug: lula-life
slug: lula-life-eligibility
source_date: '2026-11-09'
source_filename: lula-life-eligibility.yml
source_heading: Eligibility
source_page: https://lula.life/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lula (maintenance)\naid: lula-life\nurl: https://lula.life/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity (such as a trust or limited liability company of which you are a member), you represent and warrant that\n    you have the authority on behalf of such entity\nrestricted_uses:\n- summary: Competing products\n  text: Customer will not use or reference the Services to develop or offer a competing service\
  \ or product\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lula-life/eligibility/lula-life-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Lula (maintenance)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Property Management
- Maintenance
- Real Estate
---
