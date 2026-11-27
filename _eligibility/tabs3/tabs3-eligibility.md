---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - IR
    - SY
    - SD
    - LY
    - CU
    - KP
    served: []
    text: You are not a citizen of, or located within, an embargoed or otherwise restricted nation (including without limitation Iran, Syria, Sudan, Libya, Cuba, and North Korea)
  entity_types:
  - text: 'To be eligible to use the Services, you represent and warrant that you: (i) are at least 18 years of age or otherwise over the age of majority in the jurisdiction in which you reside'
    type: individual
  - text: If you are using the Services on behalf of a company or other legal entity, you hereby represent and warrant that you have the authority to enter into these Terms on behalf of such entity.
    type: business
  minimum_age:
    text: are at least 18 years of age or otherwise over the age of majority in the jurisdiction in which you reside
    value: '18'
  restricted_uses:
  - summary: Emergency services via SMS
    text: Using Law Ruler numbers to provide emergency services, such as 911-types of communication
  - summary: Unsolicited or bulk marketing SMS
    text: Sending mass marketing or bulk messaging using Law Ruler long code phone numbers
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- IR
- SY
- SD
- LY
- CU
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tabs3
provenance_date: '2026-11-10'
provider_name: Tabs3
provider_slug: tabs3
slug: tabs3-eligibility
source_date: '2026-11-10'
source_filename: tabs3-eligibility.yml
source_heading: Eligibility
source_page: https://www.tabs3.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tabs3\naid: tabs3\nurl: https://www.tabs3.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - IR\n  - SY\n  - SD\n  - LY\n  - CU\n  - KP\n  text: You are not a citizen of, or located within, an embargoed or otherwise restricted nation (including without\n    limitation Iran, Syria, Sudan, Libya, Cuba, and North Korea)\nentity_types:\n- type: individual\n  text: 'To be eligible to use the Services, you represent and warrant that you: (i) are at least 18 years of age\n    or otherwise over the age of majority in the jurisdiction in which you reside'\n- type: business\n \
  \ text: If you are using the Services on behalf of a company or other legal entity, you hereby represent and warrant\n    that you have the authority to enter into these Terms on behalf of such entity.\nrestricted_uses:\n- summary: Emergency services via SMS\n  text: Using Law Ruler numbers to provide emergency services, such as 911-types of communication\n- summary: Unsolicited or bulk marketing SMS\n  text: Sending mass marketing or bulk messaging using Law Ruler long code phone numbers\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: are at least 18 years of age or otherwise over the age of majority in the jurisdiction in which you reside\n"
source_yaml_url: https://artifacts.apis.io/tabs3/eligibility/tabs3-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Tabs3's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Legal Tech
- Practice Management
- Cloud Software
---
