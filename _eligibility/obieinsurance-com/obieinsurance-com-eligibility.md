---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Site and Services for use only by persons located in the United States
  entity_types:
  - text: If you are agreeing to be bound by these Terms on behalf of your employer or another entity, you must have the full legal authority to bind your employer or such entity to these Terms.
    type: business
  minimum_age:
    text: The Site and Services are offered and available to users who are 18 years of age or older and who reside in the United States.
    value: '18'
  restricted_uses:
  - summary: U.S. trade sanctions
    text: Obie does not provide insurance brokerage or other services to governments, governmental agencies, businesses, individuals, other groups, or any of their agents that are subject to U.S. trade sanctions.
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
name: Obie
provenance_date: '2026-11-10'
provider_name: Obie
provider_slug: obieinsurance-com
slug: obieinsurance-com-eligibility
source_date: '2026-11-10'
source_filename: obieinsurance-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.obieinsurance.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Obie\naid: obieinsurance-com\nurl: https://www.obieinsurance.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Site and Services for use only by persons located in the United States\nentity_types:\n- type: business\n  text: If you are agreeing to be bound by these Terms on behalf of your employer or another entity, you must have\n    the full legal authority to bind your employer or such entity to these Terms.\nrestricted_uses:\n- summary: U.S. trade sanctions\n  text: Obie does not provide insurance brokerage or other services to governments,\
  \ governmental agencies, businesses,\n    individuals, other groups, or any of their agents that are subject to U.S. trade sanctions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site and Services are offered and available to users who are 18 years of age or older and who reside\n    in the United States.\n"
source_yaml_url: https://artifacts.apis.io/obieinsurance-com/eligibility/obieinsurance-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Obie's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- Real Estate
- Fintech
- Landlords
- Investor
---
