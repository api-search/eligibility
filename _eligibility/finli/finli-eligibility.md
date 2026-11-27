---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: In order to use the Payment Services, you must ... (iii) use the Services on behalf of a United States-domiciled business entity or freelancer.
  entity_types:
  - text: If you are a business your Dispute shall be subject to the AAA Commercial Rules
    type: business
  - text: if you are an individual your Dispute shall be subject to the AAA Consumer Rules.
    type: individual
  minimum_age:
    text: you must (i) be an individual of at least 18 years of age and able to form legally binding contracts under applicable law
    value: '18'
  restricted_uses:
  - summary: Prohibited Businesses
    text: You may not use the Payment Services to enable any person (including you) to benefit from any activities Finli has identified as a prohibited business or activity
  - summary: Restricted payment activities
    text: send or receive fraudulent funds;
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You authorize Finli or a Third Party Service Provider, directly or through third parties, to make any inquiries they consider necessary to validate your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Finli
provenance_date: '2026-11-09'
provider_name: Finli
provider_slug: finli
slug: finli-eligibility
source_date: '2026-11-09'
source_filename: finli-eligibility.yml
source_heading: Eligibility
source_page: https://finli.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Finli\naid: finli\nurl: https://finli.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: In order to use the Payment Services, you must ... (iii) use the Services on behalf of a United States-domiciled\n    business entity or freelancer.\nentity_types:\n- type: business\n  text: If you are a business your Dispute shall be subject to the AAA Commercial Rules\n- type: individual\n  text: if you are an individual your Dispute shall be subject to the AAA Consumer Rules.\nrestricted_uses:\n- summary: Prohibited Businesses\n  text: You may not\
  \ use the Payment Services to enable any person (including you) to benefit from any activities\n    Finli has identified as a prohibited business or activity\n- summary: Restricted payment activities\n  text: send or receive fraudulent funds;\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You authorize Finli or a Third Party Service Provider, directly or through third parties, to make any inquiries\n    they consider necessary to validate your identity.\nminimum_age:\n  value: '18'\n  text: you must (i) be an individual of at least 18 years of age and able to form legally binding contracts under\n    applicable law\n"
source_yaml_url: https://artifacts.apis.io/finli/eligibility/finli-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Finli's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Invoicing
- Small Business
- Billing
- Banking
- ACH
---
