---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A consumer is an individual acting mainly outside their trade, business, or profession.
    type: individual
  - text: If you have a separately signed business agreement with us, that agreement takes precedence over these Terms where they conflict.
    type: business
  minimum_age:
    text: You must be 13 or older to use the Services.
    value: '13'
  restricted_uses:
  - summary: Illicit or illegal use
    text: you won't use Diggle for anything illicit or illegal
  - summary: Automated decisions with significant effect
    text: use AI Features for automated decisions that have a legal or similarly significant effect on a person.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A valid credit card is required for paid accounts; other payment methods can be arranged with our team.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Diggle
provenance_date: '2026-11-09'
provider_name: Diggle
provider_slug: diggle
slug: diggle-eligibility
source_date: '2026-11-09'
source_filename: diggle-eligibility.yml
source_heading: Eligibility
source_page: https://diggle.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Diggle\naid: diggle\nurl: https://diggle.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A consumer is an individual acting mainly outside their trade, business, or profession.\n- type: business\n  text: If you have a separately signed business agreement with us, that agreement takes precedence over these Terms\n    where they conflict.\nrestricted_uses:\n- summary: Illicit or illegal use\n  text: you won't use Diggle for anything illicit or illegal\n- summary: Automated decisions with significant effect\n  text:\
  \ use AI Features for automated decisions that have a legal or similarly significant effect on a person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A valid credit card is required for paid accounts; other payment methods can be arranged with our team.\nminimum_age:\n  value: '13'\n  text: You must be 13 or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/diggle/eligibility/diggle-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Diggle's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- Collaboration
- Surveys
- Software-as-a-Service
---
