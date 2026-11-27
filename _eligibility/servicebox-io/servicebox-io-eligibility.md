---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'ServiceBox yalnızca işletmelere hizmet verir: hesap açarak ve satın alarak bir işletme adına hareket ettiğinizi beyan edersiniz.'
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Ücretli planlar ve kredi paketleri geçerli bir vergi numarası (AB KDV numarası, VKN, şahıs şirketleri için TCKN veya ülkenizin eşdeğeri) ile satın alınır
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: servicebox-io
provenance_date: '2026-11-10'
provider_name: servicebox-io
provider_slug: servicebox-io
slug: servicebox-io-eligibility
source_date: '2026-11-10'
source_filename: servicebox-io-eligibility.yml
source_heading: Eligibility
source_page: https://servicebox.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: servicebox-io\naid: servicebox-io\nurl: https://servicebox.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'ServiceBox yalnızca işletmelere hizmet verir: hesap açarak ve satın alarak bir işletme adına hareket ettiğinizi\n    beyan edersiniz.'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Ücretli planlar ve kredi paketleri geçerli bir vergi numarası (AB KDV numarası, VKN, şahıs şirketleri için\n    TCKN veya ülkenizin eşdeğeri) ile satın alınır\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/servicebox-io/eligibility/servicebox-io-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from servicebox-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Europe
- Turkey
---
