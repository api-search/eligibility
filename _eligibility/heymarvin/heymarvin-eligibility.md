---
api_specs:
- filename: heymarvin-openapi-generated.yml
  format: yaml
  label: HeyMarvin API
  slug: heymarvin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heymarvin/openapi/_ae-authored/heymarvin-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting these Terms on behalf of your employer or another entity (which will be deemed to the case if you sign up for the HeyMarvin Product using an email address from your employer or such entity) then you represent and warrant that
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Compliance with applicable law
    text: Customer shall use the HeyMarvin Product in compliance with applicable law.
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
name: HeyMarvin
provenance_date: '2026-11-09'
provider_name: HeyMarvin
provider_slug: heymarvin
slug: heymarvin-eligibility
source_date: '2026-11-09'
source_filename: heymarvin-eligibility.yml
source_heading: Eligibility
source_page: https://heymarvin.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HeyMarvin\naid: heymarvin\nurl: https://heymarvin.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting these Terms on behalf of your employer or another entity (which will be deemed to the\n    case if you sign up for the HeyMarvin Product using an email address from your employer or such entity) then\n    you represent and warrant that\nrestricted_uses:\n- summary: Compliance with applicable law\n  text: Customer shall use the HeyMarvin Product in compliance with applicable law.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/heymarvin/eligibility/heymarvin-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from HeyMarvin's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Customer Insights
- Analytics
- Software-as-a-Service
- Platform
---
