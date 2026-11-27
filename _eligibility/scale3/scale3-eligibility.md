---
api_specs:
- filename: scale3-blockchain-intelligence-api-openapi.yml
  format: yaml
  label: Scale3 Blockchain Intelligence API
  slug: scale3-blockchain-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scale3/openapi/scale3-blockchain-intelligence-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may establish either an individual free account (“Free Account”), an individual user paid account (“Paid Account”)
    type: individual
  - text: If you are acting on behalf of another person or entity, you represent and warrant that such person or entity has authorized you to act and enter into legally binding contracts
    type: business
  minimum_age:
    text: minors in any jurisdiction and individuals who have been suspended or terminated from the Service may not use the Service
    value: not stated
  restricted_uses:
  - summary: Sanctioned or denied parties
    text: if you are a denied person, entity, or against any general denial order, as listed with the DOC
  - summary: Military end-use
    text: if your use is for military end-use not authorized under the applicable provision of the EAR, or if you are subject to U.S. trade sanctions
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Service is available only to users that can form legally binding contracts and accept contracts in the English language.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Scale3
provenance_date: '2026-11-10'
provider_name: Scale3
provider_slug: scale3
slug: scale3-eligibility
source_date: '2026-11-10'
source_filename: scale3-eligibility.yml
source_heading: Eligibility
source_page: https://www.scale3labs.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scale3\naid: scale3\nurl: https://www.scale3labs.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may establish either an individual free account (“Free Account”), an individual user paid account (“Paid\n    Account”)\n- type: business\n  text: If you are acting on behalf of another person or entity, you represent and warrant that such person or entity\n    has authorized you to act and enter into legally binding contracts\nrestricted_uses:\n- summary: Sanctioned or denied parties\n  text: if you are a denied\
  \ person, entity, or against any general denial order, as listed with the DOC\n- summary: Military end-use\n  text: if your use is for military end-use not authorized under the applicable provision of the EAR, or if you\n    are subject to U.S. trade sanctions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Service is available only to users that can form legally binding contracts and accept contracts in the\n    English language.\nminimum_age:\n  value: not stated\n  text: minors in any jurisdiction and individuals who have been suspended or terminated from the Service may not\n    use the Service\n"
source_yaml_url: https://artifacts.apis.io/scale3/eligibility/scale3-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Scale3's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Blockchain
- Web3
- Node Monitoring
- Observability
- Infrastructure
- Validator
- DevOps
- Alerting
- LLM Observability
---
