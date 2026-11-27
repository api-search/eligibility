---
api_specs:
- filename: aptean-consumers-api-openapi.yml
  format: yaml
  label: Aptean Consumers API
  slug: aptean-consumers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptean/openapi/aptean-consumers-api-openapi.yml
- filename: aptean-events-api-openapi.yml
  format: yaml
  label: Aptean Events API
  slug: aptean-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptean/openapi/aptean-events-api-openapi.yml
- filename: aptean-producers-api-openapi.yml
  format: yaml
  label: Aptean Producers API
  slug: aptean-producers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptean/openapi/aptean-producers-api-openapi.yml
- filename: aptean-event-definitions-api-openapi.yml
  format: yaml
  label: Aptean Event Definitions API
  slug: aptean-event-definitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptean/openapi/aptean-event-definitions-api-openapi.yml
- filename: aptean-public-keys-api-openapi.yml
  format: yaml
  label: Aptean Public Keys API
  slug: aptean-public-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptean/openapi/aptean-public-keys-api-openapi.yml
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
  - summary: Comply with laws on data transmission
    text: you agree to comply with all laws and regulations from the country in which you reside (or from which you access or use aptean.com) governing the transmission of data on the Internet
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
name: Aptean
provenance_date: '2026-11-09'
provider_name: Aptean
provider_slug: aptean
slug: aptean-eligibility
source_date: '2026-11-09'
source_filename: aptean-eligibility.yml
source_heading: Eligibility
source_page: https://www.aptean.com/en-US/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aptean\naid: aptean\nurl: https://www.aptean.com/en-US/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Comply with laws on data transmission\n  text: you agree to comply with all laws and regulations from the country in which you reside (or from which you\n    access or use aptean.com) governing the transmission of data on the Internet\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aptean/eligibility/aptean-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Aptean's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Manufacturing
- ERP
- Supply Chain
- Integration
- Event-Driven
- Webhook
- Enterprise Software
---
