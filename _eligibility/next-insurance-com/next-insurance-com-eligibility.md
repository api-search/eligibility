---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Our Services are intended for use for those areas in the United States where we, our affiliates, our partner insurers, our brokers, or our agents are licensed and permitted to sell our products and services.
  entity_types:
  - text: You are authorized to purchase and bind this insurance on behalf of the entity applying for coverage.
    type: business
  minimum_age:
    text: You are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Non-commercial use restricted
    text: Our Services, as well as their underlying processes, related content, and generated data, may not be used for personal, family, household, informational, or non-commercial use.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Issuance of insurance coverage is dependent on underwriting approval; availability and coverages may vary by state.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Next Insurance
provenance_date: '2026-11-10'
provider_name: Next Insurance
provider_slug: next-insurance-com
slug: next-insurance-com-eligibility
source_date: '2026-11-10'
source_filename: next-insurance-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.nextinsurance.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Next Insurance\naid: next-insurance-com\nurl: https://www.nextinsurance.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Our Services are intended for use for those areas in the United States where we, our affiliates, our partner\n    insurers, our brokers, or our agents are licensed and permitted to sell our products and services.\nentity_types:\n- type: business\n  text: You are authorized to purchase and bind this insurance on behalf of the entity applying for coverage.\nrestricted_uses:\n- summary: Non-commercial use restricted\n  text: Our Services,\
  \ as well as their underlying processes, related content, and generated data, may not be used\n    for personal, family, household, informational, or non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Issuance of insurance coverage is dependent on underwriting approval; availability and coverages may vary\n    by state.\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/next-insurance-com/eligibility/next-insurance-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Next Insurance's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Insurance
- Small Business
- Fintech
- US
---
