---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Program is available to individuals ... Individuals who are residents of the United States (including its territories and possessions)
  entity_types:
  - text: Our products and Services may be purchased for resale only through the Divi Pro website located at https://diviofficialpro.com after an account has been registered and approved by us
    type: business
  minimum_age:
    text: By agreeing to these Terms, you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: No resale or export
    text: you represent and warrant that you are buying products or services from us for your own personal or household use, and not for resale or export.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: after an account has been registered and approved by us, which approval may be granted or denied in our sole and absolute discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Divi Official
provenance_date: '2026-11-09'
provider_name: Divi Official
provider_slug: diviofficial
slug: diviofficial-eligibility
source_date: '2026-11-09'
source_filename: diviofficial-eligibility.yml
source_heading: Eligibility
source_page: https://www.diviofficial.com/pages/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Divi Official\naid: diviofficial\nurl: https://www.diviofficial.com/pages/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Program is available to individuals ... Individuals who are residents of the United States (including\n    its territories and possessions)\nentity_types:\n- type: business\n  text: Our products and Services may be purchased for resale only through the Divi Pro website located at https://diviofficialpro.com\n    after an account has been registered and approved by us\nrestricted_uses:\n- summary: No resale or export\n  text: you represent\
  \ and warrant that you are buying products or services from us for your own personal or household\n    use, and not for resale or export.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: after an account has been registered and approved by us, which approval may be granted or denied in our\n    sole and absolute discretion.\nminimum_age:\n  value: age of majority\n  text: By agreeing to these Terms, you represent that you are at least the age of majority in your state or province\n    of residence\n"
source_yaml_url: https://artifacts.apis.io/diviofficial/eligibility/diviofficial-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Divi Official's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer Packaged Goods
- Beauty
- Hair Care
- E-Commerce
- Direct to Consumer
- Shopify
- Subscription
---
