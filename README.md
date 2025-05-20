# 🧬 CNN for Histopathology — XAI on PatchCamelyon

This project uses the PatchCamelyon dataset to train a CNN that classifies image patches as cancerous or non-cancerous. Multiple explainability techniques — including Grad-CAM, saliency maps, occlusion sensitivity, and integrated gradients — are applied to interpret model decisions. Grad-CAM consistently highlights tumor regions, while comparative metrics (insertion and deletion) validate its superiority over other XAI methods.

Concerning the Data, a reduced version (50,000 images) was used with custom PyTorch loaders for efficient training. They are available at this link : https://github.com/basveeling/pcam

To run the analysis, open and execute the notebook `TP2_DAVID_FAYNOT.ipynb` in Jupyter Notebook or JupyterLab.

