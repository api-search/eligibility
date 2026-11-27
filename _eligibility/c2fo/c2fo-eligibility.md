---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Sanctioned Jurisdictions are restricted but the page does not list them; arbitration venue varies by US/Canada, India, or other countries.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned persons and jurisdictions
    text: C2FO may terminate this agreement and/or suspend Supplier’s access to the Service immediately, with or without notice, if C2FO believes, in its sole discretion, that Supplier or one of its Affiliates is subject to Sanctions, located in a Sanctioned Jurisdiction
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
name: C2FO
provenance_date: '2026-11-09'
provider_name: C2FO
provider_slug: c2fo
slug: c2fo-eligibility
source_date: '2026-11-09'
source_filename: c2fo-eligibility.yml
source_heading: Eligibility
source_page: https://c2fo.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: C2FO\naid: c2fo\nurl: https://c2fo.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Sanctioned Jurisdictions are restricted but the page does not list them; arbitration venue varies by US/Canada,\n    India, or other countries.\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned persons and jurisdictions\n  text: C2FO may terminate this agreement and/or suspend Supplier’s access to the Service immediately, with or without\n    notice, if C2FO believes, in its sole discretion, that Supplier or one of its Affiliates is subject to Sanctions,\n\
  \    located in a Sanctioned Jurisdiction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/c2fo/eligibility/c2fo-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from C2FO's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Working Capital
- Supply Chain Finance
- Dynamic Discounting
- Invoice Financing
- Cash Flow
- Payments
---
