---
api_specs:
- filename: inboxvet-com-openapi-generated.yml
  format: yaml
  label: inboxvet-com API
  slug: inboxvet-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inboxvet-com/openapi/_ae-authored/inboxvet-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of a company, you confirm you are authorised to accept these Terms for it.
    type: business
  minimum_age:
    text: be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Verifying addresses without lawful right
    text: verify email addresses you have no lawful right to process
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
name: inboxvet-com
provenance_date: '2026-11-09'
provider_name: inboxvet-com
provider_slug: inboxvet-com
slug: inboxvet-com-eligibility
source_date: '2026-11-09'
source_filename: inboxvet-com-eligibility.yml
source_heading: Eligibility
source_page: https://inboxvet.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: inboxvet-com\naid: inboxvet-com\nurl: https://inboxvet.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of a company, you confirm you are authorised to accept these Terms for\n    it.\nrestricted_uses:\n- summary: Verifying addresses without lawful right\n  text: verify email addresses you have no lawful right to process\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/inboxvet-com/eligibility/inboxvet-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from inboxvet-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email Verification
- Software-as-a-Service
- Marketing
---
