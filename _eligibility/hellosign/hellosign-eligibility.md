---
api_specs:
- filename: hellosign-account-api-openapi.yml
  format: yaml
  label: Dropbox Sign (HelloSign) Account API
  slug: hellosign-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosign/openapi/hellosign-account-api-openapi.yml
- filename: hellosign-api-app-api-openapi.yml
  format: yaml
  label: Dropbox Sign (HelloSign) Api App API
  slug: hellosign-api-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosign/openapi/hellosign-api-app-api-openapi.yml
- filename: hellosign-bulk-send-job-api-openapi.yml
  format: yaml
  label: Dropbox Sign (HelloSign) Bulk Send Job API
  slug: hellosign-bulk-send-job-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosign/openapi/hellosign-bulk-send-job-api-openapi.yml
- filename: hellosign-embedded-api-openapi.yml
  format: yaml
  label: Dropbox Sign (HelloSign) Embedded API
  slug: hellosign-embedded-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosign/openapi/hellosign-embedded-api-openapi.yml
- filename: hellosign-fax-api-openapi.yml
  format: yaml
  label: Dropbox Sign (HelloSign) Fax API
  slug: hellosign-fax-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosign/openapi/hellosign-fax-api-openapi.yml
- filename: hellosign-fax-line-api-openapi.yml
  format: yaml
  label: Dropbox Sign (HelloSign) Fax Line API
  slug: hellosign-fax-line-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosign/openapi/hellosign-fax-line-api-openapi.yml
- filename: hellosign-report-api-openapi.yml
  format: yaml
  label: Dropbox Sign (HelloSign) Report API
  slug: hellosign-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosign/openapi/hellosign-report-api-openapi.yml
- filename: hellosign-signature-request-api-openapi.yml
  format: yaml
  label: Dropbox Sign (HelloSign) Signature Request API
  slug: hellosign-signature-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosign/openapi/hellosign-signature-request-api-openapi.yml
- filename: hellosign-team-api-openapi.yml
  format: yaml
  label: Dropbox Sign (HelloSign) Team API
  slug: hellosign-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosign/openapi/hellosign-team-api-openapi.yml
- filename: hellosign-template-api-openapi.yml
  format: yaml
  label: Dropbox Sign (HelloSign) Template API
  slug: hellosign-template-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosign/openapi/hellosign-template-api-openapi.yml
- filename: hellosign-unclaimed-draft-api-openapi.yml
  format: yaml
  label: Dropbox Sign (HelloSign) Unclaimed Draft API
  slug: hellosign-unclaimed-draft-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosign/openapi/hellosign-unclaimed-draft-api-openapi.yml
- filename: hellosign-callbacks-and-events-api-openapi.yml
  format: yaml
  label: Dropbox Sign (HelloSign) Callbacks and Events API
  slug: hellosign-callbacks-and-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosign/openapi/hellosign-callbacks-and-events-api-openapi.yml
- filename: hellosign-oauth-api-openapi.yml
  format: yaml
  label: Dropbox Sign (HelloSign) O Auth API
  slug: hellosign-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosign/openapi/hellosign-oauth-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Dropbox entity depends on whether customer is based in the United States, its territories and possessions, Canada or Mexico; no country-level service restriction stated beyond export control provisions.
  entity_types:
  - text: You may only use this Site and the Dropbox Sign Services if you are 18 years of age or older, able to legally agree to these Terms, and not a competitor to Dropbox
    type: individual
  minimum_age:
    text: You may only use this Site and the Dropbox Sign Services if you are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: No PHI without BAA
    text: store, transmit or otherwise process any information via the Dropbox Sign Services that falls within the definition of “Protected Health Information” under the HIPAA Privacy Rule (45 C.F.R. Section 164.051), unless Customer and Dropbox separately enter into a HIPAA Business Associate Agreement.
  - summary: No illegal or misleading use
    text: use or permit the Dropbox Sign Services to be used for any illegal or misleading purpose
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
name: Dropbox Sign (HelloSign)
provenance_date: '2026-11-09'
provider_name: Dropbox Sign (HelloSign)
provider_slug: hellosign
slug: hellosign-eligibility
source_date: '2026-11-09'
source_filename: hellosign-eligibility.yml
source_heading: Eligibility
source_page: https://sign.dropbox.com/about/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dropbox Sign (HelloSign)\naid: hellosign\nurl: https://sign.dropbox.com/about/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Dropbox entity depends on whether customer is based in the United States, its territories and possessions,\n    Canada or Mexico; no country-level service restriction stated beyond export control provisions.\nentity_types:\n- type: individual\n  text: You may only use this Site and the Dropbox Sign Services if you are 18 years of age or older, able to legally\n    agree to these Terms, and not a competitor to Dropbox\nrestricted_uses:\n- summary: No\
  \ PHI without BAA\n  text: store, transmit or otherwise process any information via the Dropbox Sign Services that falls within the\n    definition of “Protected Health Information” under the HIPAA Privacy Rule (45 C.F.R. Section 164.051), unless\n    Customer and Dropbox separately enter into a HIPAA Business Associate Agreement.\n- summary: No illegal or misleading use\n  text: use or permit the Dropbox Sign Services to be used for any illegal or misleading purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may only use this Site and the Dropbox Sign Services if you are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/hellosign/eligibility/hellosign-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Dropbox Sign (HelloSign)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Signature
- Documents
- Digital Agreements
- Signature Workflow
- Embedded Signing
- Compliance
---
