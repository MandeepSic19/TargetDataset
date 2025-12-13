 **Target_Dataset**

 **Dataset Overview**
The 3D point cloud data for each target distance were captured using the UTM-30LX-EW sensor. Depth measurements were processed using **URGBBENRI Plus** software. To ensure accurate measurements, the point clouds were preprocessed using pass-through filtering, outlier removal, and voxel grid downsampling. All preprocessing parameters are documented in the `rqt/` folder. Plane segmentation was applied to extract the target plane, followed by min–max bounding box computation and corner detection to determine the target **Height** and **Width**.

 **Sample Images**
Representative sample images illustrating the captured point clouds and the corresponding Height and Width measurements are provided in the `figures/` folder. These images offer a qualitative overview of the dataset and the measurement workflow.

**Data Availability**
The raw `.pcd` files and associated scripts are available upon request. Interested researchers may submit a request using the Google Form (link below).

Upon approval:
- The requested files will be uploaded to this repository or shared privately, as appropriate.
- A direct GitHub link to the files will be sent to the requester via email.

Please note that data sharing is subject to approval and may take some time.

 **Usage Disclaimer**
This dataset is provided **for academic and research purposes only** and must **not be used for commercial applications**.


 **Reproducibility and Workflow**
All preprocessing steps, software details, and filter parameters required to reproduce the results are documented in the `rqt/` folder.


 **Citation**
If you use this dataset in your work, please cite the following paper:

> *Author(s)*, “*Title of the paper*,” manuscript under review / under preparation.

A formal citation with publication details and DOI will be provided once the paper is published.
