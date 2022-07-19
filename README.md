# healthcare-data
Best of healthcare data

### Tools / searchable engines
- Drug (ATC - NDC), genomic, diseases (ICD-9:ICD-11), genomic, and more
    - KEGG: https://www.kegg.jp/ AND https://www.kegg.jp/kegg/brite.html 
    - MONDO: Disease mappings: https://github.com/monarch-initiative/mondo
- Government Data US (focuses on open source government datasets (healthdata.gov, cdc.gov, etc...): https://www.find.nhit.org 
- SNOWMED searchable: https://browser.ihtsdotools.org/?
- Relational search tool (athena - via ohdsi.org - / 'Odyssey': https://athena.ohdsi.org/search-terms/start AND https://www.ohdsi.org 
- Tools from US government agencies (HHS, CDC, etc...): https://code.gov/agencies
- Other health data / aggregator: https://ghdx.healthdata.org/

### Synthetic Data 
- Synthea: https://github.com/synthetichealth/synthea 

### Open source tools 
- Symptom to condition check - https://github.com/hantswilliams/medical-symptom-checker 

### Services 
- Particle Health - https://www.particlehealth.com/
- Better Platform - Build healthcare apps - https://platform.better.care/sandbox 
- DrChrono API Platform - https://www.drchrono.com/api/ 
- Bluebutton CMS - https://bluebutton.cms.gov/developers/ 
- Humana Data Exchange - https://developers.humana.com/apis/registerapp 
- Redux API - https://www.redoxengine.com/product/fhir-api/ 
- Morf (dr.P clone) - https://www.morf.health/

### Assessments 
- SDoH, mental health, substance use disorders, etc... -> https://www.phenxtoolkit.org/  
- CMS quality measure inventory -> https://cmit.cms.gov/cmit/#/ 
- AHRQ - Health Tech Assessments -> https://digital.ahrq.gov/health-it-tools-and-resources/evaluation-resources/health-it-survey-compendium-search 
- AHRQ time motion - https://digital.ahrq.gov/time-and-motion-studies-database 

### Unique open source datasets 
- All of Us (NIH) - genetric, PRO, environmental, social, etc...  - https://databrowser.researchallofus.org/
- Mimic - ICU-like data - https://physionet.org/content/mimiciii-demo/1.4/ 
- CMS - open payments - https://www.cms.gov/OpenPayments/Data/Dataset-Downloads 
- CMS - medicare claims public use files (PUF) - https://www.cms.gov/Research-Statistics-Data-and-Systems/Downloadable-Public-Use-Files/BSAPUFS 

### APIs 
- FDA open APIs 
  - Open FDA: https://open.fda.gov/apis/
  - FDA: Drug Side effects, product labeling
      - https://open.fda.gov/apis/drug/event/
      - https://dailymed.nlm.nih.gov/dailymed/
  - National Library Medicine (clinicaltables - ICD, LOINC, NPI, RXnorm, and many more)
      - https://clinicaltables.nlm.nih.gov/ 
      - For more NLM, go here and filter for APIs: https://eresources.nlm.nih.gov/nlm_eresources/ 

3. Drug Classes (NLM) 
  - https://lhncbc.nlm.nih.gov/RxNav/APIs/RxClassAPIs.html
4. Nutrition
  - https://www.nutritionix.com/

### Open sourced ML 
1. Radiology related 
  - https://www.acrdsi.org 

2. Generic 
  - https://the-algorithms.com/category/machinelearning 


### ML test data healthcare 
1. Medical Imaging  
  - Stanford: https://aimi.stanford.edu/shared-datasets
  - NYU Langone Health: https://fastmri.med.nyu.edu/ 
      - Facebooks code for NYU langone data: https://github.com/facebookresearch/fastMRI





# To organize:

Healthcare: 
  - https://www.nature.com/articles/s41746-022-00557-1 
  - https://www.nature.com/articles/s41587-021-01145-6 
  - https://jamanetwork.com/journals/jama/article-abstract/2788483 
  - Brain imaging tools: 
    - https://github.com/fepegar/torchio 
    - Zip code better then genetics -> https://medcitynews.com/2021/08/zip-codes-have-become-a-better-predictor-of-health-outcomes-than-genetic-codes-technology-may-be-ready-to-fix-that/ 
   - Statistical tests
      - https://link.springer.com/article/10.1007/s10654-016-0149-3 
   -  ML best practices
      -  FDA 
        -  https://www.fda.gov/medical-devices/software-medical-device-samd/good-machine-learning-practice-medical-device-development-guiding-principles 
        -  https://www.fda.gov/medical-devices/software-medical-device-samd/artificial-intelligence-and-machine-learning-aiml-enabled-medical-devices 
        -  Action plan - > https://www.fda.gov/media/145022/download 
        - Digital health reports -> https://www.fda.gov/medical-devices/digital-health-center-excellence/digital-health-reports 
   - Clinical Knowledge graph (contains tons of APIs/open data to capture) 
            - https://github.com/MannLabs/CKG 
   - Interoperability: 
            - https://smarthealthit.org/ 
            - USCDI: https://www.healthit.gov/isa/united-states-core-data-interoperability-uscdi 
            - SAFER - https://www.healthit.gov/topic/safety/safer-guides 
   - Case Studies:
            - https://www.healthit.gov/case-studies
            - https://www.ahrq.gov/news/newsroom/case-studies/index.html 
   - Enrichment of geographic data: 
            - General data by zipcode 
                - https://censusreporter.org/ 
                - https://github.com/censusreporter/census-api/blob/master/API.md 
                    - Demographics
                    - Economics
                    - Families
                    - Housing
                    - Social
                    - Health insurance 
                    - Poverty (food stamps / SNAP) 
            - Disparities ->
                - https://www.neighborhoodatlas.medicine.wisc.edu/ 
                - https://www.countyhealthrankings.org/ 
                
                
EMRS:
Behavioral health specific:
valant emr (https://www.valant.io)
eleos health - https://eleos.health
blue print health - https://www.blueprint-health.com
luminello - https://luminello.com
kipu health -https://kipuhealth.com
opus health - https://www.opusbehavioral.com/ehr
alleva - https://helloalleva.com (know these guys, somewhat competitor to inrecovery platform which I have access to)
sessionshealth - https://www.sessionshealth.com/pricing - interesting thing here -> free level that we could use
therapy notes (https://www.therapynotes.com)
next-gent EMR/headless:
canvas EMR (
@Nick Foden
 - know the founder here, this is a 'headless' EMR where WE build the frontend, and they provide all APIs/backend to then make it functioanl; so its like a hybrid approach, we build and use what we want/need - i dont know any other company like this yet)
modern cloud-first on AWS that are well established for small clinics:
https://www.elationhealth.com/ehr/
https://www.drchrono.com 
younger/new that are still startup phase:
https://www.akutehealth.com
generic/small practice EMRs:
kareo emr (https://www.kareo.com)
non-EMR/complementary for mental health:
patient success - https://www.lumahealth.io


Healthcare Icons
- https://healthicons.org/

Pose Estimation  
- Movement - https://github.com/akshaybahadur21/GymLytics 
- Bed Position - https://web.northeastern.edu/ostadabbas/2019/06/27/multimodal-in-bed-pose-estimation/ 
- Instructional - https://www.analyticsvidhya.com/blog/2022/01/a-comprehensive-guide-on-human-pose-estimation/ 
- Summary of librarires - https://medium.datadriveninvestor.com/top-and-best-computer-vision-human-pose-estimation-projects-186d04204dde 
