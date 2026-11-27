---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this website for use only by persons located in the United States.
  entity_types:
  - text: if you're agreeing to this Agreement on behalf of an organization or entity, you represent and warrant that you are authorized to agree to this Agreement on the organization or entity's behalf
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No emergency use
    text: Do not use the website for emergency medical or mental health needs.
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
name: Manatee
provenance_date: '2026-11-10'
provider_name: Manatee
provider_slug: manatee
slug: manatee-eligibility
source_date: '2026-11-10'
source_filename: manatee-eligibility.yml
source_heading: Eligibility
source_page: https://www.getmanatee.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Manatee\naid: manatee\nurl: https://www.getmanatee.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this website for use only by persons located in the United States.\nentity_types:\n- type: business\n  text: if you're agreeing to this Agreement on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to this Agreement on the organization or entity's behalf\nrestricted_uses:\n- summary: No emergency use\n  text: Do not use the website for emergency medical or mental health needs.\nverification:\n \
  \ kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/manatee/eligibility/manatee-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Manatee's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Mental Health
- Telehealth
- Therapy
- Family Care
- Digital Health
---
