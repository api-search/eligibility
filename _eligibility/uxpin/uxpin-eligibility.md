---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Subscriber shall not access or use the Service if Subscriber is located in any jurisdiction in which the provision of the Service ... is prohibited under U.S. or other applicable laws
  entity_types:
  - text: the Service rendered by UXPin on the Site is developed and offered solely on business to business basis. UXPIN PROVIDES THE SERVICE ONLY FOR BUSINESS OR PROFESSIONAL PARTNERS AND REFRAINS FROM PROVIDING THE SERVICE TO THE CONSUMERS
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No benefit to third parties / commercial use during trial
    text: The Service may not be used commercially during a Free Trial.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: If the registration is approved (which approval may be withheld in the sole discretion of UXPin), the Subscriber will receive an e-mail
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: UXPin
provenance_date: '2026-11-10'
provider_name: UXPin
provider_slug: uxpin
slug: uxpin-eligibility
source_date: '2026-11-10'
source_filename: uxpin-eligibility.yml
source_heading: Eligibility
source_page: https://www.uxpin.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UXPin\naid: uxpin\nurl: https://www.uxpin.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Subscriber shall not access or use the Service if Subscriber is located in any jurisdiction in which the\n    provision of the Service ... is prohibited under U.S. or other applicable laws\nentity_types:\n- type: business\n  text: the Service rendered by UXPin on the Site is developed and offered solely on business to business basis.\n    UXPIN PROVIDES THE SERVICE ONLY FOR BUSINESS OR PROFESSIONAL PARTNERS AND REFRAINS FROM PROVIDING THE SERVICE\n    TO THE CONSUMERS\nrestricted_uses:\n\
  - summary: No benefit to third parties / commercial use during trial\n  text: The Service may not be used commercially during a Free Trial.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: If the registration is approved (which approval may be withheld in the sole discretion of UXPin), the Subscriber\n    will receive an e-mail\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/uxpin/eligibility/uxpin-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from UXPin's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Design
- Prototyping
- Design Systems
- React
- Components
- Artificial Intelligence
- Developer Tools
---
