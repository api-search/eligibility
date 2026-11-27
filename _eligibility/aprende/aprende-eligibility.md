---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: No puede acceder a nuestros Servicios si se encuentra en un territorio donde las empresas de los EE. UU. tengan prohibido realizar negocios (como Cuba, Irán, Corea del Norte, Sudán o Siria)
  minimum_age:
    text: declara que tiene al menos 18 años de edad
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: No puede acceder ni utilizar los Servicios ni crear una cuenta con propósitos ilegales.
  - summary: Educational services to others
    text: Usted no puede usar los Servicios para proporcionar servicios educativos a otras personas.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Nosotros podemos limitar la cantidad de dispositivos en los que puede utilizar el Servicio, o solicitar la verificación en dos pasos (2-Step Verification) de nuevos dispositivos.
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aprende
provenance_date: '2026-11-09'
provider_name: Aprende
provider_slug: aprende
slug: aprende-eligibility
source_date: '2026-11-09'
source_filename: aprende-eligibility.yml
source_heading: Eligibility
source_page: https://aprende.com/terminos-y-condiciones/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aprende\naid: aprende\nurl: https://aprende.com/terminos-y-condiciones/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: No puede acceder a nuestros Servicios si se encuentra en un territorio donde las empresas de los EE. UU.\n    tengan prohibido realizar negocios (como Cuba, Irán, Corea del Norte, Sudán o Siria)\nentity_types: []\nrestricted_uses:\n- summary: Illegal purposes\n  text: No puede acceder ni utilizar los Servicios ni crear una cuenta con propósitos ilegales.\n- summary: Educational services to others\n  text: Usted no puede usar\
  \ los Servicios para proporcionar servicios educativos a otras personas.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Nosotros podemos limitar la cantidad de dispositivos en los que puede utilizar el Servicio, o solicitar\n    la verificación en dos pasos (2-Step Verification) de nuevos dispositivos.\nminimum_age:\n  value: '18'\n  text: declara que tiene al menos 18 años de edad\n"
source_yaml_url: https://artifacts.apis.io/aprende/eligibility/aprende-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Aprende's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- E-Learning
- Vocational Training
- Online Courses
- EdTech
- Spanish
- Latin America
---
