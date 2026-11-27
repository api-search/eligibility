---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: JOIN CLIENTS IN 80+ COUNTRIES
  entity_types:
  - text: Membrain, to the extent selling products or services, sells products or services to adults who can purchase with a credit card or other permitted payment method.
    type: individual
  minimum_age:
    text: If you are under 18, you may use Membrain.com only with your parent or guardian’s involvement and consent.
    value: '18'
  restricted_uses:
  - summary: Restricted content posted by visitors
    text: provided the content is not illegal, obscene, threatening, defamatory, invasive of privacy, infringing of intellectual property rights, or otherwise injurious to third parties or objectionable
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
name: Membrain
provenance_date: '2026-11-10'
provider_name: Membrain
provider_slug: membrain
slug: membrain-eligibility
source_date: '2026-11-10'
source_filename: membrain-eligibility.yml
source_heading: Eligibility
source_page: https://www.membrain.com/legal/website-terms-of-use?hsLang=en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Membrain\naid: membrain\nurl: https://www.membrain.com/legal/website-terms-of-use?hsLang=en\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: JOIN CLIENTS IN 80+ COUNTRIES\nentity_types:\n- type: individual\n  text: Membrain, to the extent selling products or services, sells products or services to adults who can purchase\n    with a credit card or other permitted payment method.\nrestricted_uses:\n- summary: Restricted content posted by visitors\n  text: provided the content is not illegal, obscene, threatening, defamatory, invasive of privacy, infringing of\n    intellectual property\
  \ rights, or otherwise injurious to third parties or objectionable\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18, you may use Membrain.com only with your parent or guardian’s involvement and consent.\n"
source_yaml_url: https://artifacts.apis.io/membrain/eligibility/membrain-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Membrain's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sales
- B2B
- Platform
- CRM
---
