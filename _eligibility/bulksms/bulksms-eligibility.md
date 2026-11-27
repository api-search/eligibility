---
api_specs:
- filename: bulksms-attachments-api-openapi.yml
  format: yaml
  label: BulkSMS Attachments API
  slug: bulksms-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bulksms/openapi/bulksms-attachments-api-openapi.yml
- filename: bulksms-blocked-numbers-api-openapi.yml
  format: yaml
  label: BulkSMS Blocked Numbers API
  slug: bulksms-blocked-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bulksms/openapi/bulksms-blocked-numbers-api-openapi.yml
- filename: bulksms-credits-api-openapi.yml
  format: yaml
  label: BulkSMS Credits API
  slug: bulksms-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bulksms/openapi/bulksms-credits-api-openapi.yml
- filename: bulksms-message-api-openapi.yml
  format: yaml
  label: BulkSMS Message API
  slug: bulksms-message-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bulksms/openapi/bulksms-message-api-openapi.yml
- filename: bulksms-profile-api-openapi.yml
  format: yaml
  label: BulkSMS Profile API
  slug: bulksms-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bulksms/openapi/bulksms-profile-api-openapi.yml
- filename: bulksms-webhooks-api-openapi.yml
  format: yaml
  label: BulkSMS Webhooks API
  slug: bulksms-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bulksms/openapi/bulksms-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may not use the Website or the Services if you are not of a legal age to form a binding contract with BulkSMS.
    type: individual
  minimum_age:
    text: You may not use the Website or the Services if you are not of a legal age to form a binding contract with BulkSMS.
    value: null
  restricted_uses:
  - summary: Gambling-related use
    text: Users acknowledge in particular that use of the Services for purposes related to gambling activities may be prohibited in certain territories.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: BulkSMS reserves the right to refuse to accept and/or execute an order or request to do business or to render any Services without giving any reasons therefor.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BulkSMS
provenance_date: '2026-11-09'
provider_name: BulkSMS
provider_slug: bulksms
slug: bulksms-eligibility
source_date: '2026-11-09'
source_filename: bulksms-eligibility.yml
source_heading: Eligibility
source_page: https://www.bulksms.com/company/terms-and-conditions.htm
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BulkSMS\naid: bulksms\nurl: https://www.bulksms.com/company/terms-and-conditions.htm\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may not use the Website or the Services if you are not of a legal age to form a binding contract with\n    BulkSMS.\nrestricted_uses:\n- summary: Gambling-related use\n  text: Users acknowledge in particular that use of the Services for purposes related to gambling activities may\n    be prohibited in certain territories.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text:\
  \ BulkSMS reserves the right to refuse to accept and/or execute an order or request to do business or to render\n    any Services without giving any reasons therefor.\nminimum_age:\n  value: null\n  text: You may not use the Website or the Services if you are not of a legal age to form a binding contract with\n    BulkSMS.\n"
source_yaml_url: https://artifacts.apis.io/bulksms/eligibility/bulksms-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from BulkSMS's own page on 2026-11-09.
synthetic: false
tags:
- SMS
- Messaging
- Communications
- Business
- Bulk SMS
---
