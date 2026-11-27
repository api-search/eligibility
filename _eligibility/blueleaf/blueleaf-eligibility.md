---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no claims concerning whether Blueleaf.com may be downloaded, viewed, or be appropriate for use outside of the United States.
  entity_types:
  - text: If you are using the Services on behalf of an organization, you are agreeing to these terms for that organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: You are only entitled to access and use Blueleaf for lawful purposes.
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
name: BlueLeaf
provenance_date: '2026-11-09'
provider_name: BlueLeaf
provider_slug: blueleaf
slug: blueleaf-eligibility
source_date: '2026-11-09'
source_filename: blueleaf-eligibility.yml
source_heading: Eligibility
source_page: https://www.blueleaf.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BlueLeaf\naid: blueleaf\nurl: https://www.blueleaf.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no claims concerning whether Blueleaf.com may be downloaded, viewed, or be appropriate for use outside\n    of the United States.\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of an organization, you are agreeing to these terms for that organization\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You are only entitled to access and use Blueleaf for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/blueleaf/eligibility/blueleaf-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from BlueLeaf's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wealth Management
- Fintech
- Financial Advisors
- Investment Reporting
- Account Aggregation
- Client Portal
- OAuth
- Authentication
---
