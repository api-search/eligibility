---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF CUSTOMER IS AN INDIVIDUAL AGREEING TO THE TERMS OF THIS AGREEMENT AND THE PRIVACY POLICY ON BEHALF OF THE CUSTOMER’S LEGAL ENTITY, CUSTOMER REPRESENTS THAT SUCH INDIVIDUAL HAS THE LEGAL AUTHORITY TO BIND SUCH ENTITY.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Protected health information limits
    text: Customer agrees to only upload or transmit to Ottimate the minimum necessary amount of Protected Health Information (“PHI”) reasonably required for Ottimate’s provision of the Services.
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
name: Paro
provenance_date: '2026-11-10'
provider_name: Paro
provider_slug: plateiq-com
slug: plateiq-com-eligibility
source_date: '2026-11-10'
source_filename: plateiq-com-eligibility.yml
source_heading: Eligibility
source_page: https://ottimate.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paro\naid: plateiq-com\nurl: https://ottimate.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF CUSTOMER IS AN INDIVIDUAL AGREEING TO THE TERMS OF THIS AGREEMENT AND THE PRIVACY POLICY ON BEHALF OF\n    THE CUSTOMER’S LEGAL ENTITY, CUSTOMER REPRESENTS THAT SUCH INDIVIDUAL HAS THE LEGAL AUTHORITY TO BIND SUCH ENTITY.\nrestricted_uses:\n- summary: Protected health information limits\n  text: Customer agrees to only upload or transmit to Ottimate the minimum necessary amount of Protected Health\n    Information (“PHI”)\
  \ reasonably required for Ottimate’s provision of the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/plateiq-com/eligibility/plateiq-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Paro's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Automation
- Artificial Intelligence
- AP
---
