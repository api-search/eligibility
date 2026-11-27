---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    source: https://pubmatic.com/legal/website-terms-of-service/
    text: The Site may not be appropriate or available for use in some jurisdictions outside of the United States.
  entity_types:
  - text: If you are using the PubMatic Developer Services on behalf of any company, entity, or organization, you represent and warrant that you have authority to bind such company, entity, or organization, as applicable.
    type: business
  minimum_age:
    text: You may not use the PubMatic Developer Services and may not accept the Terms if (i) you are not of legal age to form a binding contract with PubMatic
    value: null
  restricted_uses:
  - summary: Illegal or indecent contexts
    text: Feature or use the PubMatic Developer Services (including any PubMatic Brand Features) in any pornographic, discriminatory, illegal, or otherwise indecent context.
  - source: https://pubmatic.com/legal/website-terms-of-service/
    summary: Unauthorized advertising or selling
    text: Use the Site to advertise or offer to sell or buy any goods or services without our express prior written consent.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: From time to time, PubMatic may require you to submit your Application for review and approval by PubMatic prior to distribution to your users.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PubMatic
provenance_date: '2026-11-10'
provider_name: PubMatic
provider_slug: pubmatic
slug: pubmatic-eligibility
source_date: '2026-11-10'
source_filename: pubmatic-eligibility.yml
source_heading: Eligibility
source_page: https://pubmatic.com/legal/developer-terms-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PubMatic\naid: pubmatic\nurl: https://pubmatic.com/legal/developer-terms-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://pubmatic.com/legal/developer-terms-use/\n  - https://pubmatic.com/legal/website-terms-of-service/\ncountries:\n  served: []\n  excluded: []\n  text: The Site may not be appropriate or available for use in some jurisdictions outside of the United States.\n  source: https://pubmatic.com/legal/website-terms-of-service/\nentity_types:\n- type: business\n  text: If you are using the PubMatic Developer Services on behalf of any company, entity, or organization, you\n    represent and warrant\
  \ that you have authority to bind such company, entity, or organization, as applicable.\nrestricted_uses:\n- summary: Illegal or indecent contexts\n  text: Feature or use the PubMatic Developer Services (including any PubMatic Brand Features) in any pornographic,\n    discriminatory, illegal, or otherwise indecent context.\n- summary: Unauthorized advertising or selling\n  text: Use the Site to advertise or offer to sell or buy any goods or services without our express prior written\n    consent.\n  source: https://pubmatic.com/legal/website-terms-of-service/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: From time to time, PubMatic may require you to submit your Application for review and approval by PubMatic\n    prior to distribution to your users.\nminimum_age:\n  value: null\n  text: You may not use the PubMatic Developer Services and may not accept the Terms if (i) you are not of legal\n    age to form a binding contract with PubMatic\n"
source_yaml_url: https://artifacts.apis.io/pubmatic/eligibility/pubmatic-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from PubMatic's own page on 2026-11-10.
synthetic: false
tags:
- Advertising
- AdTech
- Programmatic Advertising
- Supply Side Platform
- Header Bidding
- OpenWrap
- Prebid
- OpenRTB
- Connected TV
- CTV
- Mobile Advertising
- Commerce Media
- Retail Media
- Identity
- Curation
- Auction Packages
- AI Agents
---
