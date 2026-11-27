---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or immoral use
    text: use the Services for any unlawful, obscene or immoral purpose or for soliciting others to perform any unlawful or immoral acts
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'To register as a user, you must provide us the following information concerning the Client: business name, registry code or number, VAT number, address and name, e-mail address and other requested information about the legal entity and the contact person of the Client.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Jobbatical
provenance_date: '2026-11-09'
provider_name: Jobbatical
provider_slug: jobbatical
slug: jobbatical-eligibility
source_date: '2026-11-09'
source_filename: jobbatical-eligibility.yml
source_heading: Eligibility
source_page: https://www.jobbatical.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jobbatical\naid: jobbatical\nurl: https://www.jobbatical.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or immoral use\n  text: use the Services for any unlawful, obscene or immoral purpose or for soliciting others to perform any unlawful\n    or immoral acts\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'To register as a user, you must provide us the following information concerning the Client: business name,\n    registry code or number, VAT number, address and name,\
  \ e-mail address and other requested information about\n    the legal entity and the contact person of the Client.'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jobbatical/eligibility/jobbatical-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Jobbatical's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Immigration
- Global Mobility
- Relocation
- Visa
- Work Permits
- Human Resources
- Compliance
- Software-as-a-Service
---
