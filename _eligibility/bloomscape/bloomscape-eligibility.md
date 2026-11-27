---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 16 years of age; if you are a child under 16 years of age, please do not attempt to register for or otherwise use the Services
    value: '16'
  restricted_uses:
  - summary: Use only where lawful
    text: If your use of the Services or Products is prohibited by applicable laws, then you aren’t authorized to use the Services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Bloomscape reserves the right to request further identification for credit card processing on any order you place with us.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bloomscape
provenance_date: '2026-11-09'
provider_name: Bloomscape
provider_slug: bloomscape
slug: bloomscape-eligibility
source_date: '2026-11-09'
source_filename: bloomscape-eligibility.yml
source_heading: Eligibility
source_page: https://bloomscape.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloomscape\naid: bloomscape\nurl: https://bloomscape.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\nrestricted_uses:\n- summary: Use only\
  \ where lawful\n  text: If your use of the Services or Products is prohibited by applicable laws, then you aren’t authorized to\n    use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Bloomscape reserves the right to request further identification for credit card processing on any order\n    you place with us.\nminimum_age:\n  value: '16'\n  text: We do not knowingly collect or solicit personally identifiable information from children under 16 years\n    of age; if you are a child under 16 years of age, please do not attempt to register for or otherwise use the\n    Services\n"
source_yaml_url: https://artifacts.apis.io/bloomscape/eligibility/bloomscape-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Bloomscape's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Houseplants
- E-Commerce
- Direct to Consumer
- Gardening
- Retail
---
