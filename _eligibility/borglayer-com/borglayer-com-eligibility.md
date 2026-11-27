---
api_specs:
- filename: borglayer-com-balance-api-openapi.yml
  format: yaml
  label: BorgLayer Balance API
  slug: borglayer-com-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-balance-api-openapi.yml
- filename: borglayer-com-chains-api-openapi.yml
  format: yaml
  label: BorgLayer Chains API
  slug: borglayer-com-chains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-chains-api-openapi.yml
- filename: borglayer-com-domains-api-openapi.yml
  format: yaml
  label: BorgLayer Domains API
  slug: borglayer-com-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-domains-api-openapi.yml
- filename: borglayer-com-formation-api-openapi.yml
  format: yaml
  label: BorgLayer Formation API
  slug: borglayer-com-formation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-formation-api-openapi.yml
- filename: borglayer-com-marketplace-api-openapi.yml
  format: yaml
  label: BorgLayer Marketplace API
  slug: borglayer-com-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-marketplace-api-openapi.yml
- filename: borglayer-com-register-api-openapi.yml
  format: yaml
  label: BorgLayer Register API
  slug: borglayer-com-register-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-register-api-openapi.yml
- filename: borglayer-com-registrant-profiles-api-openapi.yml
  format: yaml
  label: BorgLayer Registrant Profiles API
  slug: borglayer-com-registrant-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-registrant-profiles-api-openapi.yml
- filename: borglayer-com-search-api-openapi.yml
  format: yaml
  label: BorgLayer Search API
  slug: borglayer-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-search-api-openapi.yml
- filename: borglayer-com-transfer-in-api-openapi.yml
  format: yaml
  label: BorgLayer Transfer In API
  slug: borglayer-com-transfer-in-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/borglayer-com/openapi/borglayer-com-transfer-in-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be able to form a binding contract to use the Service.
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or fraudulent domain use
    text: Customers must not register, acquire, use, sell, transfer, or maintain a domain for unlawful purposes or for activities involving fraud, phishing, malware, impersonation, scams, cybersquatting, or trademark or intellectual-property infringement
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Registration requirements vary by TLD.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BorgLayer
provenance_date: '2026-11-09'
provider_name: BorgLayer
provider_slug: borglayer-com
slug: borglayer-com-eligibility
source_date: '2026-11-09'
source_filename: borglayer-com-eligibility.yml
source_heading: Eligibility
source_page: https://borglayer.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BorgLayer\naid: borglayer-com\nurl: https://borglayer.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: You must be able to form a binding contract to use the Service.\nrestricted_uses:\n- summary: Unlawful or fraudulent domain use\n  text: Customers must not register, acquire, use, sell, transfer, or maintain a domain for unlawful purposes or\n    for activities involving fraud, phishing, malware, impersonation, scams, cybersquatting, or trademark or intellectual-property\n    infringement\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: Registration requirements vary by TLD.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/borglayer-com/eligibility/borglayer-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from BorgLayer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wallets
- Domains
- Hosting
- Email
---
