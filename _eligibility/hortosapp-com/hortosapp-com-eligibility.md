---
api_specs:
- filename: hortosapp-com-quote-api-openapi.yml
  format: yaml
  label: hortosapp-com Quote API
  slug: hortosapp-com-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hortosapp-com/openapi/hortosapp-com-quote-api-openapi.yml
- filename: hortosapp-com-search-api-openapi.yml
  format: yaml
  label: hortosapp-com Search API
  slug: hortosapp-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hortosapp-com/openapi/hortosapp-com-search-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: the United States service is provided to trade businesses on that basis.
  entity_types:
  - text: A business identifier (EIN or state registration) is required to place orders or claim a grower profile
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not open to general public
    text: It is not a retail store and is not open to the general public.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A business identifier (EIN or state registration) is required to place orders or claim a grower profile, and it is shown to the growers you order from.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: hortosapp-com
provenance_date: '2026-11-09'
provider_name: hortosapp-com
provider_slug: hortosapp-com
slug: hortosapp-com-eligibility
source_date: '2026-11-09'
source_filename: hortosapp-com-eligibility.yml
source_heading: Eligibility
source_page: https://us.hortosapp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: hortosapp-com\naid: hortosapp-com\nurl: https://us.hortosapp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: the United States service is provided to trade businesses on that basis.\nentity_types:\n- type: business\n  text: A business identifier (EIN or state registration) is required to place orders or claim a grower profile\nrestricted_uses:\n- summary: Not open to general public\n  text: It is not a retail store and is not open to the general public.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A business identifier (EIN or state\
  \ registration) is required to place orders or claim a grower profile,\n    and it is shown to the growers you order from.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hortosapp-com/eligibility/hortosapp-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from hortosapp-com's own page on 2026-11-09.
synthetic: false
tags:
- Agriculture
- Horticulture
- Marketplace
- Wholesale
- PlantData
---
