---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If you are registering for or using the Services on behalf of an organization, you represent and warrant that: You have authority to bind that organization to these terms'
    type: business
  - text: If you are using the Services as an individual, references to "Customer" refer to you personally.
    type: individual
  - text: U.S. Government Entities The Services are commercial computer software. Federal government end users acquire the Services with only those rights set forth in these terms.
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Healthcare use requires BAA
    text: Healthcare organizations must execute a separate Business Associate Agreement (BAA) for HIPAA compliance. The Services are not HIPAA-compliant without an executed BAA.
  - summary: Patent assertion entities
    text: Customers that are patent assertion entities may not use the Services to pursue patent infringement claims against Tallyfy or its customers.
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
name: Tallyfy
provenance_date: '2026-11-10'
provider_name: Tallyfy
provider_slug: tallyfy
slug: tallyfy-eligibility
source_date: '2026-11-10'
source_filename: tallyfy-eligibility.yml
source_heading: Eligibility
source_page: https://tallyfy.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tallyfy\naid: tallyfy\nurl: https://tallyfy.com/legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'If you are registering for or using the Services on behalf of an organization, you represent and warrant\n    that: You have authority to bind that organization to these terms'\n- type: individual\n  text: If you are using the Services as an individual, references to \"Customer\" refer to you personally.\n- type: government\n  text: U.S. Government Entities The Services are commercial computer software. Federal government end users\
  \ acquire\n    the Services with only those rights set forth in these terms.\nrestricted_uses:\n- summary: Healthcare use requires BAA\n  text: Healthcare organizations must execute a separate Business Associate Agreement (BAA) for HIPAA compliance.\n    The Services are not HIPAA-compliant without an executed BAA.\n- summary: Patent assertion entities\n  text: Customers that are patent assertion entities may not use the Services to pursue patent infringement claims\n    against Tallyfy or its customers.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tallyfy/eligibility/tallyfy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Tallyfy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Workflow Automation
- Business Process Management
- SOPs
- Task
- Approvals
- Forms
- Process Management
- No-Code
---
