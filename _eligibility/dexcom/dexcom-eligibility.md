---
api_specs:
- filename: dexcom-alerts-api-openapi.yml
  format: yaml
  label: Dexcom Alerts API
  slug: dexcom-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexcom/openapi/dexcom-alerts-api-openapi.yml
- filename: dexcom-authentication-api-openapi.yml
  format: yaml
  label: Dexcom Authentication API
  slug: dexcom-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexcom/openapi/dexcom-authentication-api-openapi.yml
- filename: dexcom-calibrations-api-openapi.yml
  format: yaml
  label: Dexcom Calibrations API
  slug: dexcom-calibrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexcom/openapi/dexcom-calibrations-api-openapi.yml
- filename: dexcom-data-range-api-openapi.yml
  format: yaml
  label: Dexcom Data Range API
  slug: dexcom-data-range-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexcom/openapi/dexcom-data-range-api-openapi.yml
- filename: dexcom-devices-api-openapi.yml
  format: yaml
  label: Dexcom Devices API
  slug: dexcom-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexcom/openapi/dexcom-devices-api-openapi.yml
- filename: dexcom-estimated-glucose-values-api-openapi.yml
  format: yaml
  label: Dexcom Estimated Glucose Values API
  slug: dexcom-estimated-glucose-values-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexcom/openapi/dexcom-estimated-glucose-values-api-openapi.yml
- filename: dexcom-events-api-openapi.yml
  format: yaml
  label: Dexcom Events API
  slug: dexcom-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexcom/openapi/dexcom-events-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The DexCom Store may only be used by residents of those jurisdictions shown on the DexCom website. Anyone may use the DexCom Services, DexCom Products and Software Apps.
  entity_types:
  - text: By agreeing to this Agreement, you are representing that you of the age of majority of the country in which you reside and have the legal capacity to enter into this Agreement.
    type: individual
  minimum_age:
    text: you are representing that you of the age of majority of the country in which you reside
    value: age of majority
  restricted_uses:
  - summary: Export restrictions
    text: you represent, warrant and covenant that you are not (a) located in, or a resident or a national of, any country subject to a United States government embargo or other restriction
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
name: Dexcom
provenance_date: '2026-11-09'
provider_name: Dexcom
provider_slug: dexcom
slug: dexcom-eligibility
source_date: '2026-11-09'
source_filename: dexcom-eligibility.yml
source_heading: Eligibility
source_page: https://www.dexcom.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dexcom\naid: dexcom\nurl: https://www.dexcom.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The DexCom Store may only be used by residents of those jurisdictions shown on the DexCom website. Anyone\n    may use the DexCom Services, DexCom Products and Software Apps.\nentity_types:\n- type: individual\n  text: By agreeing to this Agreement, you are representing that you of the age of majority of the country in which\n    you reside and have the legal capacity to enter into this Agreement.\nrestricted_uses:\n- summary: Export restrictions\n\
  \  text: you represent, warrant and covenant that you are not (a) located in, or a resident or a national of, any\n    country subject to a United States government embargo or other restriction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you are representing that you of the age of majority of the country in which you reside\n"
source_yaml_url: https://artifacts.apis.io/dexcom/eligibility/dexcom-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Dexcom's own page on 2026-11-09.
synthetic: false
tags:
- Continuous Glucose Monitoring
- Diabetes
- Digital Health
- Glucose
- Healthcare
- Medical Devices
- Wearables
---
