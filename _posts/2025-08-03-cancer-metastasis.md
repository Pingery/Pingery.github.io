# Liquid Biopsy for Cancer Metastasis Detections

## What is cancer metastasis?
- Cancer cells spread from the primary tumor site to form new tumors in distant organs or tissues.
- It is not random: cancer cells often spread to specific organs (e.g breast cancer commonly spreads to bone, brain, lung, liver) --- called organotropism
- Cancer cells after metastasis are still the same tyoe. (e.g breast cancer cells in the brain are not brain cancer)
- Metastasis is responsible for the vast majority of deaths (>90%)

## Key steps in metastasis
- Local invasion
  - EMT
  - Breakdown of basement membrane
- Intravasation
  - Entry into blood or lymph vessels
  - Role of tumor-associated macrophages (TAMs) 
- Circulation (CTCs)
  - Circulating tumor cells face immune attack and shear stress
  - Often travel in clusters
- Extravasation
- Colonization

## How to detect metastassi
- Usually through image such as CT scan, MRI, etc.
- Very expensive and a lot of effort to send a patient through image scans.

## Detect Circulating Tumor Cells (CTCs)
- Idea of the existence of CTCs was proposed a long time ago
- 1990s-2000s: CTC detection re-emerged, especially with the development of enrichment and detection platforms using nanotechnology.
- In 2004, the CellSearch system (Veridex) became the first FDA-cleared teset for enumerating CTCs in metastatic breast, prostate, and colorectal cancers.

## What is inside blood?
- Red blood cells (RBCs) are by far the most numerous (~4.5-6 million per mL).
  - Has no nucleus
- White blood cells (WBCs) are far fewer (~4,000-11,000 per mL).
  - Has nucleus, diverse types, larger than RBC
- Platelets are intermediate (~150,000-450,000 per mL).
  - No nucleus, cell fragments
- CTCs (if present in cancer patients) occur at <10 cells per mL of blood - extremely rare).
  - Has nucleus, cell origins, often epithelial, larger than RBC
 
## CellSearch
- In 2004, the CellSearch system (Veridex) became the first FDA-cleared test for enumerating CTCs in metastatic breast, prostate, and colorectal cacners.
- It is the first and only clinically validated, FDA-cleared blood test for enumerating circulating tumor cells.
- As of late 2016, when Menarini Silicon Biosystems acquired the CellSearch CTC business from Janssen Diagnostics (previously Veridex), it was reported that approximately 300 laboratories worldwide were actively using CellSearch.

## How does enumerating the number of CTCs help?
- Enrolled 177 mBC patients.
- Kaplan-Meyer plot for overall survival for enrolled patients./
  - Patients with <5 CTCs overall survival is 21.9 months.
  - Patients with >5 CTCs have an overall survival of 10.9 months.
- Number of CTCs impact the overall survival

## Kaplan-Meier plot
- A statistiacl method to estimate the probability of an event occurring at different points in time
- Frequently used for clinical trials to observe treatments effectiveness
- Survival curve is generated (non-parametric) by observing "events (i.e deaths) at time intervals
- Tou need to follow up patients and know their survival time

## Liquid biopsy
- A liquid biopsy is a test done on a sample of blood (or sometimes other fluids like uring or cerebrospinal fluid) to detech diseases (for example cancer metastasis)
- CellSearch system is one kind of liquid biopsy technology
- There are other technology platforms developed

## Why Liquid Biopsy in Metastasis?
- Metastatic tumors are often hard to reach
- Metastatic burden is dynamic, and liquid biopsy allows repeated sampling over time.
- It provides a non-invasive snapshot of the tumor evolution, heterogeneity, and treatment resistance.

## What can Liquid Biopsy Detect?
- CTCs
- ctDNA
- cfRNA
- Exosomes / EVS
- Tumor-Educated Platelets

## Parsotix versus CellSearch
- CellSearch capture CTCs via anti-EpCAM. This is a major limitation. Some cancer types do not have EpCAM expression.
- Parsortix use microfluidic and cell deformability.
  - Tumor cells are larver and less deformable than blood cells

## ctDNA
- Circulating tumor DNA: fragments from DNA released by tumor into blookd stream
- The company focused on developing detection of ctDNA Guardant Health
- Guardant Health was co-founded by Helmy Eltoukhy and AmirAli Talasaz during 2012-2013; both got Ph.D from Stanford

## Future of Liquid Biopsy
- Transforming cancer detection and monitoring
- From late detection to early detection
- Real-time monitoring of tumor evolution
- Non-invasive and broadly accessible
- Integration with Big Data: Enabling precision Medicine

# Kaplan-Meier Plots Created in Jupyter Notebook
<img width="891" height="602" alt="Screenshot 2025-08-03 at 3 13 13 PM" src="https://github.com/user-attachments/assets/64af8ebd-589d-4c35-a98d-dbb2c5efdc03" />
<img width="873" height="599" alt="Screenshot 2025-08-03 at 3 13 02 PM" src="https://github.com/user-attachments/assets/a538679e-b14e-494f-aa89-0281b590352e" />


