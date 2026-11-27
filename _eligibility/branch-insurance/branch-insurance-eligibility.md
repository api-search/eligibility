---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Branch is a licensed insurance producer in the states where Branch offers its products and services
  entity_types:
  - text: includes you personally
    type: individual
  - text: if you are using this website on behalf of the company or organization on whose behalf we grant you access, such company and organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial purposes
    text: Use the Site for any commercial purpose or the benefit of any third party, except as otherwise explicitly permitted for you by Branch
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Applications are subject to underwriting review and approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Branch
provenance_date: '2026-11-09'
provider_name: Branch
provider_slug: branch-insurance
slug: branch-insurance-eligibility
source_date: '2026-11-09'
source_filename: branch-insurance-eligibility.yml
source_heading: Eligibility
source_page: https://www.ourbranch.com/s/blog/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Branch\naid: branch-insurance\nurl: https://www.ourbranch.com/s/blog/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Branch is a licensed insurance producer in the states where Branch offers its products and services\nentity_types:\n- type: individual\n  text: includes you personally\n- type: business\n  text: if you are using this website on behalf of the company or organization on whose behalf we grant you access,\n    such company and organization\nrestricted_uses:\n- summary: Commercial purposes\n  text: Use the Site for any commercial purpose or the benefit of any\
  \ third party, except as otherwise explicitly\n    permitted for you by Branch\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Applications are subject to underwriting review and approval.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/branch-insurance/eligibility/branch-insurance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Branch's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Home Insurance
- Auto Insurance
- Umbrella Insurance
- Bundled Insurance
- Insurtech
- Reciprocal Exchange
- Embedded Insurance
- Quote to Bind
- GraphQL
- Partner API
- Affinity
- Mortgage
- Columbus Ohio
- Renters Insurance
---
