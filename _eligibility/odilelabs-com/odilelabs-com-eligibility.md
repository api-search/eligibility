---
api_specs:
- filename: odilelabs-com-account-api-openapi.yml
  format: yaml
  label: odilelabs-com Account API
  slug: odilelabs-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odilelabs-com/openapi/odilelabs-com-account-api-openapi.yml
- filename: odilelabs-com-lines-api-openapi.yml
  format: yaml
  label: odilelabs-com Lines API
  slug: odilelabs-com-lines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/odilelabs-com/openapi/odilelabs-com-lines-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Odile Labs runs worldwide.
  entity_types:
  - text: Use the products for a real business you are entitled to represent.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unsolicited calls, impersonation, unlawful use
    text: Do not use them to make unsolicited calls, to impersonate anyone, or for anything unlawful.
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
name: odilelabs-com
provenance_date: '2026-11-10'
provider_name: odilelabs-com
provider_slug: odilelabs-com
slug: odilelabs-com-eligibility
source_date: '2026-11-10'
source_filename: odilelabs-com-eligibility.yml
source_heading: Eligibility
source_page: https://odilelabs.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: odilelabs-com\naid: odilelabs-com\nurl: https://odilelabs.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Odile Labs runs worldwide.\nentity_types:\n- type: business\n  text: Use the products for a real business you are entitled to represent.\nrestricted_uses:\n- summary: Unsolicited calls, impersonation, unlawful use\n  text: Do not use them to make unsolicited calls, to impersonate anyone, or for anything unlawful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/odilelabs-com/eligibility/odilelabs-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from odilelabs-com's own page on 2026-11-10.
synthetic: false
tags:
- Communication Infrastructure
- AI Receptionist
- Phone Answering
- Developer API
---
