---
api_specs:
- filename: openmenu-analytics-api-openapi.yml
  format: yaml
  label: OpenMenu Analytics API
  slug: openmenu-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmenu/openapi/openmenu-analytics-api-openapi.yml
- filename: openmenu-deals-api-openapi.yml
  format: yaml
  label: OpenMenu Deals API
  slug: openmenu-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmenu/openapi/openmenu-deals-api-openapi.yml
- filename: openmenu-ingredients-api-openapi.yml
  format: yaml
  label: OpenMenu Ingredients API
  slug: openmenu-ingredients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmenu/openapi/openmenu-ingredients-api-openapi.yml
- filename: openmenu-restaurants-api-openapi.yml
  format: yaml
  label: OpenMenu Restaurants API
  slug: openmenu-restaurants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmenu/openapi/openmenu-restaurants-api-openapi.yml
- filename: openmenu-search-api-openapi.yml
  format: yaml
  label: OpenMenu Search API
  slug: openmenu-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openmenu/openapi/openmenu-search-api-openapi.yml
claim_count: 2
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
  - summary: Use of OpenMenu trademark
    text: have an application which uses the OpenMenu trademark or infringes on any/all OpenMenu trademarks. Use of the word/phrase/term OpenMenu is prohibited;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to access the API you must create an OpenMenu Account and apply for a developers key ("Key")
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: OpenMenu
provenance_date: '2026-11-10'
provider_name: OpenMenu
provider_slug: openmenu
slug: openmenu-eligibility
source_date: '2026-11-10'
source_filename: openmenu-eligibility.yml
source_heading: Eligibility
source_page: https://www.openmenu.com/tos-api.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenMenu\naid: openmenu\nurl: https://www.openmenu.com/tos-api.php\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Use of OpenMenu trademark\n  text: have an application which uses the OpenMenu trademark or infringes on any/all OpenMenu trademarks. Use of\n    the word/phrase/term OpenMenu is prohibited;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to access the API you must create an OpenMenu Account and apply for a developers key (\"Key\")\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/openmenu/eligibility/openmenu-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from OpenMenu's own page on 2026-11-10.
synthetic: false
tags:
- Restaurant
- Menus
- Menu Data
- Search
- Nutrition
- Structured Data
---
