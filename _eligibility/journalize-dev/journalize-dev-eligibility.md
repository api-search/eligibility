---
api_specs:
- filename: journalize-dev-accounts-api-openapi.yml
  format: yaml
  label: journalize-dev Accounts API
  slug: journalize-dev-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-accounts-api-openapi.yml
- filename: journalize-dev-export-api-openapi.yml
  format: yaml
  label: journalize-dev Export API
  slug: journalize-dev-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-export-api-openapi.yml
- filename: journalize-dev-health-api-openapi.yml
  format: yaml
  label: journalize-dev Health API
  slug: journalize-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-health-api-openapi.yml
- filename: journalize-dev-journal-api-openapi.yml
  format: yaml
  label: journalize-dev Journal API
  slug: journalize-dev-journal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-journal-api-openapi.yml
- filename: journalize-dev-journalize-api-openapi.yml
  format: yaml
  label: journalize-dev Journalize API
  slug: journalize-dev-journalize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-journalize-api-openapi.yml
- filename: journalize-dev-llms-txt-api-openapi.yml
  format: yaml
  label: journalize-dev Llms.txt API
  slug: journalize-dev-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-llms-txt-api-openapi.yml
- filename: journalize-dev-privacy-api-openapi.yml
  format: yaml
  label: journalize-dev Privacy API
  slug: journalize-dev-privacy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-privacy-api-openapi.yml
- filename: journalize-dev-register-api-openapi.yml
  format: yaml
  label: journalize-dev Register API
  slug: journalize-dev-register-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-register-api-openapi.yml
- filename: journalize-dev-reports-api-openapi.yml
  format: yaml
  label: journalize-dev Reports API
  slug: journalize-dev-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-reports-api-openapi.yml
- filename: journalize-dev-robots-txt-api-openapi.yml
  format: yaml
  label: journalize-dev Robots.txt API
  slug: journalize-dev-robots-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-robots-txt-api-openapi.yml
- filename: journalize-dev-security-txt-api-openapi.yml
  format: yaml
  label: journalize-dev Security.txt API
  slug: journalize-dev-security-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-security-txt-api-openapi.yml
- filename: journalize-dev-skill-md-api-openapi.yml
  format: yaml
  label: journalize-dev SKILL.md API
  slug: journalize-dev-skill-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-skill-md-api-openapi.yml
- filename: journalize-dev-terms-api-openapi.yml
  format: yaml
  label: journalize-dev Terms API
  slug: journalize-dev-terms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-terms-api-openapi.yml
- filename: journalize-dev-well-known-api-openapi.yml
  format: yaml
  label: journalize-dev .well Known API
  slug: journalize-dev-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-well-known-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you ("you", the calling agent or its operator)
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraudulent or deceptive bookkeeping
    text: Use the Service to create or maintain records intended to deceive a third party (e.g. fraudulent bookkeeping for regulatory or tax evasion purposes).
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
name: journalize-dev
provenance_date: '2026-11-09'
provider_name: journalize-dev
provider_slug: journalize-dev
slug: journalize-dev-eligibility
source_date: '2026-11-09'
source_filename: journalize-dev-eligibility.yml
source_heading: Eligibility
source_page: https://journalize.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: journalize-dev\naid: journalize-dev\nurl: https://journalize.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: you (\"you\", the calling agent or its operator)\nrestricted_uses:\n- summary: Fraudulent or deceptive bookkeeping\n  text: Use the Service to create or maintain records intended to deceive a third party (e.g. fraudulent bookkeeping\n    for regulatory or tax evasion purposes).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/journalize-dev/eligibility/journalize-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from journalize-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Accounting
- Artificial Intelligence
- Fintech
- Ledger
---
