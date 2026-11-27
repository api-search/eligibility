---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using or opening an account on the Service on behalf of a retailer (“Retailer”), then you represent and warrant that you are an authorized representative of that Retailer with the authority to bind such Retailer to the Terms
    type: business
  minimum_age:
    text: In order to use the Service, you must be the age of majority in your country and fully competent to understand and agree to the Terms.
    value: age of majority
  restricted_uses:
  - summary: Spam
    text: You must not upload, post, host, or transmit unsolicited email, SMSs, or “spam” messages.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SKU IQ
provenance_date: '2026-11-10'
provider_name: SKU IQ
provider_slug: sku-iq
slug: sku-iq-eligibility
source_date: '2026-11-10'
source_filename: sku-iq-eligibility.yml
source_heading: Eligibility
source_page: https://www.skuiq.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SKU IQ\naid: sku-iq\nurl: https://www.skuiq.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using or opening an account on the Service on behalf of a retailer (“Retailer”), then you represent\n    and warrant that you are an authorized representative of that Retailer with the authority to bind such Retailer\n    to the Terms\nrestricted_uses:\n- summary: Spam\n  text: You must not upload, post, host, or transmit unsolicited email, SMSs, or “spam” messages.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: age of majority\n  text: In order to use the Service, you must be the age of majority in your country and fully competent to understand\n    and agree to the Terms.\n"
source_yaml_url: https://artifacts.apis.io/sku-iq/eligibility/sku-iq-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from SKU IQ's own page on 2026-11-10.
synthetic: false
tags:
- Inventory
- Point-of-Sale
- E-Commerce
- Sync
- Retail
- Automation
---
