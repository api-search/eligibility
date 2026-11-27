---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The use of MeWe is for all persons age 18 and over who agree to these Terms of Service.
    type: individual
  minimum_age:
    text: The use of MeWe is for all persons age 18 and over who agree to these Terms of Service.
    value: '18'
  restricted_uses:
  - summary: Spam and bulk unsolicited messaging
    text: Collect e-mail addresses or other contact information of other users by electronic or other means for the purpose of sending unsolicited or unauthorized advertising or commercial communications, such as spam.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to verify your identity before you can receive a Payout.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MeWe
provenance_date: '2026-11-10'
provider_name: MeWe
provider_slug: mewe
slug: mewe-eligibility
source_date: '2026-11-10'
source_filename: mewe-eligibility.yml
source_heading: Eligibility
source_page: https://mewe.com/cms/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MeWe\naid: mewe\nurl: https://mewe.com/cms/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The use of MeWe is for all persons age 18 and over who agree to these Terms of Service.\nrestricted_uses:\n- summary: Spam and bulk unsolicited messaging\n  text: Collect e-mail addresses or other contact information of other users by electronic or other means for the\n    purpose of sending unsolicited or unauthorized advertising or commercial communications, such as spam.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: You may be required to verify your identity before you can receive a Payout.\nminimum_age:\n  value: '18'\n  text: The use of MeWe is for all persons age 18 and over who agree to these Terms of Service.\n"
source_yaml_url: https://artifacts.apis.io/mewe/eligibility/mewe-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from MeWe's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social
- Privacy
- Networking
- Communications
---
