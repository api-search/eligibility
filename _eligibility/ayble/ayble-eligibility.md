---
api_specs:
- filename: ayble-openapi-generated.yml
  format: yaml
  label: Ayble API
  slug: ayble-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayble/openapi/_ae-authored/ayble-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for visitors located within the United States. We make no representation that the Service is appropriate or available for use outside of the United States. Access to the Service from countries or territories or by individuals where such access is illegal is prohibited.
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Illegal use
    text: use the Service for any illegal purpose or in violation of any local, state, national, or international law
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Your eligibility for Medical Services may depend on a determination of eligibility by one or more additional parties, such as the Provider and/or your insurance carrier.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ayble
provenance_date: '2026-11-09'
provider_name: Ayble
provider_slug: ayble
slug: ayble-eligibility
source_date: '2026-11-09'
source_filename: ayble-eligibility.yml
source_heading: Eligibility
source_page: https://www.ayblehealth.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ayble\naid: ayble\nurl: https://www.ayblehealth.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for visitors located within the United States. We make no representation that the\n    Service is appropriate or available for use outside of the United States. Access to the Service from countries\n    or territories or by individuals where such access is illegal is prohibited.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If you are an entity,\
  \ organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: Illegal use\n  text: use the Service for any illegal purpose or in violation of any local, state, national, or international\n    law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Your eligibility for Medical Services may depend on a determination of eligibility by one or more additional\n    parties, such as the Provider and/or your insurance carrier.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/ayble/eligibility/ayble-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Ayble's own page on 2026-11-09.
synthetic: false
tags:
- Health
- Telehealth
- Digestive Health
- VirtualClinic
- Employer Benefits
- Healthcare
---
