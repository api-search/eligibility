---
api_specs:
- filename: workera-audit-events-api-openapi.yml
  format: yaml
  label: Workera Audit Events API
  slug: workera-audit-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workera/openapi/workera-audit-events-api-openapi.yml
- filename: workera-benchmarks-api-openapi.yml
  format: yaml
  label: Workera Benchmarks API
  slug: workera-benchmarks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workera/openapi/workera-benchmarks-api-openapi.yml
- filename: workera-capability-api-openapi.yml
  format: yaml
  label: Workera Capability API
  slug: workera-capability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workera/openapi/workera-capability-api-openapi.yml
- filename: workera-domains-api-openapi.yml
  format: yaml
  label: Workera Domains API
  slug: workera-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workera/openapi/workera-domains-api-openapi.yml
- filename: workera-ping-api-openapi.yml
  format: yaml
  label: Workera Ping API
  slug: workera-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workera/openapi/workera-ping-api-openapi.yml
- filename: workera-programs-api-openapi.yml
  format: yaml
  label: Workera Programs API
  slug: workera-programs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workera/openapi/workera-programs-api-openapi.yml
- filename: workera-scores-api-openapi.yml
  format: yaml
  label: Workera Scores API
  slug: workera-scores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workera/openapi/workera-scores-api-openapi.yml
- filename: workera-self-ratings-api-openapi.yml
  format: yaml
  label: Workera Self Ratings API
  slug: workera-self-ratings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workera/openapi/workera-self-ratings-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services may not be appropriate or available for use in some non-U.S. jurisdictions. You represent you are not located in a country embargoed by the United States or subject to U.S. sanctions.
  entity_types:
  - text: If you’re accessing the Services as an authorized user of or on behalf of a Workera business customer (“Customer”), including in connection with a Workera Enterprise subscription purchased by your employer, you shall be referred to as a “Workera Enterprise User”.
    type: business
  minimum_age:
    text: you are at least eighteen (18) years of age and have the right, authority, and capacity to enter into these Terms
    value: '18'
  restricted_uses:
  - summary: Minors under thirteen
    text: In any manner that may harm minors or that interacts with or targets people under the age of thirteen.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require you to provide information that may be used to confirm your identity and help ensure the security of your account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Workera
provenance_date: '2026-11-10'
provider_name: Workera
provider_slug: workera
slug: workera-eligibility
source_date: '2026-11-10'
source_filename: workera-eligibility.yml
source_heading: Eligibility
source_page: https://www.workera.ai/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Workera\naid: workera\nurl: https://www.workera.ai/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services may not be appropriate or available for use in some non-U.S. jurisdictions. You represent you\n    are not located in a country embargoed by the United States or subject to U.S. sanctions.\nentity_types:\n- type: business\n  text: If you’re accessing the Services as an authorized user of or on behalf of a Workera business customer (“Customer”),\n    including in connection with a Workera Enterprise subscription purchased by your employer, you shall be\
  \ referred\n    to as a “Workera Enterprise User”.\nrestricted_uses:\n- summary: Minors under thirteen\n  text: In any manner that may harm minors or that interacts with or targets people under the age of thirteen.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require you to provide information that may be used to confirm your identity and help ensure the\n    security of your account.\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years of age and have the right, authority, and capacity to enter into these\n    Terms\n"
source_yaml_url: https://artifacts.apis.io/workera/eligibility/workera-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Workera's own page on 2026-11-10.
synthetic: false
tags:
- Skills Intelligence
- Skills Assessment
- Human Resources
- Learning and Development
- Talent Management
- Workforce Analytics
- Artificial Intelligence
- Benchmarking
- Enterprise Software
- MCP
- Company
---
