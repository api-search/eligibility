---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Companies (Company): Employers, human resources specialists (HR), company administrators'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purposes
    text: not to use the Platform for unlawful purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The User may create an account only with a corporate email
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GLORRI
provenance_date: '2026-11-09'
provider_name: GLORRI
provider_slug: glorri-inc
slug: glorri-inc-eligibility
source_date: '2026-11-09'
source_filename: glorri-inc-eligibility.yml
source_heading: Eligibility
source_page: https://glorri.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GLORRI\naid: glorri-inc\nurl: https://glorri.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'Companies (Company): Employers, human resources specialists (HR), company administrators'\nrestricted_uses:\n- summary: Unlawful purposes\n  text: not to use the Platform for unlawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The User may create an account only with a corporate email\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/glorri-inc/eligibility/glorri-inc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from GLORRI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Human Resources
- Recruiting
- Applicant Tracking
- Talent Acquisition
- Hiring
- Recruiting Automation
- Software-as-a-Service
---
