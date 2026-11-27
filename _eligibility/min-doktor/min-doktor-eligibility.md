---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Kunden ska vara folkbokförd i Sverige is not stated; page mentions regions in Sweden only as e-frikort context.
  minimum_age:
    text: Kunden måste vara minst 16 år för att vara en registrerad användare av och nyttja Tjänsten.
    value: '16'
  restricted_uses:
  - summary: Emergencies directed elsewhere
    text: Tjänsten är inte till för att användas vid situationer som kan upplevas som akuta eller med mycket allvarliga och hastigt påkomna symtom. I sådana situationer ska Kunden ringa 1177 eller i akuta situationer 112.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: För att kunna använda Tjänsten måste Kunden kunna legitimera sig med e-legitimation (BankID eller Mobilt BankID).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Min Doktor
provenance_date: '2026-11-10'
provider_name: Min Doktor
provider_slug: min-doktor
slug: min-doktor-eligibility
source_date: '2026-11-10'
source_filename: min-doktor-eligibility.yml
source_heading: Eligibility
source_page: https://www.mindoktor.se/anvandarvillkor/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Min Doktor\naid: min-doktor\nurl: https://www.mindoktor.se/anvandarvillkor/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Kunden ska vara folkbokförd i Sverige is not stated; page mentions regions in Sweden only as e-frikort context.\nentity_types: []\nrestricted_uses:\n- summary: Emergencies directed elsewhere\n  text: Tjänsten är inte till för att användas vid situationer som kan upplevas som akuta eller med mycket allvarliga\n    och hastigt påkomna symtom. I sådana situationer ska Kunden ringa 1177 eller i akuta situationer 112.\nverification:\n  kyc: true\n  kyb: null\n  approval_required:\
  \ null\n  text: För att kunna använda Tjänsten måste Kunden kunna legitimera sig med e-legitimation (BankID eller Mobilt\n    BankID).\nminimum_age:\n  value: '16'\n  text: Kunden måste vara minst 16 år för att vara en registrerad användare av och nyttja Tjänsten.\n"
source_yaml_url: https://artifacts.apis.io/min-doktor/eligibility/min-doktor-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Min Doktor's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health Tech
- Telehealth
- Digital Health
- Primary Care
- Healthcare
- Sweden
---
