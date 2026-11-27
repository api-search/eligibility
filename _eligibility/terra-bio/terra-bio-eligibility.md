---
api_specs:
- filename: terra-bio-public-api-openapi.yml
  format: yaml
  label: Terra Public API
  slug: terra-bio-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terra-bio/openapi/terra-bio-public-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any individual may become a Terra User.
    type: individual
  minimum_age:
    text: In order to use Terra you must be 18 years of age or older, unless you are accessing Terra in connection with your activities using your account authorized by a Non-Profit Entity, in which case you must be 16 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Protected health information
    text: You may not use Terra to Connect Content that includes PHI or special category personal data, unless your organization has signed an Enterprise License Agreement with us that includes a Business Associate Agreement (BAA).
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
name: Terra
provenance_date: '2026-11-10'
provider_name: Terra
provider_slug: terra-bio
slug: terra-bio-eligibility
source_date: '2026-11-10'
source_filename: terra-bio-eligibility.yml
source_heading: Eligibility
source_page: https://terra.bio/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Terra\naid: terra-bio\nurl: https://terra.bio/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Any individual may become a Terra User.\nrestricted_uses:\n- summary: Protected health information\n  text: You may not use Terra to Connect Content that includes PHI or special category personal data, unless your\n    organization has signed an Enterprise License Agreement with us that includes a Business Associate Agreement\n    (BAA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: In order to use Terra you must be 18 years of age or older, unless you are accessing Terra in connection\n    with your activities using your account authorized by a Non-Profit Entity, in which case you must be 16 years\n    of age or older.\n"
source_yaml_url: https://artifacts.apis.io/terra-bio/eligibility/terra-bio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Terra's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biomedical
- Data Analysis
- Collaboration
- Cloud Platform
---
