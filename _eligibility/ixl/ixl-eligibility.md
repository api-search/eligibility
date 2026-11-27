---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IXL does not sell the Service to children, but only to adults who can purchase the Service with a credit card or other permitted payment method.
    type: individual
  - text: When the Service is used by an educational agency or institution, including but not limited to a school, school district, school official
    type: other
  minimum_age:
    text: If you are under eighteen (18) years of age, you may use the Service only with the involvement and consent of a parent, legal guardian, or at the direction of your School.
    value: '18'
  restricted_uses:
  - summary: No autonomous agents
    text: You will not use, allow, enable, or cause the deployment of an Agent (i.e., any software or service that takes autonomous or semi-autonomous action on behalf of, or at the instruction of, any person or entity) to access, use, or interact with the Service.
  - summary: No account sharing
    text: IXL accounts may not be shared by more than one person or organization unless express authorization is given by IXL Learning, Inc.
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
name: IXL Learning
provenance_date: '2026-11-09'
provider_name: IXL Learning
provider_slug: ixl
slug: ixl-eligibility
source_date: '2026-11-09'
source_filename: ixl-eligibility.yml
source_heading: Eligibility
source_page: https://www.ixl.com/termsofservice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: IXL Learning\naid: ixl\nurl: https://www.ixl.com/termsofservice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: IXL does not sell the Service to children, but only to adults who can purchase the Service with a credit\n    card or other permitted payment method.\n- type: other\n  text: When the Service is used by an educational agency or institution, including but not limited to a school,\n    school district, school official\nrestricted_uses:\n- summary: No autonomous agents\n  text: You will not use, allow, enable,\
  \ or cause the deployment of an Agent (i.e., any software or service that\n    takes autonomous or semi-autonomous action on behalf of, or at the instruction of, any person or entity) to\n    access, use, or interact with the Service.\n- summary: No account sharing\n  text: IXL accounts may not be shared by more than one person or organization unless express authorization is given\n    by IXL Learning, Inc.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under eighteen (18) years of age, you may use the Service only with the involvement and consent\n    of a parent, legal guardian, or at the direction of your School.\n"
source_yaml_url: https://artifacts.apis.io/ixl/eligibility/ixl-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from IXL Learning's own page on 2026-11-09.
synthetic: false
tags:
- Education
- K-12
- Math
- Language Arts
- Science
- Social Studies
- Spanish
- Diagnostics
- Rostering
- SSO
- Identity Federation
- Assessment
---
