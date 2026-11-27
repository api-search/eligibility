---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An individual may access and/or use the Service on behalf of a company or other entity, such as that individual’s employer (such entity, an “Organization”).
    type: business
  minimum_age:
    text: any access to, or use of, the Service by anyone who is a minor (which is under the age of 18 in most jurisdictions) in any applicable jurisdiction (a “Minor”) is strictly prohibited and in violation of these Terms, unless such access and/or use is supervised by a parent or legal guardian
    value: '18'
  restricted_uses:
  - summary: Minors
    text: any access to, or use of, the Service by anyone who is a minor (which is under the age of 18 in most jurisdictions) in any applicable jurisdiction (a “Minor”) is strictly prohibited
  - summary: Automated agents and bots
    text: use any robot, spider, scraper, off-line reader, data mining tool, data gathering or extraction tool, or any other automated means to access the Service
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
name: Paradigm
provenance_date: '2026-11-10'
provider_name: Paradigm
provider_slug: paradigmai-com
slug: paradigmai-com-eligibility
source_date: '2026-11-10'
source_filename: paradigmai-com-eligibility.yml
source_heading: Eligibility
source_page: https://paradigmai.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paradigm\naid: paradigmai-com\nurl: https://paradigmai.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: An individual may access and/or use the Service on behalf of a company or other entity, such as that individual’s\n    employer (such entity, an “Organization”).\nrestricted_uses:\n- summary: Minors\n  text: any access to, or use of, the Service by anyone who is a minor (which is under the age of 18 in most jurisdictions)\n    in any applicable jurisdiction (a “Minor”) is strictly prohibited\n- summary:\
  \ Automated agents and bots\n  text: use any robot, spider, scraper, off-line reader, data mining tool, data gathering or extraction tool, or\n    any other automated means to access the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: any access to, or use of, the Service by anyone who is a minor (which is under the age of 18 in most jurisdictions)\n    in any applicable jurisdiction (a “Minor”) is strictly prohibited and in violation of these Terms, unless such\n    access and/or use is supervised by a parent or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/paradigmai-com/eligibility/paradigmai-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Paradigm's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Go-To-Market
- Automation
- Analytics
---
