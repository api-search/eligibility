---
api_specs:
- filename: leadfriendly-com-openapi-generated.yml
  format: yaml
  label: leadfriendly-com API
  slug: leadfriendly-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadfriendly-com/openapi/_ae-authored/leadfriendly-com-openapi-generated.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, legally able to enter into binding contracts
    type: individual
  - text: business verification (legal name, EIN, address, website) appropriate to your subscription tier and intended use of the Service
    type: business
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: HIPAA communications
    text: Communications subject to the Health Insurance Portability and Accountability Act
  - summary: FCRA consumer reporting
    text: Activities that would render Lead Friendly LLC a Consumer Reporting Agency under the Fair Credit Reporting Act
  - summary: Debt collection
    text: Debt collection activities subject to the Fair Debt Collection Practices Act ("FDCPA") or Regulation F unless Customer is a licensed debt collector
  verification:
    approval_required: true
    kyb: true
    kyc: true
    text: We may require identity verification (driver's license + selfie via a verification provider such as Stripe Identity or Persona) and business verification (legal name, EIN, address, website)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: leadfriendly-com
provenance_date: '2026-11-09'
provider_name: leadfriendly-com
provider_slug: leadfriendly-com
slug: leadfriendly-com-eligibility
source_date: '2026-11-09'
source_filename: leadfriendly-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.leadfriendly.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: leadfriendly-com\naid: leadfriendly-com\nurl: https://www.leadfriendly.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, legally able to enter into binding contracts\n- type: business\n  text: business verification (legal name, EIN, address, website) appropriate to your subscription tier and intended\n    use of the Service\nrestricted_uses:\n- summary: HIPAA communications\n  text: Communications subject to the Health Insurance Portability and Accountability Act\n- summary: FCRA consumer\
  \ reporting\n  text: Activities that would render Lead Friendly LLC a Consumer Reporting Agency under the Fair Credit Reporting\n    Act\n- summary: Debt collection\n  text: Debt collection activities subject to the Fair Debt Collection Practices Act (\"FDCPA\") or Regulation F unless\n    Customer is a licensed debt collector\nverification:\n  kyc: true\n  kyb: true\n  approval_required: true\n  text: We may require identity verification (driver's license + selfie via a verification provider such as Stripe\n    Identity or Persona) and business verification (legal name, EIN, address, website)\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/leadfriendly-com/eligibility/leadfriendly-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from leadfriendly-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- CRM
- Voice
- Small Business
- Telephony
---
