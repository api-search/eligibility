---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service may not be appropriate or available for use in some non-U.S. jurisdictions. Reforge may limit the Service's availability at any time, in whole or in part, to any person, geographic area or jurisdiction that it chooses.
  entity_types:
  - text: “Customer” means the company defined in the Order Form, which orders the Service
    type: business
  - text: AFFIRMS THAT YOU ARE AT LEAST 18 YEARS OF AGE
    type: individual
  minimum_age:
    text: AFFIRMS THAT YOU ARE AT LEAST 18 YEARS OF AGE (OR HAVE REACHED THE AGE OF MAJORITY IN THE JURISDICTION WHERE YOU RESIDE)
    value: '18'
  restricted_uses:
  - summary: Sensitive data
    text: Customer shall not, and shall not permit any of its Authorized Users to, provide or make available any Sensitive Content to Reforge
  - summary: Unlawful or monitoring use
    text: (vii) access or use (or permit a third party to access or use) the Service for any unlawful purpose or for purposes of monitoring the availability, performance or functionality of the Service or for any other benchmarking or competitive purposes
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
name: Reforge
provenance_date: '2026-11-10'
provider_name: Reforge
provider_slug: reforge
slug: reforge-eligibility
source_date: '2026-11-10'
source_filename: reforge-eligibility.yml
source_heading: Eligibility
source_page: https://www.reforge.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reforge\naid: reforge\nurl: https://www.reforge.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Service may not be appropriate or available for use in some non-U.S. jurisdictions. Reforge may limit\n    the Service's availability at any time, in whole or in part, to any person, geographic area or jurisdiction\n    that it chooses.\nentity_types:\n- type: business\n  text: “Customer” means the company defined in the Order Form, which orders the Service\n- type: individual\n  text: AFFIRMS THAT YOU ARE AT LEAST 18 YEARS OF AGE\nrestricted_uses:\n\
  - summary: Sensitive data\n  text: Customer shall not, and shall not permit any of its Authorized Users to, provide or make available any Sensitive\n    Content to Reforge\n- summary: Unlawful or monitoring use\n  text: (vii) access or use (or permit a third party to access or use) the Service for any unlawful purpose or for\n    purposes of monitoring the availability, performance or functionality of the Service or for any other benchmarking\n    or competitive purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: AFFIRMS THAT YOU ARE AT LEAST 18 YEARS OF AGE (OR HAVE REACHED THE AGE OF MAJORITY IN THE JURISDICTION WHERE\n    YOU RESIDE)\n"
source_yaml_url: https://artifacts.apis.io/reforge/eligibility/reforge-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Reforge's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Feature Flags
- Feature Management
- Dynamic Configuration
- Live Config
- Experimentation
- Developer Tools
- SDK
- Observability
---
