---
api_specs:
- filename: apixstar-com-openapi-generated.yml
  format: yaml
  label: apixstar-com API
  slug: apixstar-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apixstar-com/openapi/_ae-authored/apixstar-com-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to enter a binding contract.
    type: individual
  - text: If you use the Service for a company, you confirm that you can bind that company, and "you" means that company.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to enter a binding contract.
    value: '18'
  restricted_uses:
  - summary: Sanctions or export law
    text: You may not use the Service where doing so is prohibited by sanctions or export laws that apply to you or to us.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with a Google account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: apixstar-com
provenance_date: '2026-11-09'
provider_name: apixstar-com
provider_slug: apixstar-com
slug: apixstar-com-eligibility
source_date: '2026-11-09'
source_filename: apixstar-com-eligibility.yml
source_heading: Eligibility
source_page: https://apixstar.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: apixstar-com\naid: apixstar-com\nurl: https://apixstar.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter a binding contract.\n- type: business\n  text: If you use the Service for a company, you confirm that you can bind that company, and \"you\" means that company.\nrestricted_uses:\n- summary: Sanctions or export law\n  text: You may not use the Service where doing so is prohibited by sanctions or export laws that apply to you or\n    to us.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: You sign in with a Google account.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/apixstar-com/eligibility/apixstar-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from apixstar-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Reddit
- Data
- Developers
- Analytics
---
