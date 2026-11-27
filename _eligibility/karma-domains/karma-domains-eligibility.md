---
api_specs:
- filename: karma-domains-domains-api-openapi.yml
  format: yaml
  label: Karma.Domains Domains API
  slug: karma-domains-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karma-domains/openapi/karma-domains-domains-api-openapi.yml
- filename: karma-domains-reports-api-openapi.yml
  format: yaml
  label: Karma.Domains Reports API
  slug: karma-domains-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karma-domains/openapi/karma-domains-reports-api-openapi.yml
- filename: karma-domains-user-api-openapi.yml
  format: yaml
  label: Karma.Domains User API
  slug: karma-domains-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karma-domains/openapi/karma-domains-user-api-openapi.yml
- filename: karma-domains-webhooks-api-openapi.yml
  format: yaml
  label: Karma.Domains Webhooks API
  slug: karma-domains-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karma-domains/openapi/karma-domains-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Each natural person may maintain only one User account on the Service.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No account sale
    text: The User may not in any way sell or sell their personal account on the Karma.Domains Site to any third party.
  - summary: One account per person
    text: The User must not register more than once, create additional accounts for the same person
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
name: Karma.Domains
provenance_date: '2026-11-09'
provider_name: Karma.Domains
provider_slug: karma-domains
slug: karma-domains-eligibility
source_date: '2026-11-09'
source_filename: karma-domains-eligibility.yml
source_heading: Eligibility
source_page: https://karma.domains/legal/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Karma.Domains\naid: karma-domains\nurl: https://karma.domains/legal/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Each natural person may maintain only one User account on the Service.\nrestricted_uses:\n- summary: No account sale\n  text: The User may not in any way sell or sell their personal account on the Karma.Domains Site to any third party.\n- summary: One account per person\n  text: The User must not register more than once, create additional accounts for the same person\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/karma-domains/eligibility/karma-domains-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Karma.Domains's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SEO
- Domains
- Data
---
