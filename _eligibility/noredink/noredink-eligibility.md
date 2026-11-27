---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are of legal age to form a binding contract
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity (for example, if you’re a teacher agreeing to these Terms on behalf of a school or an administrator agreeing to these Terms on behalf of your district), you represent and warrant that you are authorized to agree to these Terms on that organization or entity’s behalf
    type: business
  minimum_age:
    text: You represent and warrant that you are of legal age to form a binding contract, or If you are not of legal age to form a binding contract (in many jurisdictions, this age is 18), you may only use the Applications with the express consent of and agreement to these Terms by your parent, guardian, school or school district.
    value: null
  restricted_uses:
  - summary: Zero tolerance for offensive content
    text: We have a zero tolerance policy for any Content or User Submission that constitute, in our sole discretion, harassment, racism, defamation, disparagement, obscene content, discrimination, or any other offensive content of any kind.
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
name: NoRedInk
provenance_date: '2026-11-10'
provider_name: NoRedInk
provider_slug: noredink
slug: noredink-eligibility
source_date: '2026-11-10'
source_filename: noredink-eligibility.yml
source_heading: Eligibility
source_page: https://www.noredink.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NoRedInk\naid: noredink\nurl: https://www.noredink.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are of legal age to form a binding contract\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity (for example, if you’re a teacher\n    agreeing to these Terms on behalf of a school or an administrator agreeing to these Terms on behalf of your\n    district), you represent and warrant that you are authorized to agree to these Terms on that organization\
  \ or\n    entity’s behalf\nrestricted_uses:\n- summary: Zero tolerance for offensive content\n  text: We have a zero tolerance policy for any Content or User Submission that constitute, in our sole discretion,\n    harassment, racism, defamation, disparagement, obscene content, discrimination, or any other offensive content\n    of any kind.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent and warrant that you are of legal age to form a binding contract, or If you are not of legal\n    age to form a binding contract (in many jurisdictions, this age is 18), you may only use the Applications with\n    the express consent of and agreement to these Terms by your parent, guardian, school or school district.\n"
source_yaml_url: https://artifacts.apis.io/noredink/eligibility/noredink-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from NoRedInk's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- English Language Arts
- Grammar
- Writing
- Literacy
- K-12
- OAuth
- SSO
- Rostering
- Identity
- Authentication
---
