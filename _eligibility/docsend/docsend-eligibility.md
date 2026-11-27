---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms for use of the Services by an organization, you are agreeing on behalf of that organization.
    type: business
  minimum_age:
    text: The Services are not intended for End Users under the age of 13 in the United States or 16 outside of the United States.
    value: '13'
  restricted_uses:
  - summary: No consumer transactions for DocSend Signature
    text: Customer may not use DocSend Signature in connection with consumer transactions.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to use the Services, Customers and End Users must first register with us through our on-line registration process
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DocSend
provenance_date: '2026-11-09'
provider_name: DocSend
provider_slug: docsend
slug: docsend-eligibility
source_date: '2026-11-09'
source_filename: docsend-eligibility.yml
source_heading: Eligibility
source_page: https://www.docsend.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DocSend\naid: docsend\nurl: https://www.docsend.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms for use of the Services by an organization, you are agreeing on behalf\n    of that organization.\nrestricted_uses:\n- summary: No consumer transactions for DocSend Signature\n  text: Customer may not use DocSend Signature in connection with consumer transactions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to use the Services, Customers and\
  \ End Users must first register with us through our on-line registration\n    process\nminimum_age:\n  value: '13'\n  text: The Services are not intended for End Users under the age of 13 in the United States or 16 outside of the\n    United States.\n"
source_yaml_url: https://artifacts.apis.io/docsend/eligibility/docsend-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from DocSend's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Document Sharing
- Sales Enablement
- Analytics
- Virtual Data Room
- E-Signature
- MCP
- Dropbox
---
