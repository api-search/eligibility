---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Clients are individuals and/or businesses seeking to obtain task services
    type: individual
  - text: Taskers are individuals and/or businesses seeking to perform Tasks
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Violating Marketplace Guidelines
    text: Use the Services in violation of the Marketplace Guidelines.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Clients and Taskers may be subject to an extensive vetting process before they can register and during their use of the Service, including but not limited to a verification of identity
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: JOBDOH
provenance_date: '2026-11-09'
provider_name: JOBDOH
provider_slug: jobdoh
slug: jobdoh-eligibility
source_date: '2026-11-09'
source_filename: jobdoh-eligibility.yml
source_heading: Eligibility
source_page: https://www.jobdoh.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JOBDOH\naid: jobdoh\nurl: https://www.jobdoh.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Clients are individuals and/or businesses seeking to obtain task services\n- type: business\n  text: Taskers are individuals and/or businesses seeking to perform Tasks\nrestricted_uses:\n- summary: Violating Marketplace Guidelines\n  text: Use the Services in violation of the Marketplace Guidelines.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Clients and Taskers may be subject to an extensive vetting\
  \ process before they can register and during their\n    use of the Service, including but not limited to a verification of identity\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jobdoh/eligibility/jobdoh-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from JOBDOH's own page on 2026-11-09.
synthetic: false
tags:
- Company
- On-Demand Staffing
- Recruiting
- Hiring
- Temporary Work
- Human Resources
- Job
- Gig Economy
- Hong Kong
---
