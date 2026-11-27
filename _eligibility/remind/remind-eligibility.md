---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a parent, staff member, student, or guest user, you will only join your school, classes, and/or groups to which you have been added
    type: individual
  minimum_age:
    text: If you are under the age of 18, you must read these Terms of Use with a parent or adult guardian.
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: As a condition of your use of the Subscription Services, you warrant to ParentSquare that you will not use the Subscription Services for any purpose that is unlawful or prohibited by these Terms of Use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: ParentSquare reserves the right to refuse registration of or to cancel a ParentSquare account in its sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Remind
provenance_date: '2026-11-10'
provider_name: Remind
provider_slug: remind
slug: remind-eligibility
source_date: '2026-11-10'
source_filename: remind-eligibility.yml
source_heading: Eligibility
source_page: https://www.remind.com/terms/parentsquare-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Remind\naid: remind\nurl: https://www.remind.com/terms/parentsquare-terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a parent, staff member, student, or guest user, you will only join your school, classes, and/or\n    groups to which you have been added\nrestricted_uses:\n- summary: Lawful use only\n  text: As a condition of your use of the Subscription Services, you warrant to ParentSquare that you will not use\n    the Subscription Services for any purpose that is unlawful or prohibited by these Terms of Use.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: ParentSquare reserves the right to refuse registration of or to cancel a ParentSquare account in its sole\n    discretion.\nminimum_age:\n  value: null\n  text: If you are under the age of 18, you must read these Terms of Use with a parent or adult guardian.\n"
source_yaml_url: https://artifacts.apis.io/remind/eligibility/remind-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Remind's own page on 2026-11-10.
synthetic: false
tags:
- Messaging
- Communications
- Education
- K-12
- School Communication
- Parent Engagement
- Teacher Messaging
- SMS
- Translation
- OAuth
- Webhook
- Share SDK
- ParentSquare
- Authentication
---
