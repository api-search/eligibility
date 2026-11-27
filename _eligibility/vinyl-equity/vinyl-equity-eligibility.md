---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are not intended for use by any person or entity in any jurisdiction or country where such use might be contrary to local law or regulation.
  entity_types:
  - text: Corporate entities, and the individuals, employees and affiliates of these entities that utilize our Services will be referred to as “ User(s) .”
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use contrary to local law
    text: The Services are not intended for use by any person or entity in any jurisdiction or country where such use might be contrary to local law or regulation.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: we will ask you to verify your identity by submitting additional personal information, and government identification to a third-party identity verification service provider. Currently, our chosen identity veriﬁcation solution provider is Persona.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Vinyl Equity
provenance_date: '2026-11-10'
provider_name: Vinyl Equity
provider_slug: vinyl-equity
slug: vinyl-equity-eligibility
source_date: '2026-11-10'
source_filename: vinyl-equity-eligibility.yml
source_heading: Eligibility
source_page: https://www.vinylequity.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vinyl Equity\naid: vinyl-equity\nurl: https://www.vinylequity.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are not intended for use by any person or entity in any jurisdiction or country where such\n    use might be contrary to local law or regulation.\nentity_types:\n- type: business\n  text: Corporate entities, and the individuals, employees and affiliates of these entities that utilize our Services\n    will be referred to as “ User(s) .”\nrestricted_uses:\n- summary: Use contrary to local law\n  text: The Services are not intended for\
  \ use by any person or entity in any jurisdiction or country where such\n    use might be contrary to local law or regulation.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: we will ask you to verify your identity by submitting additional personal information, and government identification\n    to a third-party identity verification service provider. Currently, our chosen identity veriﬁcation solution\n    provider is Persona.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vinyl-equity/eligibility/vinyl-equity-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Vinyl Equity's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Business Applications
- Transfer Agency
- Cap Table
- Equity Management
- Shareholder-Management
- Proxy & AGM
- Fintech
---
