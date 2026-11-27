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
  - summary: Unauthorized scanning
    text: You may only scan assets you own or are explicitly authorized to test.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Domain verification is mandatory before any audit.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hack My Website
provenance_date: '2026-11-09'
provider_name: Hack My Website
provider_slug: hack-my-website
slug: hack-my-website-eligibility
source_date: '2026-11-09'
source_filename: hack-my-website-eligibility.yml
source_heading: Eligibility
source_page: https://hackmywebsite.io/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hack My Website\naid: hack-my-website\nurl: https://hackmywebsite.io/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unauthorized scanning\n  text: You may only scan assets you own or are explicitly authorized to test.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Domain verification is mandatory before any audit.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hack-my-website/eligibility/hack-my-website-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Hack My Website's own page on 2026-11-09.
synthetic: false
tags:
- Application Security
- Web Security
- Vulnerability Scanning
- DAST
- SAST
- Cybersecurity
- AppSec
- DevSecOps
- AI Remediation
- Software-as-a-Service
---
