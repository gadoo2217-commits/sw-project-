# sw-project-
Open `SW_PRO_FINAL.ipynb` in Google Colab.
Select Runtime > Change runtime type > T4 GPU (or another compatible NVIDIA GPU).
Select Runtime > Run all to execute the cells in order. The first cell installs the required Python packages.
When prompted, upload these three Excel files together:
`Anaphoric.xlsx`
`Coordination.xlsx`
`MissingCondition.xlsx`
Keep the Colab session connected while the model loads and all three experiments run. The notebook performs 972 predictions in total and may take considerable time.
Wait until the evaluation finishes and the notebook generates the four output files:
`Qwen_ZeroShot_Results.xlsx`
`Qwen_FixedFewShot_Results.xlsx`
`Qwen_DynamicFewShot_Results.xlsx`
`Qwen_Final_Comparison.xlsx`
Download the four files when Colab prompts you. If automatic downloads are blocked, download them from the Colab Files panel.
Note: If the runtime disconnects, reconnect and rerun the notebook. Existing checkpoint CSV files can resume an experiment only when the same dataset, split, model, and prompts are used; for a fresh reproducible run, use a clean runtime without old checkpoints.
