# Stacked Ensemble of Fine-Tuned DCNNs for Knee Osteo-Arthritis Severity Grading

This work is done by Team TAJ as part of course project for DA221M Jan-May 2024 IIT Guwahati.

Team Members: <br>
    Tanvi Doshi 220101102 \
    Adarsh Gupta 220101003 \
    Japleen Kaur 220106035

This directory contains the code for the project titled: 

    Stacked Ensmeble of Fine-Tuned DCNNs for Knee Osteo-Arthritis Severity Grading

All these notebooks were run on Kaggle with the appropriate settings, all links to these publicly avalaible notebooks are located in the cooresponding folders.

The division of methodology, and the cooresponding location of code:
1. Dataset Preprocessing: ./PreprocessingInput/
2. Fine Tuning DCNNs:
    1. For Multiclass classification task: ./FineTuneCNNs/Multiclass/ contains code of fine tuning of the various different models
    2. For Binary classification task: ./FineTuneCNNs/Binary/ contains code of fine tuning of the various different models
3. Stacked Ensemble:
    1. Generate predictions on all datasets of good performing models: ./FineTuneCNNs/misc./
    2. For Multiclass classification task: ./StackingEnsemble/Multiclass/ contains code for fine tuning of various metalearners
    3. For Binary classification task: ./StackingEnsemble/Binary/ contains code for fine tuning of various metalearners
