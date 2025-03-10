# Feedback Prize Competition – DeBERTa-v3-large Approach

This repository contains our solution for the Kaggle Feedback Prize competition. We leverage the DeBERTa-v3-large model along with advanced pooling techniques and optimized training schedules to generate robust text representations and achieve competitive performance.

## Overview

- **Hybrid Pooling Strategy**:  
  The model utilizes a combination of **MeanPooling** and **MaxPooling** to extract robust text features and dynamically aggregate hidden states through layer-weighted pooling.

- **Optimized Learning Rate Scheduling**:  
  A **polynomial decay scheduler with warmup** is employed. The encoder and decoder are optimized separately with distinct configurations to ensure precise control over model training.

- **Performance**:  
  This approach achieves an **MCRMSE score of 0.47** on the validation set.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/feedback-prize-deberta-v3.git
   cd feedback-prize-deberta-v3
