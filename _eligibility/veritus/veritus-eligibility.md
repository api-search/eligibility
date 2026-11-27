---
api_specs:
- filename: veritus-calls-api-openapi.yml
  format: yaml
  label: Veritus Calls API
  slug: veritus-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veritus/openapi/veritus-calls-api-openapi.yml
- filename: veritus-clients-api-openapi.yml
  format: yaml
  label: Veritus Clients API
  slug: veritus-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veritus/openapi/veritus-clients-api-openapi.yml
- filename: veritus-customers-api-openapi.yml
  format: yaml
  label: Veritus Customers API
  slug: veritus-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veritus/openapi/veritus-customers-api-openapi.yml
- filename: veritus-interactions-api-openapi.yml
  format: yaml
  label: Veritus Interactions API
  slug: veritus-interactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veritus/openapi/veritus-interactions-api-openapi.yml
- filename: veritus-veritus-api-api-openapi.yml
  format: yaml
  label: Veritus API
  slug: veritus-veritus-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veritus/openapi/veritus-veritus-api-api-openapi.yml
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
  - summary: Unlawful or harmful activity
    text: use the Platform to perform any activity which does or may violate any applicable law or regulation, or that is or may be, directly or indirectly, harmful, threatening, abusive, harassing, tortious or defamatory
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
name: Veritus
provenance_date: '2026-11-10'
provider_name: Veritus
provider_slug: veritus
slug: veritus-eligibility
source_date: '2026-11-10'
source_filename: veritus-eligibility.yml
source_heading: Eligibility
source_page: https://veritus.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Veritus\naid: veritus\nurl: https://veritus.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful activity\n  text: use the Platform to perform any activity which does or may violate any applicable law or regulation, or\n    that is or may be, directly or indirectly, harmful, threatening, abusive, harassing, tortious or defamatory\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/veritus/eligibility/veritus-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Veritus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Consumer Lending
- Collection
- AI Agents
- Voice AI
- Communications
- Compliance
- Debt Collection
---
