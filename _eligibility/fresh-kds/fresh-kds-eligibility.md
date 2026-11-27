---
api_specs:
- filename: fresh-kds-openapi-generated.yml
  format: yaml
  label: Fresh KDS API
  slug: fresh-kds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fresh-kds/openapi/_ae-authored/fresh-kds-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and offered by Fresh Technology from its facilities in the United States of America. Fresh Technology makes no representations that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: THE TERM “YOU” REFERS TO THE INDIVIDUAL OR LEGAL ENTITY, AS APPLICABLE, IDENTIFIED AS THE USER WHEN YOU REGISTERED ON THE WEBSITE.
    type: business
  minimum_age:
    text: (2) YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH FRESH TECHNOLOGY
    value: legal age
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: No contract will exist between you and Fresh Technology for the Services until Fresh Technology accepts your order by a confirmatory e-mail, text message, or other appropriate means of communication.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fresh KDS
provenance_date: '2026-11-09'
provider_name: Fresh KDS
provider_slug: fresh-kds
slug: fresh-kds-eligibility
source_date: '2026-11-09'
source_filename: fresh-kds-eligibility.yml
source_heading: Eligibility
source_page: https://www.fresh.technology/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fresh KDS\naid: fresh-kds\nurl: https://www.fresh.technology/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and offered by Fresh Technology from its facilities in the United States of\n    America. Fresh Technology makes no representations that the Services are appropriate or available for use in\n    other locations.\nentity_types:\n- type: business\n  text: THE TERM “YOU” REFERS TO THE INDIVIDUAL OR LEGAL ENTITY, AS APPLICABLE, IDENTIFIED AS THE USER WHEN YOU\n    REGISTERED ON THE WEBSITE.\nrestricted_uses:\
  \ []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: No contract will exist between you and Fresh Technology for the Services until Fresh Technology accepts\n    your order by a confirmatory e-mail, text message, or other appropriate means of communication.\nminimum_age:\n  value: legal age\n  text: (2) YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH FRESH TECHNOLOGY\n"
source_yaml_url: https://artifacts.apis.io/fresh-kds/eligibility/fresh-kds-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Fresh KDS's own page on 2026-11-09.
synthetic: false
tags:
- Kitchen Display System
- Restaurant
- POS Integration
- Enterprise
- Tablet-based
- Food Service
---
