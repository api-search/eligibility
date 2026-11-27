---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: In order to use our Services you must be legally eligible to work in the U.S. and at least 16 years old.
  entity_types:
  - text: these Terms of Service constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Service is intended for users who are at least 16 years of age.
    value: '16'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You will not use the Service for any illegal or unauthorized purpose.
  - summary: Advertising or selling goods via Service
    text: Use the Service to advertise or offer to sell goods and services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: JobGet
provenance_date: '2026-11-09'
provider_name: JobGet
provider_slug: jobget
slug: jobget-eligibility
source_date: '2026-11-09'
source_filename: jobget-eligibility.yml
source_heading: Eligibility
source_page: https://www.jobget.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JobGet\naid: jobget\nurl: https://www.jobget.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: In order to use our Services you must be legally eligible to work in the U.S. and at least 16 years old.\nentity_types:\n- type: business\n  text: these Terms of Service constitute a legally binding agreement made between you, whether personally or on\n    behalf of an entity\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: You will not use the Service for any illegal or unauthorized purpose.\n- summary: Advertising or selling goods via Service\n\
  \  text: Use the Service to advertise or offer to sell goods and services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with the Service.\nminimum_age:\n  value: '16'\n  text: The Service is intended for users who are at least 16 years of age.\n"
source_yaml_url: https://artifacts.apis.io/jobget/eligibility/jobget-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from JobGet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Job
- Recruiting
- Hiring
- Human Resources
- Talent Acquisition
- Job Search
- Hourly Work
- Applicant Tracking
- Marketplace
- Mobile
---
