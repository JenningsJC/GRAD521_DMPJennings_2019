# Data Description

The aquatic food web in: 1)a restored lower reach and 2)an unrestored upper reach of the South Fork McKenzie River will be sampled 4 times a year beginning in the Spring of 2019. Fish, aquatic primary producers, benthic invertebrates, organic detritus, and riparian vegetation will be sampled. 5 replicate samples will be taken in each habitat unit (main channel, side channel, slow water, etc.), using stratified sampling within each unit to sub-sample across the distribution of sub-patches (riffles, pools,...), proportionally to their overall cover. In this way, each replicate sample will consist of 3 to 8 sub-samples that will be aggregated.

**Dataset Types and Method of Collection**

*Field Sample Collection Data Sheets:* Data sheets will record metadata while taking samples, such as date, time, geographic location, taxa sampled, personnel, equipment, reach, habitat unit, sub-patch descriptor, sample measurements, sample container numbers, and a data dictionary for preferred codes, names, and formats.

*Fish Survey Data Sheets:* Fish populations in each habitat unit will be sampled using snorkel surveys, minnow traps, seine nets, electro-fishing, and other methods to be determined. Species and abundance data will be recorded on data sheets, along with weights and total lengths for each captured fish.

*Fish Specimens:* 5 non-salmonid fishes (per reach) <65mm in total length, will be captured via netting, electro-fishing or minnow trapping, total length and weight taken, and then euthanized and stored in ethanol solution in individual jars for transport to the lab for analysis of stomach contents. Each container will be labeled externally, and a data label placed inside the container with the sample number and date, reach, habitat unit, sub-patch, and taxon.

*Fish Stomach Content Samples:* All fish >65mm in total length will be captured via angling, netting, or electro-fishing and stomach contents evacuated via gastric lavage. Contents will be stored in ethanol solution and transported to the lab for processing. Each container will be labeled externally, and a data label placed inside the container with the sample number and date, reach, habitat unit, sub-patch, and taxon.

*Fish Tissue Samples:* Fin clips will be taken from all species of fishes captured and preserved in ethanol solution. Each container will be labeled externally, and a data label placed inside the container with the sample number and date, habitat unit, sub-patch, and taxon.

*Periphyton and Aquatic Primary Producer Samples:* Periphyton will be scraped from rocks, wood, algal mats and aquatic macrophytes into a bottomless bucket and water samples filtered over glass filters, frozen and stored in the dark for chlorophyll a and stable isotope analysis. Each filter container will be labeled externally with the sample number and date, habitat unit, sub-patch, and taxon.

*Dominant Riparian Plant Samples:* Leaf tissue from the dominant riparian plant community will be taken and stored in individual containers for stable isotope analysis. Each container will be labeled externally with the sample number and date, habitat unit, sub-patch, and taxon.

*Benthic Aquatic Invertebrates and detritus:* Surber samplers will be used to collect invertebrate samples from the substrate, sieved in the field to remove large debris, and stored in ethanol solution for transport to the lab. Each container will be labeled externally, and a data label placed inside the container with the sample number and date, habitat unit, sub-patch, and taxa. Debris clumps will be sampled with the surber sampler as well, and samples taken and stored individually for stable isotope analysis.

*Field Sample Collection and Fish Survey Data Sheet Images* Images of each data sheet will be taken with a smartphone at the end of each sample day, backed up to the icloud and sent to the PI for initial quality checks.

*Lab Datasheets:* Invertebrate samples will be identified, counted, measured, weighed, and all data recorded on datasheets. Stomach contents will be similarly processed and data recorded on datasheets.

*Raw Datasets:* Field and lab datasheets will be hand-entered into Excel and exported as .csv files.

*Cleaned Analysis Datasets:* Error-checked raw datasets, subsets or joins, as .csv files ready for analysis.

*Records of Analysis:* tables, graphs, spreadsheets, scripts, isotopic analysis reports, statistical software analysis code, graphics, tables of results, and physical specimens will be generated after samples are dried, isotopes analyzed, and invertebrates identified.

*Workflow:* Scripts in R, JSON or other formats, with metadata or narrative justification.

**Estimated Quantity/Size of Datasets:**
Four sample periods, with 5 replicates for each of 2 reaches = 40 replicate samples. There will be at least 40 field data sheets. If each replicate consists of an average of 5 sub-samples, there will be a minimum of 200 sample containers for invertebrates, primary producers, and detritus, each (600 total). 40 total fish will be euthanized and preserved. At a minimum, 1 GB of .csv files, scripts, and results of analysis.

# Roles and Responsibilities

The graduate researcher will submit the data management plan to the major professor and PI for review, revise, and implement the plan. The graduate researcher will be responsible for sample collection and data entry in the field, and will train field technicians in sampling and data recording protocols and inspect data sheets and sample containers for completeness and accuracy after every sample day. Images will be taken of data sheets with smartphone and emailed to the PI for immediate review and quality checks.

The graduate researcher is responsible for establishing laboratory analysis and data entry protocols, and training assistants in those protocols. Laboratory datasheets will be inspected daily for errors, scanned and sent to the PI for periodic quality checks.

The graduate student is responsible for entering data sheets into spreadsheets and conversion into .csv files for creation of raw datasets. Organization of datasets, datasheets, sample collections, quality control, analysis and backup is the responsibility of the graduate student. Both the PI and the graduate student will be responsible for archiving and preserving datasets, as these data are part of the PI’s multi-year BACI study and will be joined with other data and archived separately at a time yet to be determined.

If the graduate student leaves the project, all datasets and access privileges to the Box backup file will be transferred to the PI, as will all original datasheets and notebooks. Final disposition of physical samples will be noted and given to the major professor and/or samples will be transported to the location of choice of the major professor or PI.

# Data Standards and metadata
All documents, physical or digital, will have the date, time, geographic location, taxa sampled, personnel, equipment, reach, habitat unit, sub-patch descriptor, sample measurements, sample container numbers recorded in a readme or .xml file in EML format. A master data dictionary will be established and used to guide entries on spreadsheets, placed in metadata files, and used for data cleaning with OpenRefine. Files will be stored in a directory with the project name, sample periods, and subfolders for the restored and control reaches, and other appropriate subsection of the project e.g. benthic inverts, periphyton, salmonids, minnows. Raw datasets will be maintained intact, and subsequent versions or subsets labeled sequentially. File names will consist of taxa_reach_habitat_subpatch_description_YYYYMMDD. R scripts or JSON scripts will be stored with the associated results of analysis or datasets.

This project will use the Biological Data Profile (BDP) and the Ecological Metadata Language (EML) metadata standards. The Federal Geographic Data Committee has established the Biological Data Profile (BDP) metadata standard for datasets submitted to federal research data repositories such as the Forest Service Research Data Archive and the USGS repository, where the final data will be archived. I will use the data tool Metavist (2017) to create, edit and export .xml metadata files in the BDP and EML standard.

# Storage and Security
Data consisting of physical samples will be stored in a department laboratory during analysis. Field data sheets, field journals and laboratory journals will be stored in a secure file cabinet in a secure office on the OSU campus. Data sheets and journal pages will be photocopied, with copies stored separately at my residence.

All digital data files will be stored on my work laptop, mirrored and synced to my Box project folder, and backed up automatically to an external drive every evening. Laptop hard drive backup images will also be pushed to the Microsoft cloud monthly.

The PI will create a controlled-access account with the Forest Service Research Data Archive. As raw and cleaned datasets and results of analyses are assembled, they will be checked for quality and accuracy using OpenRefine and transferred to my PI for further quality checks and submittal to the archive.

# Access, Data Sharing, Archiving and Preservation
 During the field sampling year, data will be shared with the other Forest Service researchers involved with the project as .csv files and associated .xml metadata files. A secure Box account will be used to facilitate data sharing, and I will be responsible for version control and ensuring that datasets uploaded for sharing are the most up to date and clearly differentiated from other forms by using distinct file names and providing accurate associated metadata files. If researchers need to share their own analyses or modifications to the provided datasets, these files will be isolated in a separate file from the originals in the Box drive and clearly named and uploaded with current metadata to track the changes made and who made them.

 After final analysis and the publication of the results, the final data collection will be archived and preserved in the Forest Service Research Data Archive, which is publicly accessible. The data will be submitted as .csv files with accompanying .xml files in the EML and BDP metadata formats. This project is a component of a larger project that will continue until at least 2026, so final release of the data to the public will not occur until after this date at the earliest. Preservation will last indefinitely, and future access by the public and other researchers should be assured by the OPEN Government Data Act taking effect in 2020, that directs public agencies to make their data available to the public in machine readable formats.

 All of the physical fish specimens will be transferred to the OSU Fish collection at the end of the project. Aquatic invertebrate specimens will be transferred to the OSU Arthropod collection. Datasheets and journals will be transferred to the Forest Service for archiving and preservation.

Repository with source code [here](https://github.com/clarallebot/GRAD521_DMPtemplate)
