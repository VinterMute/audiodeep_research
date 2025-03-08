# Audio Embeddings Visualization  

This repository provides tools for vectorization and visualization of audio embeddings.  

## Quick Start  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/VinterMute/audiodeep_research.git
cd audiodeep_research
```

### 2️⃣ Run the Visualization  
The **`audio_embeddings_visualization.html`** file works directly in your browser—just open it!  

### 3️⃣ Set Up the Environment (for Vectorization)  
If you need to perform vectorization, create a Conda environment:  
```bash
conda env create -f environment.yml
conda activate your_env_name  # Replace with the environment name
```

### 4️⃣ Download the Required Model  
The project requires a pre-trained model. Download it using:  
```bash
wget --content-disposition -O music_speech_epoch_15_esc_89.25.pt "https://huggingface.co/lukewys/laion_clap/resolve/main/music_speech_epoch_15_esc_89.25.pt"
```