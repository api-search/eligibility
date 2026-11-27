---
api_specs:
- filename: accountexecutivejobs-com-jobs-api-openapi.yml
  format: yaml
  label: AccountExecutiveJobs.com Jobs API
  slug: accountexecutivejobs-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accountexecutivejobs-com/openapi/accountexecutivejobs-com-jobs-api-openapi.yml
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
  - summary: Scams, spam, unlawful hiring
    text: Use the site for scams, phishing, spam, or unlawful hiring practices.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Employer job submissions may remain private until human review and approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AccountExecutiveJobs.com
provenance_date: '2026-11-09'
provider_name: AccountExecutiveJobs.com
provider_slug: accountexecutivejobs-com
slug: accountexecutivejobs-com-eligibility
source_date: '2026-11-09'
source_filename: accountexecutivejobs-com-eligibility.yml
source_heading: Eligibility
source_page: https://accountexecutivejobs.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AccountExecutiveJobs.com\naid: accountexecutivejobs-com\nurl: https://accountexecutivejobs.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Scams, spam, unlawful hiring\n  text: Use the site for scams, phishing, spam, or unlawful hiring practices.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Employer job submissions may remain private until human review and approval.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/accountexecutivejobs-com/eligibility/accountexecutivejobs-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from AccountExecutiveJobs.com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Job Board
- Sales
- Hiring
- Software-as-a-Service
- B2B
---
