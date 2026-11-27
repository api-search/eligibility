---
api_specs:
- filename: clayhr-openapi-generated.yml
  format: yaml
  label: ClayHR API
  slug: clayhr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clayhr/openapi/_ae-authored/clayhr-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that You are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: “You” refers to any individual who agrees to the “I accept the ClayHR Terms of Service” checkbox option on the Service homepage or while registering for the Service
    type: individual
  - text: if the Service is being used on behalf of an entity by an individual authorized to agree to such terms on behalf of such entity, then “You” refers to such entity.
    type: business
  minimum_age:
    text: If You are under 18 years of age then you are required to have a parent or guardian review and complete the registration process on your behalf.
    value: '18'
  restricted_uses:
  - summary: Hazardous environments
    text: the Service is not designed or licensed for use in hazardous environments requiring fail-safe controls, including without limitation operation of nuclear facilities, aircraft navigation/communication systems, air traffic control, and life support or weapons systems.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The company assumes no duty to verify registration information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ClayHR
provenance_date: '2026-11-09'
provider_name: ClayHR
provider_slug: clayhr
slug: clayhr-eligibility
source_date: '2026-11-09'
source_filename: clayhr-eligibility.yml
source_heading: Eligibility
source_page: https://www.clayhr.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClayHR\naid: clayhr\nurl: https://www.clayhr.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that You are not located in a country that is subject to a U.S. Government embargo, or that\n    has been designated by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: “You” refers to any individual who agrees to the “I accept the ClayHR Terms of Service” checkbox option\n    on the Service homepage or while registering for the Service\n- type: business\n  text: if the Service is being used on\
  \ behalf of an entity by an individual authorized to agree to such terms on\n    behalf of such entity, then “You” refers to such entity.\nrestricted_uses:\n- summary: Hazardous environments\n  text: the Service is not designed or licensed for use in hazardous environments requiring fail-safe controls,\n    including without limitation operation of nuclear facilities, aircraft navigation/communication systems, air\n    traffic control, and life support or weapons systems.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The company assumes no duty to verify registration information.\nminimum_age:\n  value: '18'\n  text: If You are under 18 years of age then you are required to have a parent or guardian review and complete\n    the registration process on your behalf.\n"
source_yaml_url: https://artifacts.apis.io/clayhr/eligibility/clayhr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from ClayHR's own page on 2026-11-09.
synthetic: false
tags:
- Human Resources
- HRMS
- Software-as-a-Service
- Artificial Intelligence
- Employee Management
- Performance Management
---
