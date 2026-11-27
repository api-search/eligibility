---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harm to minors
    text: Πρόκληση βλάβης σε ανήλικους με οποιοδήποτε τρόπο.
  - summary: Impersonation
    text: Mίμηση οποιουδήποτε νομικού ή φυσικού προσώπου ή ψευδής δήλωση για την ταυτότητα του χρήστη/μέλους
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: το οποίο δεν δημοσιεύεται, απλά χρησιμοποιείται στο πλαίσιο της επαλήθευσης των χρηστών
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BestPrice Agent Commerce
provenance_date: '2026-11-09'
provider_name: BestPrice Agent Commerce
provider_slug: bestprice
slug: bestprice-eligibility
source_date: '2026-11-09'
source_filename: bestprice-eligibility.yml
source_heading: Eligibility
source_page: https://www.bestprice.gr/policies/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BestPrice Agent Commerce\naid: bestprice\nurl: https://www.bestprice.gr/policies/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harm to minors\n  text: Πρόκληση βλάβης σε ανήλικους με οποιοδήποτε τρόπο.\n- summary: Impersonation\n  text: Mίμηση οποιουδήποτε νομικού ή φυσικού προσώπου ή ψευδής δήλωση για την ταυτότητα του χρήστη/μέλους\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: το οποίο δεν δημοσιεύεται, απλά χρησιμοποιείται στο πλαίσιο της επαλήθευσης των χρηστών\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bestprice/eligibility/bestprice-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from BestPrice Agent Commerce's own page on 2026-11-09.
synthetic: false
tags:
- Shopping
- Price Comparison
- E-Commerce
- Retail
- MCP
- WebMCP
- Agentic Commerce
- Greece
- Product Recommendations
- Shopping Decisions
- Delivered Price
---
