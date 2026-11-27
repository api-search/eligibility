---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not an Australian, U.K., U.S., Canadian, German, Irish, Finish, Belgian, Dutch or Austrian resident.
  entity_types:
  - text: only your incorporated business or other legal entity may sign-up, access and use a Service; an individual user not acting on behalf of an incorporated business or other legal entity is prohibited from signing up, accessing and using the Services.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Direct competitors barred
    text: If you are a direct competitor of us, you are prohibited from accessing and using the Site and Services without our prior written consent.
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
name: Clearco
provenance_date: '2026-11-09'
provider_name: Clearco
provider_slug: clearbanc
slug: clearbanc-eligibility
source_date: '2026-11-09'
source_filename: clearbanc-eligibility.yml
source_heading: Eligibility
source_page: https://www.clear.co/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clearco\naid: clearbanc\nurl: https://www.clear.co/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: you are not an Australian, U.K., U.S., Canadian, German, Irish, Finish, Belgian, Dutch or Austrian resident.\nentity_types:\n- type: business\n  text: only your incorporated business or other legal entity may sign-up, access and use a Service; an individual\n    user not acting on behalf of an incorporated business or other legal entity is prohibited from signing up, accessing\n    and using the Services.\nrestricted_uses:\n- summary: Direct\
  \ competitors barred\n  text: If you are a direct competitor of us, you are prohibited from accessing and using the Site and Services\n    without our prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clearbanc/eligibility/clearbanc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Clearco's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Financial Services
- Fintech
- Lending
- Working Capital
- Revenue-Based Financing
- Invoice Funding
- E-Commerce
---
