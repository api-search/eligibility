---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: individuals and other legal entities who can form legally binding contracts under applicable law
    type: business
  minimum_age:
    text: The Curri Platform is not available to children (persons under the age of 18)
    value: '18'
  restricted_uses:
  - summary: Special shipments require qualifications
    text: Such qualifications may include, without limitation, being 21 years of age or older
  - summary: Hazardous materials
    text: Sender shall be solely responsible for ensuring that all HAZMAT is properly identified, packaged, labeled, and certified
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All Carriers must enter a written Carrier/Broker Agreement with Curri, and all Drivers (unless they are Carrier Personnel employed by a Carrier) must enter a written Non-CMV Deliverer Agreement with Curri, in each case prior to receiving access to the Curri Platform or performing any Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Curri
provenance_date: '2026-11-09'
provider_name: Curri
provider_slug: curri
slug: curri-eligibility
source_date: '2026-11-09'
source_filename: curri-eligibility.yml
source_heading: Eligibility
source_page: https://www.curri.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Curri\naid: curri\nurl: https://www.curri.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: individuals and other legal entities who can form legally binding contracts under applicable law\nrestricted_uses:\n- summary: Special shipments require qualifications\n  text: Such qualifications may include, without limitation, being 21 years of age or older\n- summary: Hazardous materials\n  text: Sender shall be solely responsible for ensuring that all HAZMAT is properly identified, packaged, labeled,\n    and certified\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All Carriers must enter a written Carrier/Broker Agreement with Curri, and all Drivers (unless they are\n    Carrier Personnel employed by a Carrier) must enter a written Non-CMV Deliverer Agreement with Curri, in each\n    case prior to receiving access to the Curri Platform or performing any Services.\nminimum_age:\n  value: '18'\n  text: The Curri Platform is not available to children (persons under the age of 18)\n"
source_yaml_url: https://artifacts.apis.io/curri/eligibility/curri-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Curri's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Vertical Software
- Delivery
- Logistics
- Last Mile Delivery
- Freight
- Construction
- Supply Chain
- GraphQL
---
