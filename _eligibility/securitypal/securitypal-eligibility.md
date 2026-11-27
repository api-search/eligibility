---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF AN INDIVIDUAL IS ENTERING INTO THIS AGREEMENT ON BEHALF OF A LEGAL ENTITY, SUCH PERSON REPRESENTS AND WARRANTS THAT IT HAS THE LEGAL AUTHORITY TO BIND SUCH LEGAL ENTITY TO THIS AGREEMENT
    type: business
  minimum_age:
    text: THE SERVICES ARE INTENDED FOR THE CLIENT AND ITS AUTHORIZED USERS ONLY AND ARE NOT FOR USE BY CHILDREN UNDER 13 YEARS OF AGE.
    value: '13'
  restricted_uses:
  - summary: Viruses, spam or destructive items
    text: use or access the Software to submit or transmit any computer viruses, worms, defects, Trojan horses or other items of a destructive nature or to send any commercial solicitation or spam
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
name: SecurityPal
provenance_date: '2026-11-10'
provider_name: SecurityPal
provider_slug: securitypal
slug: securitypal-eligibility
source_date: '2026-11-10'
source_filename: securitypal-eligibility.yml
source_heading: Eligibility
source_page: https://www.securitypalhq.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SecurityPal\naid: securitypal\nurl: https://www.securitypalhq.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF AN INDIVIDUAL IS ENTERING INTO THIS AGREEMENT ON BEHALF OF A LEGAL ENTITY, SUCH PERSON REPRESENTS AND\n    WARRANTS THAT IT HAS THE LEGAL AUTHORITY TO BIND SUCH LEGAL ENTITY TO THIS AGREEMENT\nrestricted_uses:\n- summary: Viruses, spam or destructive items\n  text: use or access the Software to submit or transmit any computer viruses, worms, defects, Trojan horses or\n    other items of a destructive nature\
  \ or to send any commercial solicitation or spam\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: THE SERVICES ARE INTENDED FOR THE CLIENT AND ITS AUTHORIZED USERS ONLY AND ARE NOT FOR USE BY CHILDREN UNDER\n    13 YEARS OF AGE.\n"
source_yaml_url: https://artifacts.apis.io/securitypal/eligibility/securitypal-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from SecurityPal's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Compliance
- GRC
- Vendor Risk
- Trust Center
- Questionnaire Automation
- Cybersecurity
---
