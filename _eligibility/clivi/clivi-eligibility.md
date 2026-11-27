---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    text: Los Términos y Condiciones están dirigidos primordialmente a las personas físicas y/o morales que se encuentren en el territorio de los Estados Unidos Mexicanos ("México")
  entity_types:
  - text: Todos los Usuarios y/o Clientes declaran que cuentan con capacidad para contratar.
    type: individual
  - text: En el caso que el Cliente reciba los Servicios a través de la contratación por parte de su empleador y/o empresa
    type: business
  minimum_age:
    text: Únicamente podrán solicitar la habilitación de una Cuenta de Usuario las personas que tengan mayoría de edad, es decir, 18 (dieciocho) años cumplidos.
    value: '18'
  restricted_uses:
  - summary: Minimum BMI for weight-control service
    text: Para acceder al Servicio de control de peso, el Cliente deberá tener un Índice de Masa Corporal (IMC) mínimo de 27 kg/m2.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Los Usuarios deberán proporcionar la información personal correspondiente en todos los campos, con datos válidos, precisos y veraces.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clivi
provenance_date: '2026-11-09'
provider_name: Clivi
provider_slug: clivi
slug: clivi-eligibility
source_date: '2026-11-09'
source_filename: clivi-eligibility.yml
source_heading: Eligibility
source_page: https://www.clivi.com.mx/terminos-y-condiciones/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clivi\naid: clivi\nurl: https://www.clivi.com.mx/terminos-y-condiciones/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - MX\n  excluded: []\n  text: Los Términos y Condiciones están dirigidos primordialmente a las personas físicas y/o morales que se encuentren\n    en el territorio de los Estados Unidos Mexicanos (\"México\")\nentity_types:\n- type: individual\n  text: Todos los Usuarios y/o Clientes declaran que cuentan con capacidad para contratar.\n- type: business\n  text: En el caso que el Cliente reciba los Servicios a través de la contratación por parte de su empleador y/o\n    empresa\nrestricted_uses:\n\
  - summary: Minimum BMI for weight-control service\n  text: Para acceder al Servicio de control de peso, el Cliente deberá tener un Índice de Masa Corporal (IMC) mínimo\n    de 27 kg/m2.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Los Usuarios deberán proporcionar la información personal correspondiente en todos los campos, con datos\n    válidos, precisos y veraces.\nminimum_age:\n  value: '18'\n  text: Únicamente podrán solicitar la habilitación de una Cuenta de Usuario las personas que tengan mayoría de\n    edad, es decir, 18 (dieciocho) años cumplidos.\n"
source_yaml_url: https://artifacts.apis.io/clivi/eligibility/clivi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Clivi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Telehealth
- Digital Health
- Diabetes
- Obesity
- GLP-1
- Mexico
---
