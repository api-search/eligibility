---
claim_count: 2
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
  - summary: Unauthorized domains and malicious certificates
    text: Issue certificates for domains or systems you do not own or control
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use Certman, you must create an account using a supported authentication provider (Google, GitHub, or Apple).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Certman
provenance_date: '2026-11-09'
provider_name: Certman
provider_slug: certman-app
slug: certman-app-eligibility
source_date: '2026-11-09'
source_filename: certman-app-eligibility.yml
source_heading: Eligibility
source_page: https://certman.app/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Certman\naid: certman-app\nurl: https://certman.app/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unauthorized domains and malicious certificates\n  text: Issue certificates for domains or systems you do not own or control\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use Certman, you must create an account using a supported authentication provider (Google, GitHub, or\n    Apple).\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/certman-app/eligibility/certman-app-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Certman's own page on 2026-11-09.
synthetic: false
tags:
- Certificate Authority
- PKI
- TLS
- Automation
---
