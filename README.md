# Navigating the Fragrance space Via Graph Generative Models And Predicting Odors
![Research Paper Overview (7)](https://github.com/user-attachments/assets/daf1ae2d-228d-4223-951f-0176de78d419)
<div align="justify"> We introduce a suite of generative modelling techniques to efficiently navigate and explore the complex landscapes of odor and the broader chemical space. The whole process involves four key stages: molecule generation, stringent sanitization checks for molecular validity, fragrance likeliness screening and odor prediction of the generated molecules. </div>

<br> The website developed for this work is available at [Exploring Fragrance Space using Generative Models](https://kumars8494.github.io/Exploring_Fragrance_Space_with_Generative_model/)</br>

# Getting started
Creating environment:
<br><code>conda create --name my_env --file requirements.txt</code></br>

# Data
The folder [data](https://github.com/CSIO-FPIL/generative-odor/tree/main/data) contains the results of different statistical tests on the distribution of generated molecules, organized by model in sub-folders named [ARGA](https://github.com/CSIO-FPIL/generative-odor/tree/main/data/ARGA), [ARGVA](https://github.com/CSIO-FPIL/generative-odor/tree/main/data/ARGVA), [diffusion](https://github.com/CSIO-FPIL/generative-odor/tree/main/data/Diffusion), <code>GAE</code>, <code>Transformer</code>, and <code>VGAE</code>. Each of these model folders includes <code>GDB Criteria</code>, <code>KS_test</code>, and <code>rule of three</code>.

# Dataset for Training
The folder named <code>curated dataset</code> in [data](https://github.com/CSIO-FPIL/generative-odor/tree/main/data) has the training data for the models and is available in two formats: <code>curated_GS_LF_merged_cleaned.csv</code> (CSV) and <code>cleaned_frag_pyg_dataset.pth</code> (PyTorch).

The above mentioned PyTorch data is created using: <code>Pyg_data_creator_for_cleaned.ipynb</code>.

# Models
Example notebooks for model training and fine tuning are available in [models](https://github.com/CSIO-FPIL/generative-odor/tree/main/models).

# Odor likeliness Equation
Unlike traditional approaches, we not only generate molecules but also predict the odor likeliness and classify probable odor labels. We show that odor likeliness is a function of physicochemical features. Additionally, we identify the most relevant features to construct an odor likeliness equation and leverage SHAP (SHapley Additive exPlanations) to demonstrate the interpretability of the work. 

# Figures
All the figures used in the paper are available in teh [figures](https://github.com/CSIO-FPIL/generative-odor/tree/main/figures) folder. 

# Contributors
**Mrityunjay Sharma**, CSIR-CSIO, Chandigarh, India                
**Sarabeshwar Balaji**, Indian Institute of Science Education and Research Bhopal(IISERB), India <br>
**Pinaki Saha**, University of Hertfordshire, UH Biocomputation Group, United Kingdom <br>
**Ritesh Kumar**, CSIR-CSIO, Chandigarh, India
