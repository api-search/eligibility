---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Site and/or the Services is limited exclusively to users located in States within the United States where the Services are available. Services are not available to users located outside the United States.
  entity_types:
  - text: In order to access the Site and the Services, you represent and warrant that you are older than 18 years old.
    type: individual
  minimum_age:
    text: In order to access the Site and the Services, you represent and warrant that you are older than 18 years old.
    value: '18'
  restricted_uses:
  - summary: No controlled substances
    text: Providers do not prescribe DEA controlled substances or scheduled medications, or certain other drugs which may be harmful because of their potential for abuse.
  - summary: No resale purchasing
    text: We do not accept orders from dealers, wholesalers, or other customers who intend to resell items offered on our Site.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Evernow and Evernow Medical and Cloud Health Medical Groups may contact you by telephone, mail, or email to verify your Account information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Evernow
provenance_date: '2026-11-09'
provider_name: Evernow
provider_slug: evernow
slug: evernow-eligibility
source_date: '2026-11-09'
source_filename: evernow-eligibility.yml
source_heading: Eligibility
source_page: https://www.evernow.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Evernow\naid: evernow\nurl: https://www.evernow.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Site and/or the Services is limited exclusively to users located in States within\n    the United States where the Services are available. Services are not available to users located outside the\n    United States.\nentity_types:\n- type: individual\n  text: In order to access the Site and the Services, you represent and warrant that you are older than 18 years\n    old.\nrestricted_uses:\n- summary: No controlled substances\n  text: Providers\
  \ do not prescribe DEA controlled substances or scheduled medications, or certain other drugs which\n    may be harmful because of their potential for abuse.\n- summary: No resale purchasing\n  text: We do not accept orders from dealers, wholesalers, or other customers who intend to resell items offered\n    on our Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Evernow and Evernow Medical and Cloud Health Medical Groups may contact you by telephone, mail, or email\n    to verify your Account information.\nminimum_age:\n  value: '18'\n  text: In order to access the Site and the Services, you represent and warrant that you are older than 18 years\n    old.\n"
source_yaml_url: https://artifacts.apis.io/evernow/eligibility/evernow-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Evernow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Menopause
- Telehealth
- Women's Health
---
