---
api_specs:
- filename: commontape-com-book-api-openapi.yml
  format: yaml
  label: CommonTape Book API
  slug: commontape-com-book-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-book-api-openapi.yml
- filename: commontape-com-cancel-api-openapi.yml
  format: yaml
  label: CommonTape Cancel API
  slug: commontape-com-cancel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-cancel-api-openapi.yml
- filename: commontape-com-discover-api-openapi.yml
  format: yaml
  label: CommonTape Discover API
  slug: commontape-com-discover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-discover-api-openapi.yml
- filename: commontape-com-hold-api-openapi.yml
  format: yaml
  label: CommonTape Hold API
  slug: commontape-com-hold-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-hold-api-openapi.yml
- filename: commontape-com-keys-api-openapi.yml
  format: yaml
  label: CommonTape Keys API
  slug: commontape-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-keys-api-openapi.yml
- filename: commontape-com-modify-api-openapi.yml
  format: yaml
  label: CommonTape Modify API
  slug: commontape-com-modify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-modify-api-openapi.yml
- filename: commontape-com-quote-api-openapi.yml
  format: yaml
  label: CommonTape Quote API
  slug: commontape-com-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-quote-api-openapi.yml
- filename: commontape-com-search-api-openapi.yml
  format: yaml
  label: CommonTape Search API
  slug: commontape-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-search-api-openapi.yml
- filename: commontape-com-status-api-openapi.yml
  format: yaml
  label: CommonTape Status API
  slug: commontape-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-status-api-openapi.yml
- filename: commontape-com-taxonomy-api-openapi.yml
  format: yaml
  label: CommonTape Taxonomy API
  slug: commontape-com-taxonomy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commontape-com/openapi/commontape-com-taxonomy-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: CommonTape lets AI agents book jobs with US home-services businesses.
  entity_types:
  - text: Anyone who signs up a business must be allowed to act for it.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not a consumer app
    text: We serve AI agents acting on behalf of consumers; we are not a consumer app or a marketplace for people to browse.
  verification:
    approval_required: true
    kyb: true
    kyc: null
    text: We check each business before agents can book it, and we may decline or remove a listing.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CommonTape
provenance_date: '2026-11-09'
provider_name: CommonTape
provider_slug: commontape-com
slug: commontape-com-eligibility
source_date: '2026-11-09'
source_filename: commontape-com-eligibility.yml
source_heading: Eligibility
source_page: https://commontape.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CommonTape\naid: commontape-com\nurl: https://commontape.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: CommonTape lets AI agents book jobs with US home-services businesses.\nentity_types:\n- type: business\n  text: Anyone who signs up a business must be allowed to act for it.\nrestricted_uses:\n- summary: Not a consumer app\n  text: We serve AI agents acting on behalf of consumers; we are not a consumer app or a marketplace for people\n    to browse.\nverification:\n  kyc: null\n  kyb: true\n  approval_required: true\n  text: We check each business before agents\
  \ can book it, and we may decline or remove a listing.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/commontape-com/eligibility/commontape-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from CommonTape's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Booking
- Home Services
- House Cleaning
- MCP
- Marketplace
- Scheduling
---
