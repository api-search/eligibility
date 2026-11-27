---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF CUSTOMER IS ENTERING INTO THIS AGREEMENT ON BEHALF OF OTHER COMPANIES OR ENTITIES (FOR INSTANCE, AS AN AGENCY OR AUTHORIZED RESELLER), THEN CUSTOMER REPRESENTS AND WARRANTS THAT IT HAS THE AUTHORITY TO BIND SUCH COMPANIES AND ENTITIES TO THIS AGREEMENT.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No child-directed sites
    text: 'Customer is expressly prohibited from: Placing Technology (e.g., NextRoll pixel) on any Customer Sites that are directed (in whole or in part) to children under the age of sixteen (16)'
  - summary: No sensitive personal information
    text: 'Customer is expressly prohibited from: Providing NextRoll with or permitting NextRoll to collect any Sensitive Personal Information'
  - source: https://www.nextroll.com/terms/api
    summary: Malicious, hateful or offensive applications
    text: 'Company will not use the NextRoll APIs for any application that constitutes, promotes or is used in connection with: spyware, adware, or any other malicious programs or code; unsolicited mass distribution of email (spam); hate materials; libelous, defamatory, obscene, abusive or otherwise offensive content;'
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
name: AdRoll
provenance_date: '2026-11-09'
provider_name: AdRoll
provider_slug: adroll
slug: adroll-eligibility
source_date: '2026-11-09'
source_filename: adroll-eligibility.yml
source_heading: Eligibility
source_page: https://www.nextroll.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdRoll\naid: adroll\nurl: https://www.nextroll.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.nextroll.com/terms\n  - https://www.nextroll.com/terms/api\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF CUSTOMER IS ENTERING INTO THIS AGREEMENT ON BEHALF OF OTHER COMPANIES OR ENTITIES (FOR INSTANCE, AS AN\n    AGENCY OR AUTHORIZED RESELLER), THEN CUSTOMER REPRESENTS AND WARRANTS THAT IT HAS THE AUTHORITY TO BIND SUCH\n    COMPANIES AND ENTITIES TO THIS AGREEMENT.\nrestricted_uses:\n- summary: No child-directed sites\n  text: 'Customer is expressly\
  \ prohibited from: Placing Technology (e.g., NextRoll pixel) on any Customer Sites\n    that are directed (in whole or in part) to children under the age of sixteen (16)'\n- summary: No sensitive personal information\n  text: 'Customer is expressly prohibited from: Providing NextRoll with or permitting NextRoll to collect any Sensitive\n    Personal Information'\n- summary: Malicious, hateful or offensive applications\n  text: 'Company will not use the NextRoll APIs for any application that constitutes, promotes or is used in connection\n    with: spyware, adware, or any other malicious programs or code; unsolicited mass distribution of email (spam);\n    hate materials; libelous, defamatory, obscene, abusive or otherwise offensive content;'\n  source: https://www.nextroll.com/terms/api\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adroll/eligibility/adroll-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from AdRoll's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Display Advertising
- Retargeting
- Marketing
- AdTech
- Programmatic
---
