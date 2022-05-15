# DeepLearningTheoremProving
This repo contains implementation of transformer-based network, created for ATP on the HOLStep dataset.
Implementation was created for the term projecm for the CIS-700 "Deep leaning and automated theorem proving".

For reproducibility purposes please import anaconda environment from the file environment.yml

## Important
In case if dataloader freezes in the notebook, please set num_workers in the DataLoader constructor to 0. This behavior is a known problem that happens with multiprocessing in Pytorch (https://discuss.pytorch.org/t/dataloader-iteration-hang-up/12886/2, https://github.com/pytorch/pytorch/issues/1579 ). Setting up num_workers=0 will fix this problem. Problem was reported under Windows, so it might not be relevant for other systems.
