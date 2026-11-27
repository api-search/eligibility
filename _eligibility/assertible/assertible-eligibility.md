---
api_specs:
- filename: assertible-triggers-api-openapi.yml
  format: yaml
  label: Assertible API
  slug: assertible-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assertible/openapi/assertible-triggers-api-openapi.yml
- filename: assertible-deployments-api-openapi.yml
  format: yaml
  label: Assertible Deployments API
  slug: assertible-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assertible/openapi/assertible-deployments-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be thirteen years of age or older to use it.
    value: '13'
  restricted_uses:
  - summary: Threats, harassment, spam, and illegal content
    text: Threaten other users with violence.
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
name: Assertible
provenance_date: '2026-11-09'
provider_name: Assertible
provider_slug: assertible
slug: assertible-eligibility
source_date: '2026-11-09'
source_filename: assertible-eligibility.yml
source_heading: Eligibility
source_page: https://assertible.com/termsofservice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Assertible\naid: assertible\nurl: https://assertible.com/termsofservice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Threats, harassment, spam, and illegal content\n  text: Threaten other users with violence.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be thirteen years of age or older to use it.\n"
source_yaml_url: https://artifacts.apis.io/assertible/eligibility/assertible-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Assertible's own page on 2026-11-09.
synthetic: false
tags:
- API Testing
- Monitoring
- Quality Assurance
- Testing
- CI/CD
- Developer Tools
---
