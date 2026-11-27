---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Clipboard offers the Site and Services for your business purposes only and not for personal, household, or consumer use.
    type: business
  - text: are either a legal entity or an individual who is 18 years or older (or have otherwise reached the age of majority in the jurisdiction in which you conduct business)
    type: individual
  minimum_age:
    text: an individual who is 18 years or older (or have otherwise reached the age of majority in the jurisdiction in which you conduct business)
    value: '18'
  restricted_uses:
  - summary: Business use only
    text: Clipboard offers the Site and Services for your business purposes only and not for personal, household, or consumer use.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: When you register for an Account and from time to time thereafter, your Account will be subject to verification, including, but not limited to, validation against third-party databases or the verification of one or more official government or legal documents that confirm your identity
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clipboard Health
provenance_date: '2026-11-09'
provider_name: Clipboard Health
provider_slug: clipboardhealth-com
slug: clipboardhealth-com-eligibility
source_date: '2026-11-09'
source_filename: clipboardhealth-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.clipboard.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clipboard Health\naid: clipboardhealth-com\nurl: https://www.clipboard.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Clipboard offers the Site and Services for your business purposes only and not for personal, household,\n    or consumer use.\n- type: individual\n  text: are either a legal entity or an individual who is 18 years or older (or have otherwise reached the age of\n    majority in the jurisdiction in which you conduct business)\nrestricted_uses:\n- summary: Business use only\n  text: Clipboard offers\
  \ the Site and Services for your business purposes only and not for personal, household,\n    or consumer use.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: When you register for an Account and from time to time thereafter, your Account will be subject to verification,\n    including, but not limited to, validation against third-party databases or the verification of one or more official\n    government or legal documents that confirm your identity\nminimum_age:\n  value: '18'\n  text: an individual who is 18 years or older (or have otherwise reached the age of majority in the jurisdiction\n    in which you conduct business)\n"
source_yaml_url: https://artifacts.apis.io/clipboardhealth-com/eligibility/clipboardhealth-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Clipboard Health's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Staffing
- On-Demand
- Platform
- Workforce
---
