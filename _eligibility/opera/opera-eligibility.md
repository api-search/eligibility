---
api_specs:
- filename: opera-inventory-api-openapi.yml
  format: yaml
  label: Opera Inventory API
  slug: opera-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opera/openapi/opera-inventory-api-openapi.yml
- filename: opera-marketing-api-openapi.yml
  format: yaml
  label: Opera Marketing API
  slug: opera-marketing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opera/openapi/opera-marketing-api-openapi.yml
- filename: opera-report-api-openapi.yml
  format: yaml
  label: Opera Report API
  slug: opera-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opera/openapi/opera-report-api-openapi.yml
- filename: opera-dspreport-api-openapi.yml
  format: yaml
  label: Opera DSP Report API
  slug: opera-dspreport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opera/openapi/opera-dspreport-api-openapi.yml
- filename: opera-publisherreport-api-openapi.yml
  format: yaml
  label: Opera Publisher Report API
  slug: opera-publisherreport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opera/openapi/opera-publisherreport-api-openapi.yml
- filename: opera-upload-api-openapi.yml
  format: yaml
  label: Opera Upload API
  slug: opera-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opera/openapi/opera-upload-api-openapi.yml
- filename: opera-file-management-api-openapi.yml
  format: yaml
  label: Opera File Management API
  slug: opera-file-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opera/openapi/opera-file-management-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: In compliance with local law, certain Services and websites may not be available in some countries.
  minimum_age:
    text: To use Services, you must be at least 18 years old and/or have full legal capacity. If you are not 18 years old and/or you don’t have a full legal capacity you must have your parent or legal guardian’s permission to use Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or illicit use of VPN Pro
    text: You may not use, assist, or enable others to use the VPN Pro for any unlawful, illicit, illegal, criminal or fraudulent purpose whatsoever.
  - summary: AI Chat professional advice
    text: We strongly discourage asking AI Chat for medical, legal, or financial advice.
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
name: Opera
provenance_date: '2026-11-10'
provider_name: Opera
provider_slug: opera
slug: opera-eligibility
source_date: '2026-11-10'
source_filename: opera-eligibility.yml
source_heading: Eligibility
source_page: https://www.opera.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Opera\naid: opera\nurl: https://www.opera.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: In compliance with local law, certain Services and websites may not be available in some countries.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or illicit use of VPN Pro\n  text: You may not use, assist, or enable others to use the VPN Pro for any unlawful, illicit, illegal, criminal\n    or fraudulent purpose whatsoever.\n- summary: AI Chat professional advice\n  text: We strongly discourage asking AI Chat for medical, legal, or financial advice.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use Services, you must be at least 18 years old and/or have full legal capacity. If you are not 18 years\n    old and/or you don’t have a full legal capacity you must have your parent or legal guardian’s permission to\n    use Services.\n"
source_yaml_url: https://artifacts.apis.io/opera/eligibility/opera-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Opera's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer Technology
- Advertising
- AdTech
- Browser
- Monetization
- OpenRTB
- Marketing
- Mobile SDK
- Header Bidding
- Publisher Monetization
- Reporting
---
