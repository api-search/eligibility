---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: if you are located in any member state that is part of the European Economic Area or any member state that has adopted the General Data Protection Regulation, you are not permitted to use the Platform and you are not permitted to provide any personal data to us.
  minimum_age:
    text: Use of the Platform by anyone under the age of 13 is prohibited.
    value: '13'
  restricted_uses:
  - summary: Unlawful or high-risk activities
    text: (ii) any activity that we deem, in our sole discretion, may be associated with a high level of risk, may create liability for us or may cause us to lose the services of any of our third-party service providers.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require you to provide information to confirm your identity and help ensure the security of your Platform account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clutch
provenance_date: '2026-11-10'
provider_name: Clutch
provider_slug: withclutch
slug: withclutch-eligibility
source_date: '2026-11-10'
source_filename: withclutch-eligibility.yml
source_heading: Eligibility
source_page: https://withclutch.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clutch\naid: withclutch\nurl: https://withclutch.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: if you are located in any member state that is part of the European Economic Area or any member state that\n    has adopted the General Data Protection Regulation, you are not permitted to use the Platform and you are not\n    permitted to provide any personal data to us.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or high-risk activities\n  text: (ii) any activity that we deem, in our sole discretion, may be associated with a high level of risk, may\n\
  \    create liability for us or may cause us to lose the services of any of our third-party service providers.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require you to provide information to confirm your identity and help ensure the security of your\n    Platform account.\nminimum_age:\n  value: '13'\n  text: Use of the Platform by anyone under the age of 13 is prohibited.\n"
source_yaml_url: https://artifacts.apis.io/withclutch/eligibility/withclutch-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Clutch's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Credit Union
- Lending
- Loan Origination
- Account Opening
- Financial Services
- Fintech
- Banking
- Data Export
---
