---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are agreeing to these Terms or using the Yesware Services on behalf of your employer, your acceptance of these Terms is deemed an agreement between your employer and Yesware
    type: business
  minimum_age:
    text: You agree that you will not use the Yesware Services if you are under the age of majority in your place of residence or otherwise not fully able and competent to agree to these Terms.
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: You agree that you will not export or re-export, directly or indirectly, the Yesware Services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'Registration: Unless you are visiting only the public areas of the Site, you are required to register and create an account to use the Yesware Services'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Yesware
provenance_date: '2026-11-10'
provider_name: Yesware
provider_slug: yesware
slug: yesware-eligibility
source_date: '2026-11-10'
source_filename: yesware-eligibility.yml
source_heading: Eligibility
source_page: https://www.yesware.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yesware\naid: yesware\nurl: https://www.yesware.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are agreeing to these Terms or using the Yesware Services on behalf of your employer, your acceptance\n    of these Terms is deemed an agreement between your employer and Yesware\nrestricted_uses:\n- summary: Export restrictions\n  text: You agree that you will not export or re-export, directly or indirectly, the Yesware Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'Registration: Unless\
  \ you are visiting only the public areas of the Site, you are required to register and\n    create an account to use the Yesware Services'\nminimum_age:\n  value: null\n  text: You agree that you will not use the Yesware Services if you are under the age of majority in your place\n    of residence or otherwise not fully able and competent to agree to these Terms.\n"
source_yaml_url: https://artifacts.apis.io/yesware/eligibility/yesware-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Yesware's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sales Engagement
- Email Tracking
- Sales Productivity
- CRM
- Salesforce
- Outreach
- Email Marketing
- Sales Enablement
- Gmail
- Outlook
---
