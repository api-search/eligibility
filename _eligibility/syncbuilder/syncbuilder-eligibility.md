---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to enter into a binding contract.
    type: individual
  - text: If you use the Service on behalf of an organisation, you confirm that you are authorised to bind that organisation to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to enter into a binding contract.
    value: '18'
  restricted_uses:
  - summary: Unlawful or unauthorised use
    text: use the Service unlawfully or in breach of third-party rights
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use most of the Service you must create an account, and you may be required to enable two-factor authentication.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SyncBuilder
provenance_date: '2026-11-10'
provider_name: SyncBuilder
provider_slug: syncbuilder
slug: syncbuilder-eligibility
source_date: '2026-11-10'
source_filename: syncbuilder-eligibility.yml
source_heading: Eligibility
source_page: https://syncbuilder.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SyncBuilder\naid: syncbuilder\nurl: https://syncbuilder.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter into a binding contract.\n- type: business\n  text: If you use the Service on behalf of an organisation, you confirm that you are authorised to bind that organisation\n    to these Terms.\nrestricted_uses:\n- summary: Unlawful or unauthorised use\n  text: use the Service unlawfully or in breach of third-party rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: To use most of the Service you must create an account, and you may be required to enable two-factor authentication.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter into a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/syncbuilder/eligibility/syncbuilder-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from SyncBuilder's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Integration
- Data Sync
- ERP
- Automation
---
