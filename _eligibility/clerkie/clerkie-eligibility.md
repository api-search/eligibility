---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: You represent and warrant that you are [an individual] of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Services
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization or entity’s behalf
    type: business
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 13
    value: null
  restricted_uses:
  - summary: Non-commercial use only
    text: You will only use the Services for your own internal, non-commercial use
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
name: Clerkie
provenance_date: '2026-11-09'
provider_name: Clerkie
provider_slug: clerkie
slug: clerkie-eligibility
source_date: '2026-11-09'
source_filename: clerkie-eligibility.yml
source_heading: Eligibility
source_page: https://s3-us-west-2.amazonaws.com/clerkie-legal/Henry+Labs+-+Terms+of+Use.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clerkie\naid: clerkie\nurl: https://s3-us-west-2.amazonaws.com/clerkie-legal/Henry+Labs+-+Terms+of+Use.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo, or\n    that has been designated by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: You represent and warrant that you are [an individual] of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Services\n- type:\
  \ business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization or entity’s behalf\nrestricted_uses:\n- summary: Non-commercial use only\n  text: You will only use the Services for your own internal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: We do not knowingly collect or solicit personally identifiable information from children under 13\n"
source_yaml_url: https://artifacts.apis.io/clerkie/eligibility/clerkie-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Clerkie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Debt Management
- Lending
- Loan Servicing
- Debt Collection
- Payments
- Credit
- Financial Services
- Personal Finance
- AI Agents
- Consumer Finance
---
