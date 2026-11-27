---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - AU
    - CA
    - JP
    served:
    - CH
    - 'NO'
    - US
    text: The website is intended for residents of a country of the European Union, Switzerland, Norway or the United States. The securities have not been registered according to the applicable securities regulations of Australia, Canada or Japan and are neither offered nor sold in Australia, Canada, nor in Japan or to persons who are residents of Australia, Canada or Japan.
  entity_types:
  - text: intended solely for private use by individuals who are residents in a country of the European Union, in Switzerland, in Norway or in the United States of America.
    type: individual
  minimum_age:
    text: By accepting these General Terms and Conditions, the user acknowledges that they have reached the age of 18.
    value: '18'
  restricted_uses:
  - summary: Market manipulation prohibited
    text: Market manipulation and any attempt for this purpose are prohibited.
  - summary: Private, non-commercial use of content
    text: may only be done for private, non-commercial use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- AU
- CA
- JP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wikifolio
provenance_date: '2026-11-10'
provider_name: Wikifolio
provider_slug: wikifolio
slug: wikifolio-eligibility
source_date: '2026-11-10'
source_filename: wikifolio-eligibility.yml
source_heading: Eligibility
source_page: https://www.wikifolio.com/en/int/legal/gtc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wikifolio\naid: wikifolio\nurl: https://www.wikifolio.com/en/int/legal/gtc\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CH\n  - 'NO'\n  - US\n  excluded:\n  - AU\n  - CA\n  - JP\n  text: The website is intended for residents of a country of the European Union, Switzerland, Norway or the United\n    States. The securities have not been registered according to the applicable securities regulations of Australia,\n    Canada or Japan and are neither offered nor sold in Australia, Canada, nor in Japan or to persons who are residents\n    of Australia, Canada or Japan.\nentity_types:\n- type: individual\n\
  \  text: intended solely for private use by individuals who are residents in a country of the European Union, in\n    Switzerland, in Norway or in the United States of America.\nrestricted_uses:\n- summary: Market manipulation prohibited\n  text: Market manipulation and any attempt for this purpose are prohibited.\n- summary: Private, non-commercial use of content\n  text: may only be done for private, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By accepting these General Terms and Conditions, the user acknowledges that they have reached the age of\n    18.\n"
source_yaml_url: https://artifacts.apis.io/wikifolio/eligibility/wikifolio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Wikifolio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Social Trading
- Copy Trading
- Investing
- Wealth Management
- Certificates
- Europe
---
