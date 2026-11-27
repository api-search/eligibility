---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer acknowledges and agrees that Skyflow Services may only be used and accessed in geographical territories in which the Skyflow Services are lawful and authorized
  entity_types:
  - text: any entity with a valid, signed Order Form (defined below) with Skyflow
    type: business
  - text: If the user or licensee of the Skyflow Services is an agency, department, or other entity of the United States Government
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No regulated data in Try Accounts
    text: Regulated data (including without limitation PHI, PCI data, financial account data, or other sensitive regulated information)
  - summary: No ITAR-controlled information
    text: Customer shall not submit to the Skyflow Services any information that is controlled under the U.S. International Traffic in Arms Regulations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The parties shall enter into and execute an Order Form as of the Effective Date for the initial Subscription Term.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Skyflow
provenance_date: '2026-11-10'
provider_name: Skyflow
provider_slug: skyflow
slug: skyflow-eligibility
source_date: '2026-11-10'
source_filename: skyflow-eligibility.yml
source_heading: Eligibility
source_page: https://www.skyflow.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Skyflow\naid: skyflow\nurl: https://www.skyflow.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer acknowledges and agrees that Skyflow Services may only be used and accessed in geographical territories\n    in which the Skyflow Services are lawful and authorized\nentity_types:\n- type: business\n  text: any entity with a valid, signed Order Form (defined below) with Skyflow\n- type: government\n  text: If the user or licensee of the Skyflow Services is an agency, department, or other entity of the United\n    States Government\nrestricted_uses:\n- summary:\
  \ No regulated data in Try Accounts\n  text: Regulated data (including without limitation PHI, PCI data, financial account data, or other sensitive regulated\n    information)\n- summary: No ITAR-controlled information\n  text: Customer shall not submit to the Skyflow Services any information that is controlled under the U.S. International\n    Traffic in Arms Regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The parties shall enter into and execute an Order Form as of the Effective Date for the initial Subscription\n    Term.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/skyflow/eligibility/skyflow-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from Skyflow's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Privacy
- PII
- Tokenization
- Data Security
- Vault
- Compliance
- PCI
- Encryption
- Data Governance
---
