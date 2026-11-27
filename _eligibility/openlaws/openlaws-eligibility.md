---
api_specs:
- filename: openlaws-courts-api-openapi.yml
  format: yaml
  label: OpenLaws Courts API
  slug: openlaws-courts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openlaws/openapi/openlaws-courts-api-openapi.yml
- filename: openlaws-jurisdictions-api-openapi.yml
  format: yaml
  label: OpenLaws Jurisdictions API
  slug: openlaws-jurisdictions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openlaws/openapi/openlaws-jurisdictions-api-openapi.yml
- filename: openlaws-law-divisions-api-openapi.yml
  format: yaml
  label: OpenLaws Law Divisions API
  slug: openlaws-law-divisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openlaws/openapi/openlaws-law-divisions-api-openapi.yml
- filename: openlaws-laws-api-openapi.yml
  format: yaml
  label: OpenLaws Laws API
  slug: openlaws-laws-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openlaws/openapi/openlaws-laws-api-openapi.yml
- filename: openlaws-opinions-api-openapi.yml
  format: yaml
  label: OpenLaws Opinions API
  slug: openlaws-opinions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openlaws/openapi/openlaws-opinions-api-openapi.yml
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
  - summary: Financial services companies
    text: use the Services if Customer is a Financial Services Company
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
name: OpenLaws
provenance_date: '2026-11-10'
provider_name: OpenLaws
provider_slug: openlaws
slug: openlaws-eligibility
source_date: '2026-11-10'
source_filename: openlaws-eligibility.yml
source_heading: Eligibility
source_page: https://openlaws.us/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenLaws\naid: openlaws\nurl: https://openlaws.us/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Financial services companies\n  text: use the Services if Customer is a Financial Services Company\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/openlaws/eligibility/openlaws-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from OpenLaws's own page on 2026-11-10.
synthetic: false
tags:
- Legal
- Law
- Statutes
- Regulations
- Constitutions
- Case Law
- Citations
- Search
- RAG
- Legal Tech
- RegTech
- Compliance
- GRC
- Government Data
---
