---
api_specs:
- filename: etherfax-accounts-api-openapi.yml
  format: yaml
  label: etherFAX Accounts API
  slug: etherfax-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/etherfax/openapi/etherfax-accounts-api-openapi.yml
- filename: etherfax-devices-api-openapi.yml
  format: yaml
  label: etherFAX Devices API
  slug: etherfax-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/etherfax/openapi/etherfax-devices-api-openapi.yml
- filename: etherfax-inbox-api-openapi.yml
  format: yaml
  label: etherFAX Inbox API
  slug: etherfax-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/etherfax/openapi/etherfax-inbox-api-openapi.yml
- filename: etherfax-outbox-api-openapi.yml
  format: yaml
  label: etherFAX Outbox API
  slug: etherfax-outbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/etherfax/openapi/etherfax-outbox-api-openapi.yml
- filename: etherfax-routes-api-openapi.yml
  format: yaml
  label: etherFAX Routes API
  slug: etherfax-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/etherfax/openapi/etherfax-routes-api-openapi.yml
- filename: etherfax-status-api-openapi.yml
  format: yaml
  label: etherFAX Status API
  slug: etherfax-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/etherfax/openapi/etherfax-status-api-openapi.yml
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
  - summary: Unsolicited fax advertising and unlawful use
    text: comply with FCC Regulations regarding unsolicited fax transmissions
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
name: etherFAX
provenance_date: '2026-11-09'
provider_name: etherFAX
provider_slug: etherfax
slug: etherfax-eligibility
source_date: '2026-11-09'
source_filename: etherfax-eligibility.yml
source_heading: Eligibility
source_page: https://www.etherfax.net/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: etherFAX\naid: etherfax\nurl: https://www.etherfax.net/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unsolicited fax advertising and unlawful use\n  text: comply with FCC Regulations regarding unsolicited fax transmissions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/etherfax/eligibility/etherfax-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from etherFAX's own page on 2026-11-09.
synthetic: false
tags:
- Fax
- Cloud
- Artificial Intelligence
- Secure
- Document Automation
---
