---
api_specs:
- filename: capmus-com-public-api-openapi.yml
  format: yaml
  label: Capmus Public API
  slug: capmus-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capmus-com/openapi/capmus-com-public-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are at least 18 years old (or the age of majority in your jurisdiction) and legally able to enter this agreement.
    type: individual
  - text: If you use the Service on behalf of an organization, you represent that you are authorized to bind that organization.
    type: business
  minimum_age:
    text: You represent that you are at least 18 years old (or the age of majority in your jurisdiction)
    value: '18'
  restricted_uses:
  - summary: Prohibited conduct
    text: Post or promote illegal goods, services, or activities.
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
name: Capmus
provenance_date: '2026-11-09'
provider_name: Capmus
provider_slug: capmus-com
slug: capmus-com-eligibility
source_date: '2026-11-09'
source_filename: capmus-com-eligibility.yml
source_heading: Eligibility
source_page: https://capmus.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Capmus\naid: capmus-com\nurl: https://capmus.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are at least 18 years old (or the age of majority in your jurisdiction) and legally\n    able to enter this agreement.\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you are authorized to bind that\n    organization.\nrestricted_uses:\n- summary: Prohibited conduct\n  text: Post or promote illegal goods, services, or activities.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are at least 18 years old (or the age of majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/capmus-com/eligibility/capmus-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Capmus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Classifieds
- Students
- Universities
- Housing
- Job
- Education
---
