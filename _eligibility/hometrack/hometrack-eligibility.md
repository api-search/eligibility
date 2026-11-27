---
api_specs:
- filename: hometrack-authentication-api-openapi.yml
  format: yaml
  label: Hometrack Authentication API
  slug: hometrack-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-authentication-api-openapi.yml
- filename: hometrack-brands-api-openapi.yml
  format: yaml
  label: Hometrack Brands API
  slug: hometrack-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-brands-api-openapi.yml
- filename: hometrack-broker-api-openapi.yml
  format: yaml
  label: Hometrack Broker API
  slug: hometrack-broker-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-broker-api-openapi.yml
- filename: hometrack-epc-hometrack-api-openapi.yml
  format: yaml
  label: Hometrack Epc Hometrack API
  slug: hometrack-epc-hometrack-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-epc-hometrack-api-openapi.yml
- filename: hometrack-flood-twinn-api-openapi.yml
  format: yaml
  label: Hometrack Flood Twinn API
  slug: hometrack-flood-twinn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-flood-twinn-api-openapi.yml
- filename: hometrack-ground-coastalerosion-twinn-api-openapi.yml
  format: yaml
  label: Hometrack Ground Coastalerosion Twinn API
  slug: hometrack-ground-coastalerosion-twinn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-ground-coastalerosion-twinn-api-openapi.yml
- filename: hometrack-ground-subsidence-twinn-api-openapi.yml
  format: yaml
  label: Hometrack Ground Subsidence Twinn API
  slug: hometrack-ground-subsidence-twinn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-ground-subsidence-twinn-api-openapi.yml
- filename: hometrack-ground-terrafirma-api-openapi.yml
  format: yaml
  label: Hometrack Ground Terrafirma API
  slug: hometrack-ground-terrafirma-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-ground-terrafirma-api-openapi.yml
- filename: hometrack-internal-api-openapi.yml
  format: yaml
  label: Hometrack Internal API
  slug: hometrack-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-internal-api-openapi.yml
- filename: hometrack-licences-api-openapi.yml
  format: yaml
  label: Hometrack Licences API
  slug: hometrack-licences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-licences-api-openapi.yml
- filename: hometrack-organisation-api-openapi.yml
  format: yaml
  label: Hometrack Organisation API
  slug: hometrack-organisation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-organisation-api-openapi.yml
- filename: hometrack-partners-api-openapi.yml
  format: yaml
  label: Hometrack Partners API
  slug: hometrack-partners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-partners-api-openapi.yml
- filename: hometrack-pvrplugin-api-openapi.yml
  format: yaml
  label: Hometrack Pvrplugin API
  slug: hometrack-pvrplugin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-pvrplugin-api-openapi.yml
- filename: hometrack-reporting-api-openapi.yml
  format: yaml
  label: Hometrack Reporting API
  slug: hometrack-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-reporting-api-openapi.yml
- filename: hometrack-status-api-openapi.yml
  format: yaml
  label: Hometrack Status API
  slug: hometrack-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-status-api-openapi.yml
- filename: hometrack-trial-api-openapi.yml
  format: yaml
  label: Hometrack Trial API
  slug: hometrack-trial-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-trial-api-openapi.yml
- filename: hometrack-valuation-api-openapi.yml
  format: yaml
  label: Hometrack Valuation API
  slug: hometrack-valuation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-valuation-api-openapi.yml
- filename: hometrack-zoopla-api-openapi.yml
  format: yaml
  label: Hometrack Zoopla API
  slug: hometrack-zoopla-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hometrack/openapi/hometrack-zoopla-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: The Hometrack Site is a place for you to access information and other services relating to properties in the United Kingdom.
  entity_types:
  - text: The hometrack.com website (the “Hometrack Site”) is provided to you for your personal use subject to these Terms of Use.
    type: individual
  - text: Please contact enquiries@hometrack.com if you would like to use the information on the Hometrack Site for commercial purposes.
    type: business
  minimum_age:
    text: When you register with the Hometrack Site you warrant that you are over eighteen years of age.
    value: '18'
  restricted_uses:
  - summary: commercial purposes
    text: You warrant that you are using the Hometrack Site for yourself and not for any commercial purposes and that you have the legal authority to use the Hometrack Site in accordance with these Terms of Use.
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
name: Hometrack
provenance_date: '2026-11-09'
provider_name: Hometrack
provider_slug: hometrack
slug: hometrack-eligibility
source_date: '2026-11-09'
source_filename: hometrack-eligibility.yml
source_heading: Eligibility
source_page: https://www.hometrack.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hometrack\naid: hometrack\nurl: https://www.hometrack.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: The Hometrack Site is a place for you to access information and other services relating to properties in\n    the United Kingdom.\nentity_types:\n- type: individual\n  text: The hometrack.com website (the “Hometrack Site”) is provided to you for your personal use subject to these\n    Terms of Use.\n- type: business\n  text: Please contact enquiries@hometrack.com if you would like to use the information on the Hometrack Site for\n    commercial purposes.\nrestricted_uses:\n\
  - summary: commercial purposes\n  text: You warrant that you are using the Hometrack Site for yourself and not for any commercial purposes and that\n    you have the legal authority to use the Hometrack Site in accordance with these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: When you register with the Hometrack Site you warrant that you are over eighteen years of age.\n"
source_yaml_url: https://artifacts.apis.io/hometrack/eligibility/hometrack-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Hometrack's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- United Kingdom
- PropTech
- Valuation
- AVM
- Mortgage
- Property Data
- Climate Risk
- Lending
- Surveying
---
