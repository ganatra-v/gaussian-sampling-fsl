# [ICCVW] Logarithm-transform aided Gaussian sampling for Few-Shot Learning
Code implementation of the paper -  Logarithm-transform aided Gaussian sampling for Few-Shot Learning [(arXiv)](https://arxiv.org/abs/2309.16337)

The pretrained checkpoints can be downloaded from - https://drive.google.com/drive/folders/1IjqOYLRH0OwkMZo8Tp4EG02ltDppi61n?usp=sharing

## Running the scripts
1) Set up a virtual environment and install the dependencies by running `pip install -r requirements.txt`
2) Download the pretrained weights from the checkpoints above, and place them in a `checkpoints` folder in the VI-Priors folder
3) Run distribution calibration by running - `python3 evaluate_dc.py`
4) Run gaussian-sampling by running `python3 gaussian_sampling.py`

## Citing
If you are using the code/method in your work, please cite the following paper - 

    
    @InProceedings{Ganatra_2023_ICCV,
    author    = {Ganatra, Vaibhav},
    title     = {Logarithm-Transform Aided Gaussian Sampling for Few-Shot Learning},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV) Workshops},
    month     = {October},
    year      = {2023},
    pages     = {247-252}

## References

1) Free Lunch for Few-shot Learning: Distribution Calibration - https://arxiv.org/abs/2101.06395
2) https://github.com/ShuoYang-1998/Few_Shot_Distribution_Calibration/tree/master
3) https://github.com/nupurkmr9/S2M2_fewshot
