# Abstract
This study proposes a novel Few-Shot Class-Incremental Learning (FSCIL) methodology that reduces dependency on base session training and effectively learns new classes from limited data. Our approach leverages a pre-trained Vision Transformer with meta-training to maximize the model's generalization performance, while also incorporating a Neural Collapse Loss to enhance learning efficiency. Furthermore, we apply Low-Rank Adaptation (LoRA) to the fully-connected (FC) layer to mitigate the problem of catastrophic forgetting.  
  
On the CIFAR-100 dataset, the proposed method achieves an approximate 5% performance improvement over the baseline while using only 4.167% of the total data. This demonstrates a significant reduction in the data and resources required to learn new classes in an FSCIL environment. These results highlight the practical applicability of our method in data-constrained settings and offer a new direction for the FSCIL field.
# Meta-Model
<img width="895" height="601" alt="Image" src="https://github.com/user-attachments/assets/328e7a1a-efc4-4e71-8bc6-9a439d9b5cf1" />

# Run the Meta-Model
    run_script/vit_run_pretrain.sh
# Requirements
    pip install requirements.txt
Dataset must be downloaded and placed under directory "local_datasets".
