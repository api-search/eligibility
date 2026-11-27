---
api_specs:
- filename: verified-inc-openapi-generated.yml
  format: yaml
  label: Verified API
  slug: verified-inc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verified-inc/openapi/_ae-authored/verified-inc-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and offered by Verified from its facilities in the United States of America. Verified makes no representations that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH VERIFIED
    type: individual
  - text: YOU HAVE THE AUTHORITY TO ENTER INTO THE TERMS OF USE PERSONALLY OR ON BEHALF OF THE ENTITY YOU HAVE NAMED AS THE USER
    type: business
  minimum_age:
    text: You represent that you are (i) at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Export control restrictions
    text: You may not use, export, import, or transfer the Services except as authorized by U.S. law
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
name: Verified
provenance_date: '2026-11-10'
provider_name: Verified
provider_slug: verified-inc
slug: verified-inc-eligibility
source_date: '2026-11-10'
source_filename: verified-inc-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.prod.website-files.com/6ab714a5dd3542d60e567c99/6ac938d72569ccfe2f49c609_verified-terms-of-use-2026-06-17.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Verified\naid: verified-inc\nurl: https://cdn.prod.website-files.com/6ab714a5dd3542d60e567c99/6ac938d72569ccfe2f49c609_verified-terms-of-use-2026-06-17.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and offered by Verified from its facilities in the United States of America.\n    Verified makes no representations that the Services are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH VERIFIED\n- type: business\n  text: YOU HAVE THE AUTHORITY TO ENTER\
  \ INTO THE TERMS OF USE PERSONALLY OR ON BEHALF OF THE ENTITY YOU HAVE NAMED\n    AS THE USER\nrestricted_uses:\n- summary: Export control restrictions\n  text: You may not use, export, import, or transfer the Services except as authorized by U.S. law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are (i) at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/verified-inc/eligibility/verified-inc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Verified's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Identity Verification
- Onboarding
- Phone Verification
- KYC
- Autofill
- Health Insurance
- Fintech
---
