---
api_specs:
- filename: smallstep-authentication-api-openapi.yml
  format: yaml
  label: SmallStep Authentication API
  slug: smallstep-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smallstep/openapi/smallstep-authentication-api-openapi.yml
- filename: smallstep-certificates-api-openapi.yml
  format: yaml
  label: SmallStep Certificates API
  slug: smallstep-certificates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smallstep/openapi/smallstep-certificates-api-openapi.yml
- filename: smallstep-credentials-api-openapi.yml
  format: yaml
  label: SmallStep Credentials API
  slug: smallstep-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smallstep/openapi/smallstep-credentials-api-openapi.yml
- filename: smallstep-device-inventory-api-openapi.yml
  format: yaml
  label: SmallStep Device Inventory API
  slug: smallstep-device-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smallstep/openapi/smallstep-device-inventory-api-openapi.yml
- filename: smallstep-pki-architecture-api-openapi.yml
  format: yaml
  label: SmallStep PKI Architecture API
  slug: smallstep-pki-architecture-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smallstep/openapi/smallstep-pki-architecture-api-openapi.yml
- filename: smallstep-protect-api-openapi.yml
  format: yaml
  label: SmallStep Protect API
  slug: smallstep-protect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smallstep/openapi/smallstep-protect-api-openapi.yml
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
  - summary: Unlawful or prohibited purposes
    text: you promise not to use the Service for any purpose that is unlawful or prohibited by these Terms of Use, or any other purpose not reasonably intended by Smallstep.
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
name: SmallStep
provenance_date: '2026-11-10'
provider_name: SmallStep
provider_slug: smallstep
slug: smallstep-eligibility
source_date: '2026-11-10'
source_filename: smallstep-eligibility.yml
source_heading: Eligibility
source_page: https://smallstep.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SmallStep\naid: smallstep\nurl: https://smallstep.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited purposes\n  text: you promise not to use the Service for any purpose that is unlawful or prohibited by these Terms of Use,\n    or any other purpose not reasonably intended by Smallstep.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/smallstep/eligibility/smallstep-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from SmallStep's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Developer Tools
- Certificate Authority
- PKI
- Device Identity
- Zero Trust
- Certificate Management
- mTLS
- ACME
- SSH
- Security
---
