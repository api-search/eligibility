---
api_specs:
- filename: tarana-wireless-alerts-asyncapi.yml
  format: yaml
  label: Tarana Cloud Suite (TCS) Northbound API
  slug: tarana-cloud-suite-tcs-northbound-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/tarana-wireless/asyncapi/tarana-wireless-alerts-asyncapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are entering into this Agreement on behalf of a company or legal entity, You represent that You have the authority to bind that company or entity to this Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Country-specific configurations
    text: You agree to configure and operate the Products in each country only using the Configurations permitted by that country.
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
name: Tarana Wireless
provenance_date: '2026-11-10'
provider_name: Tarana Wireless
provider_slug: tarana-wireless
slug: tarana-wireless-eligibility
source_date: '2026-11-10'
source_filename: tarana-wireless-eligibility.yml
source_heading: Eligibility
source_page: https://taranawireless.com/legal/#tcs-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tarana Wireless\naid: tarana-wireless\nurl: https://taranawireless.com/legal/#tcs-terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You are entering into this Agreement on behalf of a company or legal entity, You represent that You have\n    the authority to bind that company or entity to this Agreement\nrestricted_uses:\n- summary: Country-specific configurations\n  text: You agree to configure and operate the Products in each country only using the Configurations permitted\n    by that country.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tarana-wireless/eligibility/tarana-wireless-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Tarana Wireless's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Networking
- Telecommunications
- Fixed Wireless Access
- Broadband
- Wireless
- Network Management
- Internet Service Providers
- CBRS
- Spectrum
- Telemetry
- Hardware
---
