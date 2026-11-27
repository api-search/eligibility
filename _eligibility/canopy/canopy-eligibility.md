---
api_specs:
- filename: canopy-consent-api-api-openapi.yml
  format: yaml
  label: Canopy Connect Consent API
  slug: canopy-consent-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canopy/openapi/canopy-consent-api-api-openapi.yml
- filename: canopy-enrichment-api-api-openapi.yml
  format: yaml
  label: Canopy Connect Enrichment API
  slug: canopy-enrichment-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canopy/openapi/canopy-enrichment-api-api-openapi.yml
- filename: canopy-misc-api-api-openapi.yml
  format: yaml
  label: Canopy Connect Misc API
  slug: canopy-misc-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canopy/openapi/canopy-misc-api-api-openapi.yml
- filename: canopy-monitorings-api-api-openapi.yml
  format: yaml
  label: Canopy Connect Monitorings API
  slug: canopy-monitorings-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canopy/openapi/canopy-monitorings-api-api-openapi.yml
- filename: canopy-policy-check-team-setting-api-api-openapi.yml
  format: yaml
  label: Canopy Connect Policy Check Team Setting API
  slug: canopy-policy-check-team-setting-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canopy/openapi/canopy-policy-check-team-setting-api-api-openapi.yml
- filename: canopy-policy-forms-api-api-openapi.yml
  format: yaml
  label: Canopy Connect Policy Forms API
  slug: canopy-policy-forms-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canopy/openapi/canopy-policy-forms-api-api-openapi.yml
- filename: canopy-policy-search-api-api-openapi.yml
  format: yaml
  label: Canopy Connect Policy Search API
  slug: canopy-policy-search-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canopy/openapi/canopy-policy-search-api-api-openapi.yml
- filename: canopy-pulls-api-api-openapi.yml
  format: yaml
  label: Canopy Connect Pulls API
  slug: canopy-pulls-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canopy/openapi/canopy-pulls-api-api-openapi.yml
- filename: canopy-servicings-api-api-openapi.yml
  format: yaml
  label: Canopy Connect Servicings API
  slug: canopy-servicings-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canopy/openapi/canopy-servicings-api-api-openapi.yml
- filename: canopy-teams-api-api-openapi.yml
  format: yaml
  label: Canopy Connect Teams API
  slug: canopy-teams-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canopy/openapi/canopy-teams-api-api-openapi.yml
- filename: canopy-webhooks-api-api-openapi.yml
  format: yaml
  label: Canopy Connect Webhooks API
  slug: canopy-webhooks-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canopy/openapi/canopy-webhooks-api-api-openapi.yml
- filename: canopy-whitelabel-api-api-openapi.yml
  format: yaml
  label: Canopy Connect Whitelabel API
  slug: canopy-whitelabel-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canopy/openapi/canopy-whitelabel-api-api-openapi.yml
- filename: canopy-widgets-api-api-openapi.yml
  format: yaml
  label: Canopy Connect Widgets API
  slug: canopy-widgets-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canopy/openapi/canopy-widgets-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Site or Services if you are a person barred from receiving the Services under the laws of the United States or other countries, including the country in which you are resident or from which you use the Site or Services.
  entity_types:
  - text: If you are using the Site or Services on behalf of an organization, you are agreeing to these Terms and the Privacy Policy for that organization
    type: business
  minimum_age:
    text: You affirm that you are over the age of 18, as the Site and Services are not intended for children under 18.
    value: '18'
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
name: Canopy Connect
provenance_date: '2026-11-09'
provider_name: Canopy Connect
provider_slug: canopy
slug: canopy-eligibility
source_date: '2026-11-09'
source_filename: canopy-eligibility.yml
source_heading: Eligibility
source_page: https://www.usecanopy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Canopy Connect\naid: canopy\nurl: https://www.usecanopy.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Site or Services if you are a person barred from receiving the Services under the laws\n    of the United States or other countries, including the country in which you are resident or from which you use\n    the Site or Services.\nentity_types:\n- type: business\n  text: If you are using the Site or Services on behalf of an organization, you are agreeing to these Terms and\n    the Privacy Policy for that organization\nrestricted_uses: []\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You affirm that you are over the age of 18, as the Site and Services are not intended for children under\n    18.\n"
source_yaml_url: https://artifacts.apis.io/canopy/eligibility/canopy-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Canopy Connect's own page on 2026-11-09.
synthetic: false
tags:
- Auto Insurance
- Casualty
- Financial Services
- Home Insurance
- Insurance
- Insurance Verification
- Property
---
