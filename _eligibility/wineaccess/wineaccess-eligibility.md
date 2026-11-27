---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Platform is intended for use by End Users located in the United States of America.
  entity_types:
  - text: Eligibility is limited to individuals only.
    type: individual
  - text: If you are accessing or using any part of the Platform on behalf of any business, organization, or other entity of any kind, you represent and warrant that you are authorized (a) to accept these terms on its behalf and (b) to bind such business, organization, or entity to the Agreement.
    type: business
  minimum_age:
    text: The Platform is intended for use only by adults (age 21 and older) in the states or territories where they reside.
    value: '21'
  restricted_uses:
  - summary: Alcohol orders for under-21 recipients
    text: that the recipient of any alcoholic beverage orders placed by you on this Platform will be at least 21 years old
  - summary: Resale of alcohol purchased
    text: any alcohol purchased using the Platform is intended for personal consumption and not for resale.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may terminate your account if we are unable to verify or authenticate the information you provide to us.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wineaccess
provenance_date: '2026-11-10'
provider_name: Wineaccess
provider_slug: wineaccess
slug: wineaccess-eligibility
source_date: '2026-11-10'
source_filename: wineaccess-eligibility.yml
source_heading: Eligibility
source_page: https://www.wineaccess.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wineaccess\naid: wineaccess\nurl: https://www.wineaccess.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Platform is intended for use by End Users located in the United States of America.\nentity_types:\n- type: individual\n  text: Eligibility is limited to individuals only.\n- type: business\n  text: If you are accessing or using any part of the Platform on behalf of any business, organization, or other\n    entity of any kind, you represent and warrant that you are authorized (a) to accept these terms on its behalf\n    and (b) to bind such business, organization,\
  \ or entity to the Agreement.\nrestricted_uses:\n- summary: Alcohol orders for under-21 recipients\n  text: that the recipient of any alcoholic beverage orders placed by you on this Platform will be at least 21 years\n    old\n- summary: Resale of alcohol purchased\n  text: any alcohol purchased using the Platform is intended for personal consumption and not for resale.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may terminate your account if we are unable to verify or authenticate the information you provide to\n    us.\nminimum_age:\n  value: '21'\n  text: The Platform is intended for use only by adults (age 21 and older) in the states or territories where they\n    reside.\n"
source_yaml_url: https://artifacts.apis.io/wineaccess/eligibility/wineaccess-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Wineaccess's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Wine
- E-Commerce
- Retail
- Beverages
- Wine Club
- Consumer
- Food and Beverage
---
