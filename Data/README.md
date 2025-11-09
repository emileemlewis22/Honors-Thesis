# Honors Thesis: Duke Hospital Neonatal Intensive Care Unit (NICU) Dataset

## Description
This dataset includes de-identified records derived from a simulated neonatal intensive care unit (NICU) model based on Duke University Hospital data. It captures key clinical and demographic variables used to examine relationships between neonatal outcomes, hospital resource use, and length of stay.

## Format
The dataset contains **4,350 rows**, each representing an infant, and **12 columns** (variables):

| Variable                      | Description
|:----------------|:------------------------------------------------------------------
|`patient_id`                   | De-identified, randomized patient identification number assigned to each infant
|`survival_status`              | Whether the infant was alive or deceased at the time of discharge
|`gestational_age`              | Gestational age at birth (in weeks)
|`birth_weight`                 | Birth weight of the infant (in grams)
|`gender`                       | Sex of the infant
|`inborn`                       | Whether the infant was born at Duke Hospital or transferred from another facility (`Yes`, `No`)
|`race_ethnicity`               | Racial/ethnic classification of the infant (`White`, `Black`, `Other`)
|`length_of_stay`               | Total length of stay (in days) from admission to discharge or death
|`ivh`                          | Presence or grade of intraventricular hemorrhage (IVH), bleeding into the internal structures of the brain (`None`, `Grade I`, `Grade II`, `Grade III`, `Grade IV`)
|`rop`                          | Presence or stage of retinopathy of prematurity (ROP), a condition affecting blood vessels in the eye that leads to blindness if not promptly treated (`None`, `Stage I`, `Stage II`, `Stage III–IV (No Cryo or Laser Surgery)`, `Stage III–IV (With Cryo or Laser Surgery)`)
|`nec`                          | Presence or type of necrotizing enterocolitis (NEC), a severe neonatal intestinal condition (`None`, `Medical`, `Surgical`)
|`pda`                          | Presence and management of patent ductus arteriosus (PDA), a neonatal cardiovascular anomaly requiring medical or surgical intervention (`None`, `None (Medication Only)`, `Yes (Medically Treated)`, `Yes (Ligated)`, `Yes (Untreated)`)

## Source
This dataset was provided by Dr. Chris DeRienzo alongside collaborators at Duke University Hospital and SAS Institute. It is derived from a neonatal intensive care unit (NICU) simulation model developed to study relationships between patient outcomes, resource use, and length of stay.
