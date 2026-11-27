---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Personal Accounts
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal, fraudulent or defamatory purpose
    text: 'You shall not: use the services for an illegal, fraudulent, or defamatory purpose'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Your request for The Services is approved by Us
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: First Nations Bank of Canada
provenance_date: '2026-11-09'
provider_name: First Nations Bank of Canada
provider_slug: first-nations-bank-of-canada
slug: first-nations-bank-of-canada-eligibility
source_date: '2026-11-09'
source_filename: first-nations-bank-of-canada-eligibility.yml
source_heading: Eligibility
source_page: https://www.fnbc.ca/about/regulatory/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: First Nations Bank of Canada\naid: first-nations-bank-of-canada\nurl: https://www.fnbc.ca/about/regulatory/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Personal Accounts\nrestricted_uses:\n- summary: Illegal, fraudulent or defamatory purpose\n  text: 'You shall not: use the services for an illegal, fraudulent, or defamatory purpose'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Your request for The Services is approved by Us\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/first-nations-bank-of-canada/eligibility/first-nations-bank-of-canada-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from First Nations Bank of Canada's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Banking
- Canada
- Schedule I Bank
- Indigenous
- Consumer-Driven Banking
- Interac
---
