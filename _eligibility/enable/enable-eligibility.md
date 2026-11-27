---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. Government embargo
  entity_types:
  - text: you are of legal age to form a binding contract with COMPANY
    type: individual
  - text: YOU HAVE THE AUTHORITY TO ENTER INTO THE TERMS OF USE PERSONALLY OR ON BEHALF OF THE ENTITY YOU HAVE NAMED AS THE USER
    type: business
  minimum_age:
    text: you are of legal age to form a binding contract with COMPANY
    value: legal age
  restricted_uses:
  - summary: Protected health and regulated content
    text: Make Available any Content that, in Company’s sole discretion, (i) is subject to any government regulations or privacy, health or data security laws, including protected health information (as defined by HIPAA)
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: No contract will exist between you and Company for the Services until Company accepts your order by a confirmatory e-mail
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Enable
provenance_date: '2026-11-09'
provider_name: Enable
provider_slug: enable
slug: enable-eligibility
source_date: '2026-11-09'
source_filename: enable-eligibility.yml
source_heading: Eligibility
source_page: https://www.enablemedicine.com/legal/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Enable\naid: enable\nurl: https://www.enablemedicine.com/legal/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. Government embargo\nentity_types:\n- type: individual\n  text: you are of legal age to form a binding contract with COMPANY\n- type: business\n  text: YOU HAVE THE AUTHORITY TO ENTER INTO THE TERMS OF USE PERSONALLY OR ON BEHALF OF THE ENTITY YOU HAVE NAMED\n    AS THE USER\nrestricted_uses:\n- summary: Protected health and regulated content\n  text: Make Available any Content that, in Company’s\
  \ sole discretion, (i) is subject to any government regulations\n    or privacy, health or data security laws, including protected health information (as defined by HIPAA)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: No contract will exist between you and Company for the Services until Company accepts your order by a confirmatory\n    e-mail\nminimum_age:\n  value: legal age\n  text: you are of legal age to form a binding contract with COMPANY\n"
source_yaml_url: https://artifacts.apis.io/enable/eligibility/enable-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Enable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Life Sciences
- Spatial Biology
- Biopharma
- Data Platform
- Oncology
- Artificial Intelligence
---
