---
claim_count: 8
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An “Individual Use Developer” means a Developer exercising the rights under this Agreement for their own personal use and is tied to a single Developer ID.
    type: individual
  - text: A “Vendor Use Developer” means a Developer exercising the rights under this Agreement for multiple users and for Applications that may be more widely distributed.
    type: business
  - source: https://developer.morganstanley.com/terms
    text: “Client” means an entity that is party to at least one valid and existing Client Agreement.
    type: other
  - source: https://developer.morganstanley.com/terms
    text: “API Vendor” means a Client’s Vendor (other than Vendor personnel acting in the capacity of a client’s Authorised User) who accesses and uses the API Services in order to provide the API Vendor Connectivity to such Client.
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Algorithmic or automated order generation
    text: Developer shall not implement, use, permit the use of, or design the Application or any related functionality to engage in Algorithmic or Automated Order Generation in connection with the API.
  - summary: Orders for third parties without authorization
    text: The Developer shall not create, initiate, or route any order on behalf of a third-party through the API unless the Developer has received explicit, contemporaneous instructions from the third-party authorizing such action.
  - source: https://developer.morganstanley.com/terms
    summary: Export restrictions on Data
    text: You may not use or otherwise export or re-export any part of the Data except as authorised by us.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Upon request of the Company, Developer will complete an API questionnaire which will assist in identifying Developer as either an Individual User Developer or a Vendor Use Developer.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Morgan Stanley
provenance_date: '2026-11-10'
provider_name: Morgan Stanley
provider_slug: morgan-stanley
slug: morgan-stanley-eligibility
source_date: '2026-11-10'
source_filename: morgan-stanley-eligibility.yml
source_heading: Eligibility
source_page: https://us.etrade.com/l/f/agreement-library/api-developer-licensing-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Morgan Stanley\naid: morgan-stanley\nurl: https://us.etrade.com/l/f/agreement-library/api-developer-licensing-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://developer.morganstanley.com/terms\n  - https://us.etrade.com/l/f/agreement-library/api-developer-licensing-agreement\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: An “Individual Use Developer” means a Developer exercising the rights under this Agreement for their own\n    personal use and is tied to a single Developer ID.\n- type: business\n  text: A “Vendor Use Developer” means a Developer\
  \ exercising the rights under this Agreement for multiple users\n    and for Applications that may be more widely distributed.\n- type: other\n  text: “Client” means an entity that is party to at least one valid and existing Client Agreement.\n  source: https://developer.morganstanley.com/terms\n- type: other\n  text: “API Vendor” means a Client’s Vendor (other than Vendor personnel acting in the capacity of a client’s Authorised\n    User) who accesses and uses the API Services in order to provide the API Vendor Connectivity to such Client.\n  source: https://developer.morganstanley.com/terms\nrestricted_uses:\n- summary: Algorithmic or automated order generation\n  text: Developer shall not implement, use, permit the use of, or design the Application or any related functionality\n    to engage in Algorithmic or Automated Order Generation in connection with the API.\n- summary: Orders for third parties without authorization\n  text: The Developer shall not create, initiate, or route any\
  \ order on behalf of a third-party through the API\n    unless the Developer has received explicit, contemporaneous instructions from the third-party authorizing such\n    action.\n- summary: Export restrictions on Data\n  text: You may not use or otherwise export or re-export any part of the Data except as authorised by us.\n  source: https://developer.morganstanley.com/terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Upon request of the Company, Developer will complete an API questionnaire which will assist in identifying\n    Developer as either an Individual User Developer or a Vendor Use Developer.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/morgan-stanley/eligibility/morgan-stanley-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 8 quoted statements, read from Morgan Stanley's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Investment Banking
- Wealth Management
- Brokerage
- Market Data
- Trading
- Fortune 100
- United States
---
