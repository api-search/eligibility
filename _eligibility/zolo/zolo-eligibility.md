---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: We provide Zolo for use only by persons located in Canada, excluding Quebec.
  entity_types:
  - text: IF YOU ARE USING ZOLO ON BEHALF OF ANOTHER PERSON OR A CORPORATE ENTITY, YOU REPRESENT AND WARRANT THAT YOU HAVE THE AUTHORITY TO BIND SUCH PERSON OR ENTITY TO THESE TERMS OF USE.
    type: business
  minimum_age:
    text: (I) YOU HAVE REACHED THE LEGAL AGE OF MAJORITY IN YOUR JURISDICTION
    value: legal age of majority in your jurisdiction
  restricted_uses:
  - summary: Competing offering
    text: use Zolo for the purpose of building a similar or competitive offering
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Real estate boards require a verified email prior to accessing full listing data including sold prices.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zolo
provenance_date: '2026-11-10'
provider_name: Zolo
provider_slug: zolo
slug: zolo-eligibility
source_date: '2026-11-10'
source_filename: zolo-eligibility.yml
source_heading: Eligibility
source_page: https://www.zolo.ca/legal-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zolo\naid: zolo\nurl: https://www.zolo.ca/legal-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: We provide Zolo for use only by persons located in Canada, excluding Quebec.\nentity_types:\n- type: business\n  text: IF YOU ARE USING ZOLO ON BEHALF OF ANOTHER PERSON OR A CORPORATE ENTITY, YOU REPRESENT AND WARRANT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH PERSON OR ENTITY TO THESE TERMS OF USE.\nrestricted_uses:\n- summary: Competing offering\n  text: use Zolo for the purpose of building a similar or competitive offering\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: Real estate boards require a verified email prior to accessing full listing data including sold prices.\nminimum_age:\n  value: legal age of majority in your jurisdiction\n  text: (I) YOU HAVE REACHED THE LEGAL AGE OF MAJORITY IN YOUR JURISDICTION\n"
source_yaml_url: https://artifacts.apis.io/zolo/eligibility/zolo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Zolo's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Canada
- Property Listings
- MLS
- IDX
- Valuation
- AVM
- PropTech
- Rentals
- Mortgage
- Conveyancing
---
