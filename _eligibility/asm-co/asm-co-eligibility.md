---
api_specs:
- filename: asm-co-openapi-generated.yml
  format: yaml
  label: Assembly API
  slug: asm-co-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asm-co/openapi/_ae-authored/asm-co-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If the billing address of your Store is located in the United States or Canada, this Section 4(1) applies to you
  entity_types:
  - text: You confirm that you are receiving any Services provided by Assembly for the purposes of carrying on a business activity and not for any personal, household or family purpose.
    type: business
  minimum_age:
    text: 'You must be the older of: (i) 18 years, or (ii) at least the age of majority in the jurisdiction where you reside and from which you use the Services to open an Account.'
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purpose
    text: You may not use the Assembly Services for any illegal or unauthorized purpose
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
name: Assembly
provenance_date: '2026-11-09'
provider_name: Assembly
provider_slug: asm-co
slug: asm-co-eligibility
source_date: '2026-11-09'
source_filename: asm-co-eligibility.yml
source_heading: Eligibility
source_page: https://assembly.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Assembly\naid: asm-co\nurl: https://assembly.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If the billing address of your Store is located in the United States or Canada, this Section 4(1) applies\n    to you\nentity_types:\n- type: business\n  text: You confirm that you are receiving any Services provided by Assembly for the purposes of carrying on a business\n    activity and not for any personal, household or family purpose.\nrestricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: You may not use the Assembly Services for any illegal\
  \ or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'You must be the older of: (i) 18 years, or (ii) at least the age of majority in the jurisdiction where\n    you reside and from which you use the Services to open an Account.'\n"
source_yaml_url: https://artifacts.apis.io/asm-co/eligibility/asm-co-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Assembly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Low-Code
- CRM
- Artificial Intelligence
- Software-as-a-Service
---
