---
api_specs:
- filename: microsoft-package-packagecontent-api-openapi.yml
  format: yaml
  label: Microsoft Package PackageContent API
  slug: microsoft-package-packagecontent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-package/openapi/microsoft-package-packagecontent-api-openapi.yml
- filename: microsoft-package-registration-api-openapi.yml
  format: yaml
  label: Microsoft Package Registration API
  slug: microsoft-package-registration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-package/openapi/microsoft-package-registration-api-openapi.yml
- filename: microsoft-package-search-api-openapi.yml
  format: yaml
  label: Microsoft Package Search API
  slug: microsoft-package-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-package/openapi/microsoft-package-search-api-openapi.yml
- filename: microsoft-package-service-index-api-openapi.yml
  format: yaml
  label: Microsoft Package Service Index API
  slug: microsoft-package-service-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-package/openapi/microsoft-package-service-index-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Unless otherwise specified, the Services are for your personal and non-commercial use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: As a condition of your use of the Services, you will not use the Services for any purpose that is unlawful or prohibited by these terms, conditions, and notices.
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
name: Microsoft Package
provenance_date: '2026-11-10'
provider_name: Microsoft Package
provider_slug: microsoft-package
slug: microsoft-package-eligibility
source_date: '2026-11-10'
source_filename: microsoft-package-eligibility.yml
source_heading: Eligibility
source_page: https://www.microsoft.com/en-us/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Microsoft Package\naid: microsoft-package\nurl: https://www.microsoft.com/en-us/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Unless otherwise specified, the Services are for your personal and non-commercial use.\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: As a condition of your use of the Services, you will not use the Services for any purpose that is unlawful\n    or prohibited by these terms, conditions, and notices.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/microsoft-package/eligibility/microsoft-package-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Microsoft Package's own page on 2026-11-10.
synthetic: false
tags:
- Azure Artifacts
- Developer Tools
- Microsoft
- NuGet
- Package Management
- WinGet
---
