---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using this Site, you represent, acknowledge and agree that you are at least 18 years of age, or if you are under 18 years of age but are at least 13 years old (a “Minor”), that you are using the Site with the consent of your parent or legal guardian
    type: individual
  - text: If you are accessing the Site on behalf of a company or other legal entity (“Entity”), you represent that you are authorized to act on behalf of the Entity and to bind such Entity to these Terms.
    type: business
  minimum_age:
    text: If you are not at least 13 years old, you may not use the Site at any time or in any manner or submit any information to the Company or the Site.
    value: '13'
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
name: Truvian
provenance_date: '2026-11-10'
provider_name: Truvian
provider_slug: truvianhealth-com
slug: truvianhealth-com-eligibility
source_date: '2026-11-10'
source_filename: truvianhealth-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.truvianhealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Truvian\naid: truvianhealth-com\nurl: https://www.truvianhealth.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using this Site, you represent, acknowledge and agree that you are at least 18 years of age, or if you\n    are under 18 years of age but are at least 13 years old (a “Minor”), that you are using the Site with the consent\n    of your parent or legal guardian\n- type: business\n  text: If you are accessing the Site on behalf of a company or other legal entity (“Entity”), you represent that\n    you are\
  \ authorized to act on behalf of the Entity and to bind such Entity to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are not at least 13 years old, you may not use the Site at any time or in any manner or submit any\n    information to the Company or the Site.\n"
source_yaml_url: https://artifacts.apis.io/truvianhealth-com/eligibility/truvianhealth-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Truvian's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health Tech
- Diagnostics
- Point of Care
- FDA Cleared
---
