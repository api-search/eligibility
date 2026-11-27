---
api_specs:
- filename: crowdwisdomtrading-account-api-openapi.yml
  format: yaml
  label: CrowdWisdom Signals API Account API
  slug: crowdwisdomtrading-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crowdwisdomtrading/openapi/crowdwisdomtrading-account-api-openapi.yml
- filename: crowdwisdomtrading-health-api-openapi.yml
  format: yaml
  label: CrowdWisdom Signals API Health API
  slug: crowdwisdomtrading-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crowdwisdomtrading/openapi/crowdwisdomtrading-health-api-openapi.yml
- filename: crowdwisdomtrading-signals-api-openapi.yml
  format: yaml
  label: CrowdWisdom Signals API Signals API
  slug: crowdwisdomtrading-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crowdwisdomtrading/openapi/crowdwisdomtrading-signals-api-openapi.yml
- filename: crowdwisdomtrading-socialmap-api-openapi.yml
  format: yaml
  label: CrowdWisdom Signals API Socialmap API
  slug: crowdwisdomtrading-socialmap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crowdwisdomtrading/openapi/crowdwisdomtrading-socialmap-api-openapi.yml
- filename: crowdwisdomtrading-socialmap-preview-api-openapi.yml
  format: yaml
  label: CrowdWisdom Signals API Socialmap Preview API
  slug: crowdwisdomtrading-socialmap-preview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crowdwisdomtrading/openapi/crowdwisdomtrading-socialmap-preview-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use the Services.
    value: '18'
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: You may not use or export the Services in violation of applicable export control or sanctions laws
  - summary: Securities or market-manipulation laws
    text: You agree not to use the Services in violation of applicable securities, commodities, or market-manipulation laws
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
name: CrowdWisdom Signals API
provenance_date: '2026-11-09'
provider_name: CrowdWisdom Signals API
provider_slug: crowdwisdomtrading
slug: crowdwisdomtrading-eligibility
source_date: '2026-11-09'
source_filename: crowdwisdomtrading-eligibility.yml
source_heading: Eligibility
source_page: https://www.crowdwisdomtrading.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CrowdWisdom Signals API\naid: crowdwisdomtrading\nurl: https://www.crowdwisdomtrading.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: You may not use or export the Services in violation of applicable export control or sanctions laws\n- summary: Securities or market-manipulation laws\n  text: You agree not to use the Services in violation of applicable securities, commodities, or market-manipulation\n    laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/crowdwisdomtrading/eligibility/crowdwisdomtrading-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CrowdWisdom Signals API's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Trading
- Signals
- B2B
---
