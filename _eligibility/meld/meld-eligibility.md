---
api_specs:
- filename: meld-headless-api-openapi.yml
  format: yaml
  label: Meld.io Headless API
  slug: meld-headless-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meld/openapi/meld-headless-api-openapi.yml
- filename: meld-retail-ramp-api-openapi.yml
  format: yaml
  label: Meld.io Retail Ramp API
  slug: meld-retail-ramp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meld/openapi/meld-retail-ramp-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: WHEN AN INDIVIDUAL ACCEPTS THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, SUCH INDIVIDUAL REPRESENTS THAT THEY HAVE THE AUTHORITY TO BIND SUCH COMPANY OR LEGAL ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or infringing use
    text: use the Meld IP in any manner or for any purpose that infringes, misappropriates, or otherwise violates any intellectual property right or other right of any person, or that violates any applicable law
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
name: Meld.io
provenance_date: '2026-11-10'
provider_name: Meld.io
provider_slug: meld
slug: meld-eligibility
source_date: '2026-11-10'
source_filename: meld-eligibility.yml
source_heading: Eligibility
source_page: https://www.meld.io/policy/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Meld.io\naid: meld\nurl: https://www.meld.io/policy/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: WHEN AN INDIVIDUAL ACCEPTS THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, SUCH INDIVIDUAL\n    REPRESENTS THAT THEY HAVE THE AUTHORITY TO BIND SUCH COMPANY OR LEGAL ENTITY\nrestricted_uses:\n- summary: Unlawful or infringing use\n  text: use the Meld IP in any manner or for any purpose that infringes, misappropriates, or otherwise violates\n    any intellectual property right or other right of any person,\
  \ or that violates any applicable law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/meld/eligibility/meld-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Meld.io's own page on 2026-11-10.
synthetic: false
tags:
- Data Integration
- Fintech
- API Platform
- Stablecoins
- Digital Assets
- Enterprise
---
