---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Site
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 16 years of age
    value: '16'
  restricted_uses:
  - summary: No use on behalf of third parties
    text: and not on behalf of or for the benefit of any third party
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
name: Amogy
provenance_date: '2026-11-09'
provider_name: Amogy
provider_slug: amogy
slug: amogy-eligibility
source_date: '2026-11-09'
source_filename: amogy-eligibility.yml
source_heading: Eligibility
source_page: https://amogy.co/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amogy\naid: amogy\nurl: https://amogy.co/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Site\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\nrestricted_uses:\n- summary:\
  \ No use on behalf of third parties\n  text: and not on behalf of or for the benefit of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: We do not knowingly collect or solicit personally identifiable information from children under 16 years\n    of age\n"
source_yaml_url: https://artifacts.apis.io/amogy/eligibility/amogy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Amogy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Clean Energy
- Ammonia
- Decarbonization
- Hydrogen
- Power Generation
- Maritime
- Sustainability
---
