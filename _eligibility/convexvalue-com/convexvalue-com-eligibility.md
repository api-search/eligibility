---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are not a corporation, partnership, limited liability company, trust (except for qualifying trusts) or other form of entity.
    type: individual
  - text: certain small business entities (limited liability companies, partnerships, trusts or corporations) that, receive and use Information
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for professional/broker-dealer roles
    text: You are not an employee, associated person, owner, or partner of a securities broker-dealer, investment advisor, futures commission merchant, commodities introducing broker or commodity trading advisor
  - summary: No third-party asset management (CME)
    text: be limited to managing the Subscriber's own assets, and not be used in connection with the management of any assets of any third party(ies) in any capacity
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
name: ConvexValue
provenance_date: '2026-11-09'
provider_name: ConvexValue
provider_slug: convexvalue-com
slug: convexvalue-com-eligibility
source_date: '2026-11-09'
source_filename: convexvalue-com-eligibility.yml
source_heading: Eligibility
source_page: https://convexvalue.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ConvexValue\naid: convexvalue-com\nurl: https://convexvalue.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are not a corporation, partnership, limited liability company, trust (except for qualifying trusts)\n    or other form of entity.\n- type: business\n  text: certain small business entities (limited liability companies, partnerships, trusts or corporations) that,\n    receive and use Information\nrestricted_uses:\n- summary: Not for professional/broker-dealer roles\n  text: You are not an employee, associated person,\
  \ owner, or partner of a securities broker-dealer, investment\n    advisor, futures commission merchant, commodities introducing broker or commodity trading advisor\n- summary: No third-party asset management (CME)\n  text: be limited to managing the Subscriber's own assets, and not be used in connection with the management of\n    any assets of any third party(ies) in any capacity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/convexvalue-com/eligibility/convexvalue-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from ConvexValue's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Data
- Options Analytics
- Market Data
- Stocks
- Trading
- MCP
- Artificial Intelligence
---
