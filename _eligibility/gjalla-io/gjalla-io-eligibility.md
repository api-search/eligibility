---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If you are using the Service on behalf of an organization, you are agreeing to these Terms for that organization
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: No professional security audit representation
    text: Security Outputs do not constitute a professional security audit, certification, attestation, accreditation, compliance assessment, or legal opinion, and must not be represented as such to any third party;
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
name: gjalla-io
provenance_date: '2026-11-09'
provider_name: gjalla-io
provider_slug: gjalla-io
slug: gjalla-io-eligibility
source_date: '2026-11-09'
source_filename: gjalla-io-eligibility.yml
source_heading: Eligibility
source_page: https://gjalla.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: gjalla-io\naid: gjalla-io\nurl: https://gjalla.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If you are using the Service on behalf of an organization, you are agreeing to these Terms for that organization\nrestricted_uses:\n- summary: No professional security audit representation\n  text: Security Outputs do not constitute a professional security audit, certification, attestation, accreditation,\n    compliance assessment, or legal opinion,\
  \ and must not be represented as such to any third party;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/gjalla-io/eligibility/gjalla-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from gjalla-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- IoT
- Data Analytics
- Real-Time
---
