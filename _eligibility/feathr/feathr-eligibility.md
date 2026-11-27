---
api_specs:
- filename: feathr-openapi-generated.yml
  format: yaml
  label: Feathr API
  slug: feathr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/feathr/openapi/_ae-authored/feathr-openapi-generated.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be at least 18 years old and reside in the United States to create an Account.
  entity_types:
  - text: agreeing entities on behalf of itself and its affiliated entities (hereafter, “ Client ”)
    type: business
  - text: By creating an Account, logging in and using the Service, you represent and warrant that you are at least 18 years old and reside in the United States.
    type: individual
  - text: Non-profits that use the Feathr Platform are subject to a separate agreement with Feathr, and nothing herein is intended to modify or amend such agreement.
    type: nonprofit
  minimum_age:
    text: You must be at least 18 years old and reside in the United States to create an Account.
    value: '18'
  restricted_uses:
  - summary: No sensitive personal data collection
    text: Feathr does not permit the collection of social security numbers, credit card information, or any private medical information through the Feathr Materials.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to create an Account, you must either (i) provide Feathr with a valid email address or (ii) sign in through a third-party account, such as your Google account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Feathr
provenance_date: '2026-11-09'
provider_name: Feathr
provider_slug: feathr
slug: feathr-eligibility
source_date: '2026-11-09'
source_filename: feathr-eligibility.yml
source_heading: Eligibility
source_page: https://www.feathr.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Feathr\naid: feathr\nurl: https://www.feathr.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be at least 18 years old and reside in the United States to create an Account.\nentity_types:\n- type: business\n  text: agreeing entities on behalf of itself and its affiliated entities (hereafter, “ Client ”)\n- type: individual\n  text: By creating an Account, logging in and using the Service, you represent and warrant that you are at least\n    18 years old and reside in the United States.\n- type: nonprofit\n  text: Non-profits that use the Feathr\
  \ Platform are subject to a separate agreement with Feathr, and nothing herein\n    is intended to modify or amend such agreement.\nrestricted_uses:\n- summary: No sensitive personal data collection\n  text: Feathr does not permit the collection of social security numbers, credit card information, or any private\n    medical information through the Feathr Materials.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to create an Account, you must either (i) provide Feathr with a valid email address or (ii) sign\n    in through a third-party account, such as your Google account.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and reside in the United States to create an Account.\n"
source_yaml_url: https://artifacts.apis.io/feathr/eligibility/feathr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Feathr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Digital Marketing
- Artificial Intelligence
- Non-Profit
- Event Promotion
---
