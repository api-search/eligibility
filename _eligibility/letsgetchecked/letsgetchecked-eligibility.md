---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are operated by us from our offices within the United States of America (“USA”)... We will not process Orders from users whose IP address is outside, or where the user is located outside of, the United States.
  entity_types:
  - text: By accessing our using any of our Services, you represent that you are 18 years of age or older
    type: individual
  minimum_age:
    text: you represent that you are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: you are only using our Services for your own benefit and not for the purposes of providing our Services to others
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: all Orders are subject to review by a physician or other licensed clinician prior to testing, and we are under no obligation to accept or process an Order
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LetsGetChecked
provenance_date: '2026-11-09'
provider_name: LetsGetChecked
provider_slug: letsgetchecked
slug: letsgetchecked-eligibility
source_date: '2026-11-09'
source_filename: letsgetchecked-eligibility.yml
source_heading: Eligibility
source_page: https://www.letsgetchecked.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LetsGetChecked\naid: letsgetchecked\nurl: https://www.letsgetchecked.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are operated by us from our offices within the United States of America (“USA”)... We will\n    not process Orders from users whose IP address is outside, or where the user is located outside of, the United\n    States.\nentity_types:\n- type: individual\n  text: By accessing our using any of our Services, you represent that you are 18 years of age or older\nrestricted_uses:\n- summary: Personal use only\n\
  \  text: you are only using our Services for your own benefit and not for the purposes of providing our Services\n    to others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: all Orders are subject to review by a physician or other licensed clinician prior to testing, and we are\n    under no obligation to accept or process an Order\nminimum_age:\n  value: '18'\n  text: you represent that you are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/letsgetchecked/eligibility/letsgetchecked-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from LetsGetChecked's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Diagnostics
- Laboratory
- Telehealth
- Medical Testing
- Pharmacy
- Order
- Results
- Webhook
- HL7
- LOINC
---
