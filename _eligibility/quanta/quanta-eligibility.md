---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for visitors located within the United States. Company makes no representation that the Service is appropriate or available for use outside of the United States.
  entity_types:
  - text: 'If Customer is an entity, organization, or company, then: a) the individual accepting this Agreement on Customer’s behalf represents and warrants that they have authority to bind Customer to this Agreement'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful access or use
    text: Access to the Service from countries or territories or by individuals where such access is illegal is prohibited.
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
name: Quanta
provenance_date: '2026-11-10'
provider_name: Quanta
provider_slug: quanta
slug: quanta-eligibility
source_date: '2026-11-10'
source_filename: quanta-eligibility.yml
source_heading: Eligibility
source_page: https://www.usequanta.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quanta\naid: quanta\nurl: https://www.usequanta.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for visitors located within the United States. Company makes no representation that\n    the Service is appropriate or available for use outside of the United States.\nentity_types:\n- type: business\n  text: 'If Customer is an entity, organization, or company, then: a) the individual accepting this Agreement on\n    Customer’s behalf represents and warrants that they have authority to bind Customer to this Agreement'\nrestricted_uses:\n- summary: Unlawful\
  \ access or use\n  text: Access to the Service from countries or territories or by individuals where such access is illegal is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/quanta/eligibility/quanta-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Quanta's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Saas
- Accounting
- Fintech
- Bookkeeping
- Financial Reporting
- SaaS Finance
- Controller Services
---
