---
api_specs:
- filename: monid-api-keys-api-openapi.yml
  format: yaml
  label: Monid API Keys API
  slug: monid-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-api-keys-api-openapi.yml
- filename: monid-auth-api-openapi.yml
  format: yaml
  label: Monid Auth API
  slug: monid-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-auth-api-openapi.yml
- filename: monid-controls-api-openapi.yml
  format: yaml
  label: Monid Controls API
  slug: monid-controls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-controls-api-openapi.yml
- filename: monid-discover-api-openapi.yml
  format: yaml
  label: Monid Discover API
  slug: monid-discover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-discover-api-openapi.yml
- filename: monid-endpoints-api-openapi.yml
  format: yaml
  label: Monid Endpoints API
  slug: monid-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-endpoints-api-openapi.yml
- filename: monid-inspect-api-openapi.yml
  format: yaml
  label: Monid Inspect API
  slug: monid-inspect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-inspect-api-openapi.yml
- filename: monid-public-registry-api-openapi.yml
  format: yaml
  label: Monid Public Registry API
  slug: monid-public-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-public-registry-api-openapi.yml
- filename: monid-resources-api-openapi.yml
  format: yaml
  label: Monid Resources API
  slug: monid-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-resources-api-openapi.yml
- filename: monid-runs-api-openapi.yml
  format: yaml
  label: Monid Runs API
  slug: monid-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-runs-api-openapi.yml
- filename: monid-wallet-api-openapi.yml
  format: yaml
  label: Monid Wallet API
  slug: monid-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-wallet-api-openapi.yml
- filename: monid-identities-api-openapi.yml
  format: yaml
  label: Monid Identities API
  slug: monid-identities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-identities-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: individual
  minimum_age:
    text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have the permission of, and be directly supervised by, their parent or guardian to use the Services.
    value: '18'
  restricted_uses:
  - summary: Industry-regulated data use
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  - summary: GLBA-regulated use
    text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
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
name: Monid
provenance_date: '2026-11-10'
provider_name: Monid
provider_slug: monid
slug: monid-eligibility
source_date: '2026-11-10'
source_filename: monid-eligibility.yml
source_heading: Eligibility
source_page: https://monid.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Monid\naid: monid\nurl: https://monid.ai/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n- summary: Industry-regulated data use\n  text: The Services are not tailored\
  \ to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\n- summary: GLBA-regulated use\n  text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have\n    the permission of, and be directly supervised by, their parent or guardian to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/monid/eligibility/monid-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Monid's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Agents
- MCP
- Tools
- Data
- API Marketplace
---
