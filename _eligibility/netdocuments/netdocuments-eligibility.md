---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: External User is a person outside the Customer’s organization who is given rights by the Customer to access some or all of the Customer’s Service repository.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to accept these Terms of Use and to use the Service.
    value: '18'
  restricted_uses:
  - summary: Internal business purposes only
    text: Use the Service only for the internal business purposes of the Customer that invited You to access the Service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: External User must accept these Terms of Use in order to use the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: NetDocuments
provenance_date: '2026-11-10'
provider_name: NetDocuments
provider_slug: netdocuments
slug: netdocuments-eligibility
source_date: '2026-11-10'
source_filename: netdocuments-eligibility.yml
source_heading: Eligibility
source_page: https://www.netdocuments.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NetDocuments\naid: netdocuments\nurl: https://www.netdocuments.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: External User is a person outside the Customer’s organization who is given rights by the Customer to access\n    some or all of the Customer’s Service repository.\nrestricted_uses:\n- summary: Internal business purposes only\n  text: Use the Service only for the internal business purposes of the Customer that invited You to access the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: External User must accept these Terms of Use in order to use the Service.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to accept these Terms of Use and to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/netdocuments/eligibility/netdocuments-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from NetDocuments's own page on 2026-11-10.
synthetic: false
tags:
- Document Management
- Email Management
- Legal AI
- Workflow Automation
- Integration
- Security
---
