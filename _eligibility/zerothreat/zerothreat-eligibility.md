---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting these Terms on behalf of another person, a company, or another legal entity, you represent and warrant that you have the full authority to bind that person, company, or legal entity to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use and authorization for scanned systems
    text: Obtain all necessary authorizations, approvals, and permissions for the lawful use of the Service, especially in relation to the systems to which it is applied.
  - summary: Free Credits evaluation only
    text: Free Credits are intended solely for evaluation purposes. They must not be used for production environments or commercial applications.
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
name: ZeroThreat
provenance_date: '2026-11-10'
provider_name: ZeroThreat
provider_slug: zerothreat
slug: zerothreat-eligibility
source_date: '2026-11-10'
source_filename: zerothreat-eligibility.yml
source_heading: Eligibility
source_page: https://zerothreat.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ZeroThreat\naid: zerothreat\nurl: https://zerothreat.ai/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting these Terms on behalf of another person, a company, or another legal entity, you represent\n    and warrant that you have the full authority to bind that person, company, or legal entity to these Terms.\nrestricted_uses:\n- summary: Lawful use and authorization for scanned systems\n  text: Obtain all necessary authorizations, approvals, and permissions for the lawful use of the Service,\
  \ especially\n    in relation to the systems to which it is applied.\n- summary: Free Credits evaluation only\n  text: Free Credits are intended solely for evaluation purposes. They must not be used for production environments\n    or commercial applications.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zerothreat/eligibility/zerothreat-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from ZeroThreat's own page on 2026-11-10.
synthetic: false
tags:
- Pentesting
- Web Application Security
- API Security
- DevOps
- Enterprise Security
- Compliance
---
