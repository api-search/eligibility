---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: A User may not use the Site and the Platform if the User is a person barred from using the Site or the Platform under the laws of the United States or other countries including the country in which you are resident or from which you use the Site and/or the Platform.
  entity_types:
  - text: 'If you are a User, then you hereby warrant the following: (i) you are over 18 years of age'
    type: individual
  - text: if you are a corporation, the corporation is valid and allowed to enter into this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No accounts for others
    text: Create an account for anyone other than yourself (a real person).
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Subject to applicable law, Mobilize may, in its sole discretion, refuse to offer the Site and the Platform to any person or entity and change its eligibility criteria at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mobilize
provenance_date: '2026-11-10'
provider_name: Mobilize
provider_slug: mobilize
slug: mobilize-eligibility
source_date: '2026-11-10'
source_filename: mobilize-eligibility.yml
source_heading: Eligibility
source_page: https://www.forj.ai/mobilize-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mobilize\naid: mobilize\nurl: https://www.forj.ai/mobilize-terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: A User may not use the Site and the Platform if the User is a person barred from using the Site or the Platform\n    under the laws of the United States or other countries including the country in which you are resident or from\n    which you use the Site and/or the Platform.\nentity_types:\n- type: individual\n  text: 'If you are a User, then you hereby warrant the following: (i) you are over 18 years of age'\n- type: business\n  text: if you are a corporation,\
  \ the corporation is valid and allowed to enter into this Agreement.\nrestricted_uses:\n- summary: No accounts for others\n  text: Create an account for anyone other than yourself (a real person).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Subject to applicable law, Mobilize may, in its sole discretion, refuse to offer the Site and the Platform\n    to any person or entity and change its eligibility criteria at any time.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mobilize/eligibility/mobilize-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Mobilize's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Community
- Learning
- Associations
- Membership
- LMS
- Member Engagement
- Professional Networks
---
