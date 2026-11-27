---
api_specs:
- filename: looker-studio-assets-api-openapi.yml
  format: yaml
  label: Looker Studio Assets API
  slug: looker-studio-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/looker-studio/openapi/looker-studio-assets-api-openapi.yml
- filename: looker-studio-authentication-api-openapi.yml
  format: yaml
  label: Looker Studio Authentication API
  slug: looker-studio-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/looker-studio/openapi/looker-studio-authentication-api-openapi.yml
- filename: looker-studio-configuration-api-openapi.yml
  format: yaml
  label: Looker Studio Configuration API
  slug: looker-studio-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/looker-studio/openapi/looker-studio-configuration-api-openapi.yml
- filename: looker-studio-data-api-openapi.yml
  format: yaml
  label: Looker Studio Data API
  slug: looker-studio-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/looker-studio/openapi/looker-studio-data-api-openapi.yml
- filename: looker-studio-embed-api-openapi.yml
  format: yaml
  label: Looker Studio Embed API
  slug: looker-studio-embed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/looker-studio/openapi/looker-studio-embed-api-openapi.yml
- filename: looker-studio-manifest-api-openapi.yml
  format: yaml
  label: Looker Studio Manifest API
  slug: looker-studio-manifest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/looker-studio/openapi/looker-studio-manifest-api-openapi.yml
- filename: looker-studio-permissions-api-openapi.yml
  format: yaml
  label: Looker Studio Permissions API
  slug: looker-studio-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/looker-studio/openapi/looker-studio-permissions-api-openapi.yml
- filename: looker-studio-reports-api-openapi.yml
  format: yaml
  label: Looker Studio Reports API
  slug: looker-studio-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/looker-studio/openapi/looker-studio-reports-api-openapi.yml
- filename: looker-studio-schema-api-openapi.yml
  format: yaml
  label: Looker Studio Schema API
  slug: looker-studio-schema-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/looker-studio/openapi/looker-studio-schema-api-openapi.yml
- filename: looker-studio-visualization-api-openapi.yml
  format: yaml
  label: Looker Studio Visualization API
  slug: looker-studio-visualization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/looker-studio/openapi/looker-studio-visualization-api-openapi.yml
- filename: looker-studio-o-embed-api-openapi.yml
  format: yaml
  label: Looker Studio o Embed API
  slug: looker-studio-o-embed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/looker-studio/openapi/looker-studio-o-embed-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: But not all services mentioned may be available in your country.
  entity_types:
  - text: Many organizations , such as businesses, non-profits, and schools, take advantage of our services .
    type: business
  - text: If you meet these age requirements you can create a Google Account for your convenience.
    type: individual
  minimum_age:
    text: If you’re under the age required to manage your own Google Account , you must have your parent or legal guardian’s permission to use a Google Account.
    value: null
  restricted_uses:
  - summary: No reliance for professional advice
    text: DON’T RELY ON THE SERVICES FOR MEDICAL, LEGAL, FINANCIAL, OR OTHER PROFESSIONAL ADVICE.
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
name: Looker Studio
provenance_date: '2026-11-09'
provider_name: Looker Studio
provider_slug: looker-studio
slug: looker-studio-eligibility
source_date: '2026-11-09'
source_filename: looker-studio-eligibility.yml
source_heading: Eligibility
source_page: https://policies.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Looker Studio\naid: looker-studio\nurl: https://policies.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: But not all services mentioned may be available in your country.\nentity_types:\n- type: business\n  text: Many organizations , such as businesses, non-profits, and schools, take advantage of our services .\n- type: individual\n  text: If you meet these age requirements you can create a Google Account for your convenience.\nrestricted_uses:\n- summary: No reliance for professional advice\n  text: DON’T RELY ON THE SERVICES FOR MEDICAL, LEGAL, FINANCIAL, OR OTHER\
  \ PROFESSIONAL ADVICE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: If you’re under the age required to manage your own Google Account , you must have your parent or legal\n    guardian’s permission to use a Google Account.\n"
source_yaml_url: https://artifacts.apis.io/looker-studio/eligibility/looker-studio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Looker Studio's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Business Intelligence
- Dashboards
- Data Visualization
- Google
- Reports
---
