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
    text: We do not knowingly collect or solicit personally identifiable information from children under 13 years of age; if you are a child under 13 years of age, please do not attempt to register for or otherwise use the Site
    value: '13'
  restricted_uses:
  - summary: Non-commercial use only
    text: You will only use the Site for your own internal, personal, non-commercial use, and not on behalf of or for the benefit of any third party
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
name: Constellaintelligence
provenance_date: '2026-11-09'
provider_name: Constellaintelligence
provider_slug: constellaintelligence
slug: constellaintelligence-eligibility
source_date: '2026-11-09'
source_filename: constellaintelligence-eligibility.yml
source_heading: Eligibility
source_page: https://constella.ai/policies/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Constellaintelligence\naid: constellaintelligence\nurl: https://constella.ai/policies/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Site\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s\
  \ behalf\nrestricted_uses:\n- summary: Non-commercial use only\n  text: You will only use the Site for your own internal, personal, non-commercial use, and not on behalf of or\n    for the benefit of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: We do not knowingly collect or solicit personally identifiable information from children under 13 years\n    of age; if you are a child under 13 years of age, please do not attempt to register for or otherwise use the\n    Site\n"
source_yaml_url: https://artifacts.apis.io/constellaintelligence/eligibility/constellaintelligence-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Constellaintelligence's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Identity
- Data
- Security
---
