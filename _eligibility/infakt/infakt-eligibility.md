---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Ogólne warunki świadczenia usługi dla spółek
    type: business
  - text: Ogólne warunki świadczenia usługi dla JDG
    type: individual
  minimum_age:
    text: null
    value: null
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
name: inFakt
provenance_date: '2026-11-09'
provider_name: inFakt
provider_slug: infakt
slug: infakt-eligibility
source_date: '2026-11-09'
source_filename: infakt-eligibility.yml
source_heading: Eligibility
source_page: https://www.infakt.pl/owu/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: inFakt\naid: infakt\nurl: https://www.infakt.pl/owu/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Ogólne warunki świadczenia usługi dla spółek\n- type: individual\n  text: Ogólne warunki świadczenia usługi dla JDG\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/infakt/eligibility/infakt-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from inFakt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Accounting
- Invoicing
- Fintech
- Bookkeeping
- E-Invoicing
- KSeF
- Tax
- Poland
- Small Business
---
