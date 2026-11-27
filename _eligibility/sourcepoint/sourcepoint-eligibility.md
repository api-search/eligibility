---
api_specs:
- filename: sourcepoint-gdpr-reporting-api-api-openapi.yml
  format: yaml
  label: Sourcepoint GDPR reporting API
  slug: sourcepoint-gdpr-reporting-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcepoint/openapi/sourcepoint-gdpr-reporting-api-api-openapi.yml
- filename: sourcepoint-gdpr-tcf-end-user-consent-status-api-openapi.yml
  format: yaml
  label: Sourcepoint GDPR TCF end-user consent status API
  slug: sourcepoint-gdpr-tcf-end-user-consent-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcepoint/openapi/sourcepoint-gdpr-tcf-end-user-consent-status-api-openapi.yml
- filename: sourcepoint-gdpr-tcf-vendor-list-api-openapi.yml
  format: yaml
  label: Sourcepoint GDPR TCF vendor list API
  slug: sourcepoint-gdpr-tcf-vendor-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcepoint/openapi/sourcepoint-gdpr-tcf-vendor-list-api-openapi.yml
- filename: sourcepoint-preferences-end-user-history-api-openapi.yml
  format: yaml
  label: Sourcepoint Preferences end-user history API
  slug: sourcepoint-preferences-end-user-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcepoint/openapi/sourcepoint-preferences-end-user-history-api-openapi.yml
- filename: sourcepoint-u-s-multi-state-privacy-end-user-consent-status-api-openapi.yml
  format: yaml
  label: Sourcepoint U.S. Multi-State Privacy end-user consent status API
  slug: sourcepoint-u-s-multi-state-privacy-end-user-consent-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcepoint/openapi/sourcepoint-u-s-multi-state-privacy-end-user-consent-status-api-openapi.yml
- filename: sourcepoint-u-s-multi-state-privacy-reporting-api-api-openapi.yml
  format: yaml
  label: Sourcepoint U.S. Multi-State Privacy reporting API
  slug: sourcepoint-u-s-multi-state-privacy-reporting-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcepoint/openapi/sourcepoint-u-s-multi-state-privacy-reporting-api-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Adult, illegal or offensive linking sites
    text: provided further that the linking site does not contain any adult or illegal material or any material that is offensive, harassing or otherwise objectionable
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
name: Sourcepoint
provenance_date: '2026-11-10'
provider_name: Sourcepoint
provider_slug: sourcepoint
slug: sourcepoint-eligibility
source_date: '2026-11-10'
source_filename: sourcepoint-eligibility.yml
source_heading: Eligibility
source_page: https://sourcepoint.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sourcepoint\naid: sourcepoint\nurl: https://sourcepoint.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Adult, illegal or offensive linking sites\n  text: provided further that the linking site does not contain any adult or illegal material or any material that\n    is offensive, harassing or otherwise objectionable\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sourcepoint/eligibility/sourcepoint-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Sourcepoint's own page on 2026-11-10.
synthetic: false
tags:
- Privacy
- Consent Management
- Consent Management Platform
- CMP
- GDPR
- CCPA
- LGPD
- IAB TCF
- IAB GPP
- USNAT
- DSAR
- Adblock Recovery
- Compliance Monitoring
- Publisher Technology
- AdTech
- MarTech
- Privacy Engineering
- CTV
- OTT
- Mobile SDK
- Web SDK
---
