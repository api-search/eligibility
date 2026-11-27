---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF THE INDIVIDUAL SIGNING THE ORDER FORM FOR CUSTOMER IS SIGNING ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, SUCH INDIVIDUAL REPRESENTS THAT HE OR SHE HAS THE AUTHORITY TO BIND THAT COMPANY OR OTHER LEGAL ENTITY.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Direct competitors barred
    text: YOU MAY NOT ACCESS THE SERVICES IF YOU ARE A DIRECT COMPETITOR OF TAMARACK, EXCEPT WITH TAMARACK‘S PRIOR WRITTEN CONSENT.
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
name: Tamarack
provenance_date: '2026-11-10'
provider_name: Tamarack
provider_slug: tamarack
slug: tamarack-eligibility
source_date: '2026-11-10'
source_filename: tamarack-eligibility.yml
source_heading: Eligibility
source_page: https://www.tamaracksoftware.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tamarack\naid: tamarack\nurl: https://www.tamaracksoftware.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF THE INDIVIDUAL SIGNING THE ORDER FORM FOR CUSTOMER IS SIGNING ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY,\n    SUCH INDIVIDUAL REPRESENTS THAT HE OR SHE HAS THE AUTHORITY TO BIND THAT COMPANY OR OTHER LEGAL ENTITY.\nrestricted_uses:\n- summary: Direct competitors barred\n  text: YOU MAY NOT ACCESS THE SERVICES IF YOU ARE A DIRECT COMPETITOR OF TAMARACK, EXCEPT WITH TAMARACK‘S PRIOR\n    WRITTEN CONSENT.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tamarack/eligibility/tamarack-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Tamarack's own page on 2026-11-10.
synthetic: false
tags:
- Mill Management
- Software
- Cloud
- Inventory
---
