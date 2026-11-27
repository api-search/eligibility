---
claim_count: 8
description: ''
doc:
  countries:
    excluded: []
    served:
    - SA
    text: Ejari offers secure and flexible rental solutions for landlords and tenants across Saudi Arabia.
  entity_types:
  - text: You must be at least 18 years of age to use the Services.
    type: individual
  - text: If you are entering into this agreement on behalf of a business or other legal entity, you represent that you have the authority to bind such entity to this agreement
    type: business
  - text: 'Real Estate Broker or Owner: Any real estate brokerage office, property management company, or property owner who registers on the platform to facilitate tenants’ access to the “Rent Now, Pay Later” service.'
    type: other
  minimum_age:
    text: You must be at least 18 years of age to use the Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: (a) for any unlawful purpose
  - summary: Submitting false information
    text: (f) to submit false or misleading information
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may monitor and review new accounts before you may sign in and start using the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ejari Co.
provenance_date: '2026-11-09'
provider_name: Ejari Co.
provider_slug: ejari-co
slug: ejari-co-eligibility
source_date: '2026-11-09'
source_filename: ejari-co-eligibility.yml
source_heading: Eligibility
source_page: https://ejari.sa/en/tnc/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ejari Co.\naid: ejari-co\nurl: https://ejari.sa/en/tnc/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - SA\n  excluded: []\n  text: Ejari offers secure and flexible rental solutions for landlords and tenants across Saudi Arabia.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Services.\n- type: business\n  text: If you are entering into this agreement on behalf of a business or other legal entity, you represent that\n    you have the authority to bind such entity to this agreement\n- type: other\n  text: 'Real Estate Broker or Owner: Any real estate brokerage\
  \ office, property management company, or property\n    owner who registers on the platform to facilitate tenants’ access to the “Rent Now, Pay Later” service.'\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: (a) for any unlawful purpose\n- summary: Submitting false information\n  text: (f) to submit false or misleading information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may monitor and review new accounts before you may sign in and start using the Services.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/ejari-co/eligibility/ejari-co-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 8 quoted statements, read from Ejari Co.'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- PropTech
- Fintech
- Rent Now Pay Later
- Payments
- Leasing
- Housing
- Saudi Arabia
---
