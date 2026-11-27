---
api_specs:
- filename: lifx-color-api-openapi.yml
  format: yaml
  label: LIFX Color API
  slug: lifx-color-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifx/openapi/lifx-color-api-openapi.yml
- filename: lifx-lights-api-openapi.yml
  format: yaml
  label: LIFX Lights API
  slug: lifx-lights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifx/openapi/lifx-lights-api-openapi.yml
- filename: lifx-scenes-api-openapi.yml
  format: yaml
  label: LIFX Scenes API
  slug: lifx-scenes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifx/openapi/lifx-scenes-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: LIFX currently ships to addresses within the continental United States only.
  entity_types:
  - text: The Services are intended for users who are at least 18 years of age, or the age of majority in their jurisdiction if higher.
    type: individual
  - text: If you are using the Services on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years of age, or the age of majority in their jurisdiction if higher.
    value: '18'
  restricted_uses:
  - summary: Prohibited conduct
    text: 'You agree not to use the Services to: violate any applicable federal, state, local, or international law or regulation'
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
name: LIFX
provenance_date: '2026-11-09'
provider_name: LIFX
provider_slug: lifx
slug: lifx-eligibility
source_date: '2026-11-09'
source_filename: lifx-eligibility.yml
source_heading: Eligibility
source_page: https://www.lifx.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LIFX\naid: lifx\nurl: https://www.lifx.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: LIFX currently ships to addresses within the continental United States only.\nentity_types:\n- type: individual\n  text: The Services are intended for users who are at least 18 years of age, or the age of majority in their jurisdiction\n    if higher.\n- type: business\n  text: If you are using the Services on behalf of a company or other legal entity, you represent and warrant that\n    you have the authority to bind that entity to these Terms\nrestricted_uses:\n\
  - summary: Prohibited conduct\n  text: 'You agree not to use the Services to: violate any applicable federal, state, local, or international law\n    or regulation'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years of age, or the age of majority in their jurisdiction\n    if higher.\n"
source_yaml_url: https://artifacts.apis.io/lifx/eligibility/lifx-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from LIFX's own page on 2026-11-09.
synthetic: false
tags:
- Smart Lighting
- Wi‑Fi Bulbs
- Home Automation
- Lighting Fixtures
---
