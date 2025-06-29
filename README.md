#DLSS (deep learning super sampling) frame generation 
model -> RIFE


Deep learning-based video frame interpolation
NVIDIA DLSS frame generation uses the GPU to generate frames 
We will train the RIFE model from scratch on the CPU and build the full pipeline for the video interpolation

#Structure
`data` - dataset with test images
`outputs` - the generated frames from test images
`videos` - videos files 
`models` - RIFE model


#Setup
1-Python virtual-env
python3 -m venv dlss-env
source dlss-env/bin/activate


2-Dependancies
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu
pip install opencv-python numpy tqdm matplotlib

#Usage

