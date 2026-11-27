---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An individual may access and/or use the Service on behalf of a company or other entity, such as that individual's employer (such entity, an "Organization").
    type: business
  minimum_age:
    text: any access to, or use of, the Service by anyone who is a minor (which is under the age of 18 in most jurisdictions) in any applicable jurisdiction (a "Minor") is strictly prohibited and in violation of these Terms, unless such access and/or use is supervised by a parent or legal guardian
    value: '18'
  restricted_uses:
  - summary: Automated actions without review
    text: The Service includes features that automatically execute browser actions and code without manual review or confirmation.
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
name: Composite
provenance_date: '2026-11-09'
provider_name: Composite
provider_slug: composite
slug: composite-eligibility
source_date: '2026-11-09'
source_filename: composite-eligibility.yml
source_heading: Eligibility
source_page: https://composite.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Composite\naid: composite\nurl: https://composite.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: An individual may access and/or use the Service on behalf of a company or other entity, such as that individual's\n    employer (such entity, an \"Organization\").\nrestricted_uses:\n- summary: Automated actions without review\n  text: The Service includes features that automatically execute browser actions and code without manual review\n    or confirmation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: any access to, or use of, the Service by anyone who is a minor (which is under the age of 18 in most jurisdictions)\n    in any applicable jurisdiction (a \"Minor\") is strictly prohibited and in violation of these Terms, unless such\n    access and/or use is supervised by a parent or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/composite/eligibility/composite-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Composite's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Browser
- Software-as-a-Service
- Productivity
- Company
---
