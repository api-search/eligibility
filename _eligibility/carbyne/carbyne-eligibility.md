---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not access or use the Website if it is illegal for you to do so.
  entity_types:
  - text: you are authorized to enter into this agreement with us on your behalf or on behalf of the organization you represent
    type: business
  - source: https://carbyne.com/wp-content/uploads/2023/03/Carbyne-API-Terms-of-Use.final_.3.23.23.pdf
    text: If you are accepting these Terms on behalf of a company or other entity, yourepresent andwarrant that youhavetheauthoritytobindthat entitytotheseTerms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purposes
    text: You agree not to use the Website, including any content, information or other intellectual property available on or through the Website, for any unlawful purpose or in any manner which harms any other person.
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
name: Carbyne
provenance_date: '2026-11-09'
provider_name: Carbyne
provider_slug: carbyne
slug: carbyne-eligibility
source_date: '2026-11-09'
source_filename: carbyne-eligibility.yml
source_heading: Eligibility
source_page: https://carbyne.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carbyne\naid: carbyne\nurl: https://carbyne.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://carbyne.com/terms-of-use/\n  - https://carbyne.com/wp-content/uploads/2023/03/Carbyne-API-Terms-of-Use.final_.3.23.23.pdf\ncountries:\n  served: []\n  excluded: []\n  text: You may not access or use the Website if it is illegal for you to do so.\nentity_types:\n- type: business\n  text: you are authorized to enter into this agreement with us on your behalf or on behalf of the organization\n    you represent\n- type: business\n  text: If you are accepting these Terms on behalf of a company or other\
  \ entity, yourepresent andwarrant that youhavetheauthoritytobindthat\n    entitytotheseTerms.\n  source: https://carbyne.com/wp-content/uploads/2023/03/Carbyne-API-Terms-of-Use.final_.3.23.23.pdf\nrestricted_uses:\n- summary: Unlawful purposes\n  text: You agree not to use the Website, including any content, information or other intellectual property available\n    on or through the Website, for any unlawful purpose or in any manner which harms any other person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/carbyne/eligibility/carbyne-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Carbyne's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Emergency Services
- Public Safety
- Communications
- Telecommunications
- NG911
- Contact Center
- Location
- Video
- Government
- Artificial Intelligence
---
