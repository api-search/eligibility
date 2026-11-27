---
api_specs:
- filename: okteto-applications-api-openapi.yml
  format: yaml
  label: Okteto Applications API
  slug: okteto-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/okteto/openapi/okteto-applications-api-openapi.yml
- filename: okteto-namespaces-api-openapi.yml
  format: yaml
  label: Okteto Namespaces API
  slug: okteto-namespaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/okteto/openapi/okteto-namespaces-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Access to and use of our Services is only for those over the age of 13 (or 16 in the European Union).
    value: '13'
  restricted_uses:
  - summary: Gambling
    text: Gambling.
  - summary: Bots on messaging platforms
    text: Use our Services to run Telegram and WhatsApp bots or similar services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Use of our Services requires an Okteto.com account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Okteto
provenance_date: '2026-11-10'
provider_name: Okteto
provider_slug: okteto
slug: okteto-eligibility
source_date: '2026-11-10'
source_filename: okteto-eligibility.yml
source_heading: Eligibility
source_page: https://www.okteto.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Okteto\naid: okteto\nurl: https://www.okteto.com/legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Gambling\n  text: Gambling.\n- summary: Bots on messaging platforms\n  text: Use our Services to run Telegram and WhatsApp bots or similar services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Use of our Services requires an Okteto.com account.\nminimum_age:\n  value: '13'\n  text: Access to and use of our Services is only for those over the age of 13 (or 16 in the European Union).\n"
source_yaml_url: https://artifacts.apis.io/okteto/eligibility/okteto-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Okteto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Kubernetes
- Developer Environments
- Cloud-Native
- Developer Tools
- Preview Environments
- AI Agents
- CLI
---
