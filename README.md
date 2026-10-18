# Disaster_sentiment_analysis

## 1. Set Up the Environment

### Step 1: Prepare the Workspace

```bash
cd $SCRATCH
cp -r /scratch/training/hf_senti $SCRATCH
module purge
```

### Step 2: Create a Python Virtual Environment with ModuLair

```bash
modulair create hf_env -d "Environment for Disaster Social Media Sentiment Analysis with Hugging Face" -p 3.12.3
```

### Step 3: Activate the Virtual Environment

```bash
source modulair activate hf_env
```

### Step 4: Install the Required Packages

```bash
pip3 install jupyter pandas matplotlib
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/xpu
pip3 install transformers
```

### Step 5: Deactivate the Virtual Environment (When Finished)

```bash
# source modulair deactivate
```

**Note:** Use the `hf_env` environment for this notebook. Do not use `geo_ai_env`.
