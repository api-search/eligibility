---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents and warrants that it is not located in and will not permit any User to access or use the Subscription Services in a U.S.-embargoed country
  entity_types:
  - text: The individual accepting this agreement on behalf of an entity represents and warrants that she/he is duly authorized and has full authority to execute this agreement on behalf of such entity.
    type: business
  - text: If Customer is an agency or contractor of the U.S. Government, the Parties agree that Customer receives only those rights with respect to the Subscription Services, Xtype Technology and Documentation as are granted to all other end users
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No competing products
    text: access the Xtype Technology for the purpose of developing or operating products or services intended to be offered to third parties in competition with the Subscription Services
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
name: Xtype
provenance_date: '2026-11-10'
provider_name: Xtype
provider_slug: xtype
slug: xtype-eligibility
source_date: '2026-11-10'
source_filename: xtype-eligibility.yml
source_heading: Eligibility
source_page: https://www.xtype.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Xtype\naid: xtype\nurl: https://www.xtype.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents and warrants that it is not located in and will not permit any User to access or use\n    the Subscription Services in a U.S.-embargoed country\nentity_types:\n- type: business\n  text: The individual accepting this agreement on behalf of an entity represents and warrants that she/he is duly\n    authorized and has full authority to execute this agreement on behalf of such entity.\n- type: government\n  text: If Customer is an agency or contractor\
  \ of the U.S. Government, the Parties agree that Customer receives\n    only those rights with respect to the Subscription Services, Xtype Technology and Documentation as are granted\n    to all other end users\nrestricted_uses:\n- summary: No competing products\n  text: access the Xtype Technology for the purpose of developing or operating products or services intended to\n    be offered to third parties in competition with the Subscription Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/xtype/eligibility/xtype-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Xtype's own page on 2026-11-10.
synthetic: false
tags:
- ServiceNow
- Governance
- Compliance
- Change Management
- DevOps
- ITSM
- Multi-Instance Management
---
