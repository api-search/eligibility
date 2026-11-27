---
api_specs:
- filename: eia-aeo-api-openapi.yml
  format: yaml
  label: EIA AEO API
  slug: eia-aeo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-aeo-api-openapi.yml
- filename: eia-coal-api-openapi.yml
  format: yaml
  label: EIA COAL API
  slug: eia-coal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-coal-api-openapi.yml
- filename: eia-crud-imports-api-openapi.yml
  format: yaml
  label: EIA CRUD IMPORTS API
  slug: eia-crud-imports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-crud-imports-api-openapi.yml
- filename: eia-dbf-api-openapi.yml
  format: yaml
  label: EIA DBF API
  slug: eia-dbf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-dbf-api-openapi.yml
- filename: eia-elec-api-openapi.yml
  format: yaml
  label: EIA ELEC API
  slug: eia-elec-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-elec-api-openapi.yml
- filename: eia-emiss-api-openapi.yml
  format: yaml
  label: EIA EMISS API
  slug: eia-emiss-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-emiss-api-openapi.yml
- filename: eia-ieo-api-openapi.yml
  format: yaml
  label: EIA IEO API
  slug: eia-ieo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-ieo-api-openapi.yml
- filename: eia-intl-api-openapi.yml
  format: yaml
  label: EIA INTL API
  slug: eia-intl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-intl-api-openapi.yml
- filename: eia-ng-api-openapi.yml
  format: yaml
  label: EIA NG API
  slug: eia-ng-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-ng-api-openapi.yml
- filename: eia-nuc-status-api-openapi.yml
  format: yaml
  label: EIA NUC STATUS API
  slug: eia-nuc-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-nuc-status-api-openapi.yml
- filename: eia-root-api-openapi.yml
  format: yaml
  label: EIA Root API
  slug: eia-root-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-root-api-openapi.yml
- filename: eia-rto-api-openapi.yml
  format: yaml
  label: EIA RTO API
  slug: eia-rto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-rto-api-openapi.yml
- filename: eia-seds-api-openapi.yml
  format: yaml
  label: EIA SEDS API
  slug: eia-seds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-seds-api-openapi.yml
- filename: eia-sep-api-openapi.yml
  format: yaml
  label: EIA SEP API
  slug: eia-sep-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-sep-api-openapi.yml
- filename: eia-steo-api-openapi.yml
  format: yaml
  label: EIA STEO API
  slug: eia-steo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-steo-api-openapi.yml
- filename: eia-total-api-openapi.yml
  format: yaml
  label: EIA TOTAL API
  slug: eia-total-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eia/openapi/eia-total-api-openapi.yml
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
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Users of the EIA API are required to obtain an key. Your API key will be sent to your email address as well as any required API notifications.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: EIA
provenance_date: '2026-11-09'
provider_name: EIA
provider_slug: eia
slug: eia-eligibility
source_date: '2026-11-09'
source_filename: eia-eligibility.yml
source_heading: Eligibility
source_page: https://www.eia.gov/opendata/register.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EIA\naid: eia\nurl: https://www.eia.gov/opendata/register.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Users of the EIA API are required to obtain an key. Your API key will be sent to your email address as well\n    as any required API notifications.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eia/eligibility/eia-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from EIA's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- United States
- Energy Markets
- Electricity
- Natural Gas
- Petroleum
- Coal
- Nuclear
- Renewables
- Grid
- Emissions
- Government
- Open Data
- Energy Statistics
---
