---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are at least 18 (eighteen) years of age
    type: individual
  - text: If you are using the Platform on behalf of an organization, you are agreeing to the Terms on behalf of that organization
    type: business
  minimum_age:
    text: You represent that you are at least 18 (eighteen) years of age
    value: '18'
  restricted_uses:
  - summary: Under-18 use
    text: use the Services if you are under the age of 18 (eighteen) years;
  - summary: Surveys, contests, pyramid schemes
    text: conduct or forward surveys, contests, pyramid schemes or chain letters involving the Services;
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You agree and provide your express consent to provide certain information and documents that may be necessary to ascertain your eligibility to use the Platform or avail the Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cleartax
provenance_date: '2026-11-09'
provider_name: Cleartax
provider_slug: cleartax
slug: cleartax-eligibility
source_date: '2026-11-09'
source_filename: cleartax-eligibility.yml
source_heading: Eligibility
source_page: https://www.clear.in/meta/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cleartax\naid: cleartax\nurl: https://www.clear.in/meta/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are at least 18 (eighteen) years of age\n- type: business\n  text: If you are using the Platform on behalf of an organization, you are agreeing to the Terms on behalf of that\n    organization\nrestricted_uses:\n- summary: Under-18 use\n  text: use the Services if you are under the age of 18 (eighteen) years;\n- summary: Surveys, contests, pyramid schemes\n  text: conduct or forward\
  \ surveys, contests, pyramid schemes or chain letters involving the Services;\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You agree and provide your express consent to provide certain information and documents that may be necessary\n    to ascertain your eligibility to use the Platform or avail the Services\nminimum_age:\n  value: '18'\n  text: You represent that you are at least 18 (eighteen) years of age\n"
source_yaml_url: https://artifacts.apis.io/cleartax/eligibility/cleartax-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Cleartax's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Tax
- GST
- E-Invoicing
- Compliance
- Fintech
- Accounting
- India
- Financial Automation
- Government
---
