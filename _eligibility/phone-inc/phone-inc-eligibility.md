---
api_specs:
- filename: phone-inc-openapi-generated.yml
  format: yaml
  label: Phone Inc API
  slug: phone-inc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phone-inc/openapi/_ae-authored/phone-inc-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Phone.inc routes voice traffic to the United States.
  entity_types:
  - text: Phone.inc is a service for business customers only.
    type: business
  minimum_age:
    text: By signing up, you confirm that you're using it for business purposes, that you're at least 18 years old, and that you're authorized to accept these terms on behalf of your company.
    value: '18'
  restricted_uses:
  - summary: Robocalls and spam
    text: Originate robocalls, spam calls, or any other calling activity that violates U.S. federal or state law, including the TCPA, the Truth in Caller ID Act, or FCC regulations at 47 CFR § 64.1200 and § 64.6305.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We may require you to complete a full Know Your Customer (KYC) check and provide proof of address at any time, at our discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Phone Inc
provenance_date: '2026-11-10'
provider_name: Phone Inc
provider_slug: phone-inc
slug: phone-inc-eligibility
source_date: '2026-11-10'
source_filename: phone-inc-eligibility.yml
source_heading: Eligibility
source_page: https://www.phone.inc/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Phone Inc\naid: phone-inc\nurl: https://www.phone.inc/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Phone.inc routes voice traffic to the United States.\nentity_types:\n- type: business\n  text: Phone.inc is a service for business customers only.\nrestricted_uses:\n- summary: Robocalls and spam\n  text: Originate robocalls, spam calls, or any other calling activity that violates U.S. federal or state law,\n    including the TCPA, the Truth in Caller ID Act, or FCC regulations at 47 CFR § 64.1200 and § 64.6305.\nverification:\n  kyc: true\n  kyb: null\n  approval_required:\
  \ null\n  text: We may require you to complete a full Know Your Customer (KYC) check and provide proof of address at any\n    time, at our discretion.\nminimum_age:\n  value: '18'\n  text: By signing up, you confirm that you're using it for business purposes, that you're at least 18 years old,\n    and that you're authorized to accept these terms on behalf of your company.\n"
source_yaml_url: https://artifacts.apis.io/phone-inc/eligibility/phone-inc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Phone Inc's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Communications
- Cloud
- Business
---
