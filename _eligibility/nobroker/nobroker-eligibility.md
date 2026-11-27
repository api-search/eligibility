---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: Services means and includes the services provided by NoBroker within the territory of India to the User of the Site
  entity_types:
  - text: The User represents and warrants to NoBroker that the User is 18 (eighteen) years of age or above, and is capable of entering into, performing and adhering to the Agreement.
    type: individual
  minimum_age:
    text: The User represents and warrants to NoBroker that the User is 18 (eighteen) years of age or above
    value: '18'
  restricted_uses:
  - summary: Brokers may not use the Site
    text: In the event, a User is detected as a Broker, NoBroker has the right to reject or disable such Account without cause.
  - summary: Multiple accounts prohibited
    text: The User is prohibited from creating multiple Accounts
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Account means and includes the account created on the Site, by the User, in accordance with the terms of the Agreement, registered with and approved by NoBroker.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: NoBroker
provenance_date: '2026-11-10'
provider_name: NoBroker
provider_slug: nobroker
slug: nobroker-eligibility
source_date: '2026-11-10'
source_filename: nobroker-eligibility.yml
source_heading: Eligibility
source_page: https://www.nobroker.in/terms-and-condition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NoBroker\naid: nobroker\nurl: https://www.nobroker.in/terms-and-condition\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: Services means and includes the services provided by NoBroker within the territory of India to the User\n    of the Site\nentity_types:\n- type: individual\n  text: The User represents and warrants to NoBroker that the User is 18 (eighteen) years of age or above, and is\n    capable of entering into, performing and adhering to the Agreement.\nrestricted_uses:\n- summary: Brokers may not use the Site\n  text: In the event, a User is detected\
  \ as a Broker, NoBroker has the right to reject or disable such Account without\n    cause.\n- summary: Multiple accounts prohibited\n  text: The User is prohibited from creating multiple Accounts\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Account means and includes the account created on the Site, by the User, in accordance with the terms of\n    the Agreement, registered with and approved by NoBroker.\nminimum_age:\n  value: '18'\n  text: The User represents and warrants to NoBroker that the User is 18 (eighteen) years of age or above\n"
source_yaml_url: https://artifacts.apis.io/nobroker/eligibility/nobroker-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from NoBroker's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- PropTech
- Property Rental
- Marketplace
- Home Services
- Society Management
- India
---
