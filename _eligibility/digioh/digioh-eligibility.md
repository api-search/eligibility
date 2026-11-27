---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Software and Services are available only to, and may only be used by, individuals who can form legally binding contracts under applicable law.
    type: individual
  - text: If Customer is registering as a business entity, Customer represents that Customer has the authority to bind such entity to this Agreement.
    type: business
  minimum_age:
    text: the Software and Services are not available to children (persons under the age of 18).
    value: '18'
  restricted_uses:
  - summary: Prohibited item sales
    text: Customer agrees not to publish, offer for sale, sell or otherwise distribute any of the following items on, through or connected with Customer’s Webpages
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Digioh may use techniques to confirm the accuracy of the information Customer provides when Customer registers on the Digioh Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Digioh
provenance_date: '2026-11-09'
provider_name: Digioh
provider_slug: digioh
slug: digioh-eligibility
source_date: '2026-11-09'
source_filename: digioh-eligibility.yml
source_heading: Eligibility
source_page: https://www.digioh.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Digioh\naid: digioh\nurl: https://www.digioh.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Software and Services are available only to, and may only be used by, individuals who can form legally\n    binding contracts under applicable law.\n- type: business\n  text: If Customer is registering as a business entity, Customer represents that Customer has the authority to\n    bind such entity to this Agreement.\nrestricted_uses:\n- summary: Prohibited item sales\n  text: Customer agrees not to publish, offer\
  \ for sale, sell or otherwise distribute any of the following items\n    on, through or connected with Customer’s Webpages\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Digioh may use techniques to confirm the accuracy of the information Customer provides when Customer registers\n    on the Digioh Site.\nminimum_age:\n  value: '18'\n  text: the Software and Services are not available to children (persons under the age of 18).\n"
source_yaml_url: https://artifacts.apis.io/digioh/eligibility/digioh-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Digioh's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketing
- E-Commerce
- Personalization
- Zero-Party Data
- Forms
- Popups
- Quizzes
- Conversion Rate Optimization
- Identity Resolution
---
