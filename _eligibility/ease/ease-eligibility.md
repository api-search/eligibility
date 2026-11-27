---
api_specs:
- filename: ease-incidents-api-openapi.yml
  format: yaml
  label: Ease Incidents API
  slug: ease-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ease/openapi/ease-incidents-api-openapi.yml
- filename: ease-maintenance-api-openapi.yml
  format: yaml
  label: Ease Maintenance API
  slug: ease-maintenance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ease/openapi/ease-maintenance-api-openapi.yml
- filename: ease-status-api-openapi.yml
  format: yaml
  label: Ease Status API
  slug: ease-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ease/openapi/ease-status-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: EASE offers its software services for a fee to brokers and some employers.
    type: business
  minimum_age:
    text: YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD AND THAT YOU ARE LEGALLY ABLE TO ENTER INTO THIS USER AGREEMENT.
    value: '18'
  restricted_uses:
  - summary: Unlawful or objectionable content
    text: You agree not to upload, download, display, perform, transmit, or otherwise distribute any content that (a) is libelous, defamatory, obscene, pornographic, abusive, or threatening
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
name: Ease
provenance_date: '2026-11-09'
provider_name: Ease
provider_slug: ease
slug: ease-eligibility
source_date: '2026-11-09'
source_filename: ease-eligibility.yml
source_heading: Eligibility
source_page: https://www.ease.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ease\naid: ease\nurl: https://www.ease.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: EASE offers its software services for a fee to brokers and some employers.\nrestricted_uses:\n- summary: Unlawful or objectionable content\n  text: You agree not to upload, download, display, perform, transmit, or otherwise distribute any content that\n    (a) is libelous, defamatory, obscene, pornographic, abusive, or threatening\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD AND THAT YOU ARE LEGALLY ABLE TO ENTER INTO THIS USER AGREEMENT.\n"
source_yaml_url: https://artifacts.apis.io/ease/eligibility/ease-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ease's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- United States
- Employee Benefits
- Benefits Administration
- Group Benefits
- Health Insurance
- Insurtech
- Brokerage
- Enrollment
- EDI
- Payroll
- Human Resources
- Marketplace
- Status
---
