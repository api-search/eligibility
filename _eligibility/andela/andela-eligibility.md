---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: If you are under the age of 18 you may not register or use our Services.
    value: '18'
  restricted_uses:
  - summary: Violations and prohibited content
    text: Violates any law or regulation, including, without limitation, any applicable export control laws, privacy laws
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
name: Andela
provenance_date: '2026-11-09'
provider_name: Andela
provider_slug: andela
slug: andela-eligibility
source_date: '2026-11-09'
source_filename: andela-eligibility.yml
source_heading: Eligibility
source_page: https://www.andela.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Andela\naid: andela\nurl: https://www.andela.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\nrestricted_uses:\n- summary: Violations and prohibited content\n  text: Violates any law or regulation, including, without limitation, any applicable export control laws, privacy\n    laws\nverification:\n  kyc: null\n  kyb: null\n \
  \ approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under the age of 18 you may not register or use our Services.\n"
source_yaml_url: https://artifacts.apis.io/andela/eligibility/andela-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Andela's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Talent
- Artificial Intelligence
- Engineering
- Staffing
- Remote Work
- Developer Talent
- Recruiting
---
