---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents it will not make the Service available to any Authorized User or entity located in a country subject to a U.S. government embargo.
  entity_types:
  - text: the Service is for business use and not for consumers
    type: business
  - text: it is a corporation, the sole proprietorship of an individual 18 years or older, or another entity authorized to do business pursuant to applicable law
    type: individual
  minimum_age:
    text: the sole proprietorship of an individual 18 years or older
    value: '18'
  restricted_uses:
  - summary: No consumer use
    text: it will use the Service for internal business purposes and not for personal, family, household, or other consumer purposes
  - summary: No diagnostic or health use
    text: Tests and assessments within the Service are not intended for diagnostic or treatment purposes and are not intended for mental health, medical, or other health-related purposes.
  - summary: No sensitive data
    text: the Service is not intended to store or use sensitive personal information such as credit reporting information, credit card numbers
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
name: Criteria Corp
provenance_date: '2026-11-09'
provider_name: Criteria Corp
provider_slug: criteria-corp
slug: criteria-corp-eligibility
source_date: '2026-11-09'
source_filename: criteria-corp-eligibility.yml
source_heading: Eligibility
source_page: https://www.criteriacorp.com/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Criteria Corp\naid: criteria-corp\nurl: https://www.criteriacorp.com/terms-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents it will not make the Service available to any Authorized User or entity located in a\n    country subject to a U.S. government embargo.\nentity_types:\n- type: business\n  text: the Service is for business use and not for consumers\n- type: individual\n  text: it is a corporation, the sole proprietorship of an individual 18 years or older, or another entity authorized\n    to do business pursuant to applicable law\nrestricted_uses:\n-\
  \ summary: No consumer use\n  text: it will use the Service for internal business purposes and not for personal, family, household, or other\n    consumer purposes\n- summary: No diagnostic or health use\n  text: Tests and assessments within the Service are not intended for diagnostic or treatment purposes and are not\n    intended for mental health, medical, or other health-related purposes.\n- summary: No sensitive data\n  text: the Service is not intended to store or use sensitive personal information such as credit reporting information,\n    credit card numbers\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the sole proprietorship of an individual 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/criteria-corp/eligibility/criteria-corp-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Criteria Corp's own page on 2026-11-09.
synthetic: false
tags:
- Pre-Employment Testing
- Assessment
- Video Interviewing
- Talent Development
- AI Proctoring
- Enterprise Hiring
---
