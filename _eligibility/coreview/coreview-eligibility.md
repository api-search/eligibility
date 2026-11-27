---
api_specs:
- filename: coreview-connect-api-openapi.yml
  format: yaml
  label: CoreView Connect API
  slug: coreview-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coreview/openapi/coreview-connect-api-openapi.yml
- filename: coreview-public-api-openapi.yml
  format: yaml
  label: CoreView Public API
  slug: coreview-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coreview/openapi/coreview-public-api-openapi.yml
- filename: coreview-teams-api-openapi.yml
  format: yaml
  label: CoreView Teams API
  slug: coreview-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coreview/openapi/coreview-teams-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Malicious activity
    text: You must not misuse our site by knowingly introducing viruses, trojans, worms, logic bombs or other material which is malicious or technologically harmful.
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
name: CoreView
provenance_date: '2026-11-09'
provider_name: CoreView
provider_slug: coreview
slug: coreview-eligibility
source_date: '2026-11-09'
source_filename: coreview-eligibility.yml
source_heading: Eligibility
source_page: https://www.coreview.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CoreView\naid: coreview\nurl: https://www.coreview.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Malicious activity\n  text: You must not misuse our site by knowingly introducing viruses, trojans, worms, logic bombs or other material\n    which is malicious or technologically harmful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coreview/eligibility/coreview-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from CoreView's own page on 2026-11-09.
synthetic: false
tags:
- Microsoft 365
- Tenant Resilience
- Configuration Management
- Identity Security
- License Optimization
- SharePoint Control
- Enterprise Saas
---
