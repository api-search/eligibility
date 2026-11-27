---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you must be a natural person who is a U.S. Citizen or U.S. resident with a U.S. Social Security Number or Individual Taxpayer Identification Number who resides in the U.S.
  entity_types:
  - text: you must be a natural person who is a U.S. Citizen or U.S. resident
    type: individual
  - text: Businesses, such as corporations, partnerships and trusts, are not eligible to use the Service.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraud or illegal conduct
    text: use Raisin.com or any of the content contained therein in connection with any fraudulent or illegal conduct, transaction, or business, as determined by us in our sole discretion
  verification:
    approval_required: null
    kyb: false
    kyc: true
    text: we require that you complete our identify verification procedures at the time of the request. This may include, but may not be limited to, identity verification through either a digital identity verification service
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Raisin
provenance_date: '2026-11-10'
provider_name: Raisin
provider_slug: raisin
slug: raisin-eligibility
source_date: '2026-11-10'
source_filename: raisin-eligibility.yml
source_heading: Eligibility
source_page: https://assets-us.raisin.com/en-us/raisin_terms_of_service_cash_account.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Raisin\naid: raisin\nurl: https://assets-us.raisin.com/en-us/raisin_terms_of_service_cash_account.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you must be a natural person who is a U.S. Citizen or U.S. resident with a U.S. Social Security Number or\n    Individual Taxpayer Identification Number who resides in the U.S.\nentity_types:\n- type: individual\n  text: you must be a natural person who is a U.S. Citizen or U.S. resident\n- type: business\n  text: Businesses, such as corporations, partnerships and trusts, are not eligible to use the Service.\nrestricted_uses:\n\
  - summary: Fraud or illegal conduct\n  text: use Raisin.com or any of the content contained therein in connection with any fraudulent or illegal conduct,\n    transaction, or business, as determined by us in our sole discretion\nverification:\n  kyc: true\n  kyb: false\n  approval_required: null\n  text: we require that you complete our identify verification procedures at the time of the request. This may include,\n    but may not be limited to, identity verification through either a digital identity verification service\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/raisin/eligibility/raisin-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Raisin's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Savings
- Deposits
- Banking
- Marketplace
- Banking as a Service
- Wealth
---
