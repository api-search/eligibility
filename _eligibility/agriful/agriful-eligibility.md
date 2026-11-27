---
claim_count: 3
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
    text: YOU MAY NOT ACCESS THE SERVICES IF YOU ARE A DIRECT COMPETITOR OF AGRIFUL
  - summary: No benchmarking or competitive monitoring
    text: you may not access the services for purposes of monitoring their availability, performance or functionality, or for any other benchmarking or competitive purposes
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
name: Agriful
provenance_date: '2026-11-09'
provider_name: Agriful
provider_slug: agriful
slug: agriful-eligibility
source_date: '2026-11-09'
source_filename: agriful-eligibility.yml
source_heading: Eligibility
source_page: https://www.agrifulsoftware.com/about/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agriful\naid: agriful\nurl: https://www.agrifulsoftware.com/about/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF THE INDIVIDUAL SIGNING THE ORDER FORM FOR CUSTOMER IS SIGNING ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY,\n    SUCH INDIVIDUAL REPRESENTS THAT HE OR SHE HAS THE AUTHORITY TO BIND THAT COMPANY OR OTHER LEGAL ENTITY.\nrestricted_uses:\n- summary: Direct competitors barred\n  text: YOU MAY NOT ACCESS THE SERVICES IF YOU ARE A DIRECT COMPETITOR OF AGRIFUL\n- summary: No benchmarking or competitive monitoring\n\
  \  text: you may not access the services for purposes of monitoring their availability, performance or functionality,\n    or for any other benchmarking or competitive purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agriful/eligibility/agriful-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Agriful's own page on 2026-11-09.
synthetic: false
tags:
- Agriculture
- Fresh Produce
- Food Supply Chain
- Traceability
- ERP
- Inventory
- Order Management
- Accounting
- Software-as-a-Service
- Company
---
