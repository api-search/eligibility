---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You have to be 18 years of age or older to use the Services and live within the United States.
  entity_types:
  - text: The Terms describe the commitments we make to you if you are an Authorized User (either a current or prospective applicant for insurance, also referred to as a “Consumer,” or an Agent or Broker)
    type: individual
  - text: If you are using the Services on behalf of an entity, organization or company, you need to have the authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You have to be 18 years of age or older to use the Services and live within the United States.
    value: '18'
  restricted_uses:
  - summary: No information about minors
    text: You are not permitted to enter any information about a minor anywhere on the Services unless you are that minor’s legal guardian and consent to the practices described in these Terms on behalf of that minor.
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
name: Stride Health
provenance_date: '2026-11-10'
provider_name: Stride Health
provider_slug: stride-health
slug: stride-health-eligibility
source_date: '2026-11-10'
source_filename: stride-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.stridehealth.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stride Health\naid: stride-health\nurl: https://www.stridehealth.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You have to be 18 years of age or older to use the Services and live within the United States.\nentity_types:\n- type: individual\n  text: The Terms describe the commitments we make to you if you are an Authorized User (either a current or prospective\n    applicant for insurance, also referred to as a “Consumer,” or an Agent or Broker)\n- type: business\n  text: If you are using the Services on behalf of an entity, organization or company,\
  \ you need to have the authority\n    to bind that organization to these Terms\nrestricted_uses:\n- summary: No information about minors\n  text: You are not permitted to enter any information about a minor anywhere on the Services unless you are that\n    minor’s legal guardian and consent to the practices described in these Terms on behalf of that minor.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You have to be 18 years of age or older to use the Services and live within the United States.\n"
source_yaml_url: https://artifacts.apis.io/stride-health/eligibility/stride-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Stride Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Insurance
- Health Insurance
- Benefits
- Gig Economy
- Insurtech
- Tax
---
