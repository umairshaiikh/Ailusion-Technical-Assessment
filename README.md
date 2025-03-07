# PedalStart Ailusion Hiring Task

## Instructions
1. Install dependencies:
   - Python: `pip install diffusers transformers torch torchvision pillow`
   - Julia: `using Pkg; Pkg.add("Flux")`
2. Run the Python scripts to generate and preprocess images.
3. Run the Julia script to perform a forward pass with the Flux model.

## Approach
- Generated 3 synthetic images using Stable Diffusion.
- Preprocessed images by resizing to 224x224 and normalizing pixel values.
- Created a minimal Flux model with convolutional and dense layers.
- Performed a forward pass on one preprocessed image.

## Challenges
- Hardware limitations for image generation.
- Adjusting input dimensions for the Flux model.
- # PedalStart Ailusion Hiring Task

## Python Setup
1. Install dependencies:
   ```bash
   pip install -r python/requirements.txt
   
