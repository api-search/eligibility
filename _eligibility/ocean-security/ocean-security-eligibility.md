---
api_specs:
- filename: ocean-security-metrics-api-openapi.yml
  format: yaml
  label: Ocean Security Metrics API
  slug: ocean-security-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ocean-security/openapi/ocean-security-metrics-api-openapi.yml
- filename: ocean-security-settings-api-openapi.yml
  format: yaml
  label: Ocean Security Settings API
  slug: ocean-security-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ocean-security/openapi/ocean-security-settings-api-openapi.yml
- filename: ocean-security-sonar-api-openapi.yml
  format: yaml
  label: Ocean Security Sonar API
  slug: ocean-security-sonar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ocean-security/openapi/ocean-security-sonar-api-openapi.yml
- filename: ocean-security-threats-api-openapi.yml
  format: yaml
  label: Ocean Security Threats API
  slug: ocean-security-threats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ocean-security/openapi/ocean-security-threats-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is only intended for individuals aged eighteen (18) years or older.
    type: individual
  - text: If you are using the Site on behalf of a company, organization, or other legal entity (collectively, " Company "), you represent and warrant that you have the authority to bind the Company to this Agreement.
    type: business
  minimum_age:
    text: The Site is only intended for individuals aged eighteen (18) years or older.
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
name: Ocean Security
provenance_date: '2026-11-10'
provider_name: Ocean Security
provider_slug: ocean-security
slug: ocean-security-eligibility
source_date: '2026-11-10'
source_filename: ocean-security-eligibility.yml
source_heading: Eligibility
source_page: https://ocean.security/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ocean Security\naid: ocean-security\nurl: https://ocean.security/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only intended for individuals aged eighteen (18) years or older.\n- type: business\n  text: If you are using the Site on behalf of a company, organization, or other legal entity (collectively, \" Company\n    \"), you represent and warrant that you have the authority to bind the Company to this Agreement.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: The Site is only intended for individuals aged eighteen (18) years or older.\n"
source_yaml_url: https://artifacts.apis.io/ocean-security/eligibility/ocean-security-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Ocean Security's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Email Security
- Cybersecurity
- Phishing
- Threat Detection
- Email
- Anti-Phishing
- Artificial Intelligence
- Threat Intelligence
---
