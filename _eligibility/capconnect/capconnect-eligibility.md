---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Any products, services and other content of the Site are offered only in jurisdictions where they may be legally provided
  entity_types:
  - text: By using the Site, the individual on behalf of himself/herself, or the person accessing the Site on behalf of an entity, represents and warrants that he/she is at least eighteen (18) years of age
    type: individual
  minimum_age:
    text: he/she is at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Export/sanctions restriction
    text: None of the products or services or other content available via the Site may be downloaded or otherwise exported to anyone on the United Stated Treasury Department’s list of Specially Designated Nationals
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Access to the password protected portions of the Site is granted solely pursuant to the Registered User’s Agreement, to investment advisers which have entered into such Registered User’s Agreement and been admitted to such platform.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CapConnect
provenance_date: '2026-11-09'
provider_name: CapConnect
provider_slug: capconnect
slug: capconnect-eligibility
source_date: '2026-11-09'
source_filename: capconnect-eligibility.yml
source_heading: Eligibility
source_page: https://www.capconnectplus.com/terms?hsLang=en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CapConnect\naid: capconnect\nurl: https://www.capconnectplus.com/terms?hsLang=en\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Any products, services and other content of the Site are offered only in jurisdictions where they may be\n    legally provided\nentity_types:\n- type: individual\n  text: By using the Site, the individual on behalf of himself/herself, or the person accessing the Site on behalf\n    of an entity, represents and warrants that he/she is at least eighteen (18) years of age\nrestricted_uses:\n- summary: Export/sanctions restriction\n  text: None of the products\
  \ or services or other content available via the Site may be downloaded or otherwise\n    exported to anyone on the United Stated Treasury Department’s list of Specially Designated Nationals\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Access to the password protected portions of the Site is granted solely pursuant to the Registered User’s\n    Agreement, to investment advisers which have entered into such Registered User’s Agreement and been admitted\n    to such platform.\nminimum_age:\n  value: '18'\n  text: he/she is at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/capconnect/eligibility/capconnect-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from CapConnect's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Fixed Income
- Digital Platform
- Issuance
- Investor Management
---
