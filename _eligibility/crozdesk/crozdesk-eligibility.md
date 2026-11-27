---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"Vendor" or "you" means the individual or entity using BWZ''s services to list, promote, or publish a software product or other product.'
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Listing requirements
    text: The product supports English.
  - summary: Business or creative use only
    text: The product is intended for business or creative use.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: BWZ may accept or reject any listing request at its sole discretion, even if the product appears to meet the requirements below.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Crozdesk
provenance_date: '2026-11-09'
provider_name: Crozdesk
provider_slug: crozdesk
slug: crozdesk-eligibility
source_date: '2026-11-09'
source_filename: crozdesk-eligibility.yml
source_heading: Eligibility
source_page: https://vendor.revleads.com/vendor-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crozdesk\naid: crozdesk\nurl: https://vendor.revleads.com/vendor-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: '\"Vendor\" or \"you\" means the individual or entity using BWZ''s services to list, promote, or publish a software\n    product or other product.'\nrestricted_uses:\n- summary: Listing requirements\n  text: The product supports English.\n- summary: Business or creative use only\n  text: The product is intended for business or creative use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: BWZ\
  \ may accept or reject any listing request at its sole discretion, even if the product appears to meet\n    the requirements below.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/crozdesk/eligibility/crozdesk-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Crozdesk's own page on 2026-11-09.
synthetic: false
tags:
- B2B
- Software-as-a-Service
- Software Discovery
- Reviews
- Vendor Marketplace
---
