---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Availability and coverages may vary by state.
  minimum_age:
    text: you warrant that you are at least 18 years of age or the age of majority in your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: solely for your personal, non-commercial use
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: To obtain insurance coverage, you must submit a complete application through our Site or our Services. Issuance of insurance will depend upon underwriting approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LeaseLock
provenance_date: '2026-11-09'
provider_name: LeaseLock
provider_slug: leaselock
slug: leaselock-eligibility
source_date: '2026-11-09'
source_filename: leaselock-eligibility.yml
source_heading: Eligibility
source_page: https://leaselock.com/terms-and-conditions-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LeaseLock\naid: leaselock\nurl: https://leaselock.com/terms-and-conditions-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Availability and coverages may vary by state.\nentity_types: []\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: solely for your personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: To obtain insurance coverage, you must submit a complete application through our Site or our Services. Issuance\n    of insurance will depend upon underwriting approval.\nminimum_age:\n  value: '18'\n\
  \  text: you warrant that you are at least 18 years of age or the age of majority in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/leaselock/eligibility/leaselock-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from LeaseLock's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Real Estate
- Rental Housing
- Property Management
- Risk Management
- Financial Services
---
