---
api_specs:
- filename: photon-agent-discovery-api-openapi.yml
  format: yaml
  label: Photon Agent discovery API
  slug: photon-agent-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/photon/openapi/photon-agent-discovery-api-openapi.yml
- filename: photon-newsletter-api-openapi.yml
  format: yaml
  label: Photon Newsletter API
  slug: photon-newsletter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/photon/openapi/photon-newsletter-api-openapi.yml
- filename: photon-onboarding-api-openapi.yml
  format: yaml
  label: Photon Onboarding API
  slug: photon-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/photon/openapi/photon-onboarding-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Use of the Platform for the purposes of prescriptions is limited to the United States of America only.
  entity_types:
  - text: customers of Photon that have entered into any written or electronic order directly with Photon that incorporates these Terms by reference
    type: business
  - text: If Customer is a government end user, then this provision also applies to Customer.
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No controlled substance prescriptions
    text: Users may not transmit prescriptions or Orders through the Platform for controlled substances.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Access to the Services for the purposes of ordering prescriptions shall be strictly limited to Healthcare Providers who are properly licensed, registered or authorized to prescribe and are not included in the CMS preclusion list or otherwise excluded from participation in federal health care programs.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Photon
provenance_date: '2026-11-10'
provider_name: Photon
provider_slug: photon
slug: photon-eligibility
source_date: '2026-11-10'
source_filename: photon-eligibility.yml
source_heading: Eligibility
source_page: https://photonhealth.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Photon\naid: photon\nurl: https://photonhealth.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Use of the Platform for the purposes of prescriptions is limited to the United States of America only.\nentity_types:\n- type: business\n  text: customers of Photon that have entered into any written or electronic order directly with Photon that incorporates\n    these Terms by reference\n- type: government\n  text: If Customer is a government end user, then this provision also applies to Customer.\nrestricted_uses:\n- summary: No controlled substance prescriptions\n  text:\
  \ Users may not transmit prescriptions or Orders through the Platform for controlled substances.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Access to the Services for the purposes of ordering prescriptions shall be strictly limited to Healthcare\n    Providers who are properly licensed, registered or authorized to prescribe and are not included in the CMS preclusion\n    list or otherwise excluded from participation in federal health care programs.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/photon/eligibility/photon-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Photon's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- United States
- e-Prescribing
- Pharmacy
- Prescription Routing
- GraphQL
- Clinical API
- Digital Health
- Benefit Check
- OAuth
- Authentication
---
