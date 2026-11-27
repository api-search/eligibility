---
api_specs:
- filename: cite42-dev-openapi-generated.yml
  format: yaml
  label: cite42-dev API
  slug: cite42-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cite42-dev/openapi/_ae-authored/cite42-dev-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, and you are not a national or resident of, a country subject to comprehensive UK, EU, or U.S. sanctions
  entity_types:
  - text: If you are using the Service on behalf of a company or other legal entity, you represent that you are authorized to bind that entity to these Terms
    type: business
  minimum_age:
    text: You must be at least 16 years old.
    value: '16'
  restricted_uses:
  - summary: No profiling of private individuals
    text: You must not use the Service to systematically query AI models about identifiable private individuals in their private capacity for the purpose of profiling, reputation analysis, harassment, doxxing, background checks
  - summary: No impersonation
    text: You must not use the Service to impersonate any person or entity
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may refuse registration or suspend, downgrade, or terminate accounts at our discretion
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: cite42-dev
provenance_date: '2026-11-09'
provider_name: cite42-dev
provider_slug: cite42-dev
slug: cite42-dev-eligibility
source_date: '2026-11-09'
source_filename: cite42-dev-eligibility.yml
source_heading: Eligibility
source_page: https://www.cite42.dev/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: cite42-dev\naid: cite42-dev\nurl: https://www.cite42.dev/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, and you are not a national or resident of, a country subject\n    to comprehensive UK, EU, or U.S. sanctions\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of a company or other legal entity, you represent that you are authorized\n    to bind that entity to these Terms\nrestricted_uses:\n- summary: No profiling of private individuals\n  text: You must not use the Service to systematically\
  \ query AI models about identifiable private individuals in\n    their private capacity for the purpose of profiling, reputation analysis, harassment, doxxing, background checks\n- summary: No impersonation\n  text: You must not use the Service to impersonate any person or entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may refuse registration or suspend, downgrade, or terminate accounts at our discretion\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/cite42-dev/eligibility/cite42-dev-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from cite42-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- SEO
- MCP
- Data
- Visibility
---
