---
api_specs:
- filename: symphonyos-openapi-generated.yml
  format: yaml
  label: SymphonyOS API
  slug: symphonyos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/symphonyos/openapi/_ae-authored/symphonyos-openapi-generated.yml
- filename: symphonyos-campaigns-api-openapi.yml
  format: yaml
  label: SymphonyOS Campaigns API
  slug: symphonyos-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/symphonyos/openapi/symphonyos-campaigns-api-openapi.yml
- filename: symphonyos-sym-api-openapi.yml
  format: yaml
  label: SymphonyOS Sym API
  slug: symphonyos-sym-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/symphonyos/openapi/symphonyos-sym-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years of age to access or use our Services.
    type: individual
  - text: If you are accessing or using our Services on behalf of another person or entity, you represent that you are authorized to accept these Terms on that person or entity’s behalf
    type: business
  minimum_age:
    text: You must be at least 16 years of age to access or use our Services.
    value: '16'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: Use our Services for any illegal or unauthorized purpose
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
name: SymphonyOS
provenance_date: '2026-11-10'
provider_name: SymphonyOS
provider_slug: symphonyos
slug: symphonyos-eligibility
source_date: '2026-11-10'
source_filename: symphonyos-eligibility.yml
source_heading: Eligibility
source_page: https://symphonyos.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SymphonyOS\naid: symphonyos\nurl: https://symphonyos.co/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years of age to access or use our Services.\n- type: business\n  text: If you are accessing or using our Services on behalf of another person or entity, you represent that you\n    are authorized to accept these Terms on that person or entity’s behalf\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: Use our Services for any illegal or unauthorized purpose\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years of age to access or use our Services.\n"
source_yaml_url: https://artifacts.apis.io/symphonyos/eligibility/symphonyos-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from SymphonyOS's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Music
- Platform
- Agents
---
