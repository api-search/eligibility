---
api_specs:
- filename: appsamurai-campaign-spend-api-openapi.yml
  format: yaml
  label: Appsamurai Campaign Spend API
  slug: appsamurai-campaign-spend-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsamurai/openapi/appsamurai-campaign-spend-api-openapi.yml
- filename: appsamurai-app-api-openapi.yml
  format: yaml
  label: Appsamurai App API
  slug: appsamurai-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsamurai/openapi/appsamurai-app-api-openapi.yml
- filename: appsamurai-audience-api-openapi.yml
  format: yaml
  label: Appsamurai Audience API
  slug: appsamurai-audience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsamurai/openapi/appsamurai-audience-api-openapi.yml
- filename: appsamurai-instance-api-openapi.yml
  format: yaml
  label: Appsamurai Instance API
  slug: appsamurai-instance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsamurai/openapi/appsamurai-instance-api-openapi.yml
- filename: appsamurai-segment-api-openapi.yml
  format: yaml
  label: Appsamurai Segment API
  slug: appsamurai-segment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsamurai/openapi/appsamurai-segment-api-openapi.yml
- filename: appsamurai-story-api-openapi.yml
  format: yaml
  label: Appsamurai Story API
  slug: appsamurai-story-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsamurai/openapi/appsamurai-story-api-openapi.yml
- filename: appsamurai-story-group-api-openapi.yml
  format: yaml
  label: Appsamurai Story Group API
  slug: appsamurai-story-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsamurai/openapi/appsamurai-story-group-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - VE
    served: []
    text: the Crimea region of Ukraine, Cuba, Iran, North Korea, Syria, and the Government of Venezuela
  entity_types:
  - text: 'By registering, you certify to us that: (i) you are at least 18 years of age'
    type: individual
  - text: an organization includes a corporation, partnership, LLC, or other entity
    type: business
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Sanctioned jurisdictions and persons
    text: You hereby represent that you are not an Embargoed Target or otherwise subject to any sanctions under any Economic Sanctions Laws.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: name and surname or company name, email, address, tax ID, and Zip Code must be completed
excluded_countries:
- CU
- IR
- KP
- SY
- VE
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Appsamurai
provenance_date: '2026-11-09'
provider_name: Appsamurai
provider_slug: appsamurai
slug: appsamurai-eligibility
source_date: '2026-11-09'
source_filename: appsamurai-eligibility.yml
source_heading: Eligibility
source_page: https://appsamurai.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Appsamurai\naid: appsamurai\nurl: https://appsamurai.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - VE\n  text: the Crimea region of Ukraine, Cuba, Iran, North Korea, Syria, and the Government of Venezuela\nentity_types:\n- type: individual\n  text: 'By registering, you certify to us that: (i) you are at least 18 years of age'\n- type: business\n  text: an organization includes a corporation, partnership, LLC, or other entity\nrestricted_uses:\n- summary: Sanctioned jurisdictions and persons\n  text: You hereby represent that you are not\
  \ an Embargoed Target or otherwise subject to any sanctions under any\n    Economic Sanctions Laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: name and surname or company name, email, address, tax ID, and Zip Code must be completed\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/appsamurai/eligibility/appsamurai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Appsamurai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mobile
- Advertising
- User Acquisition
- Marketing
- App Growth
- Attribution
- Analytics
- Mobile Marketing
- SDK
- Storyly
- Content Experience
- In-App Stories
- MCP
- Mobile Commerce
---
