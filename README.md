# Multimodal Image-Text Retrieval using CLIP

A multimodal image retrieval system that uses CLIP to retrieve relevant
images based on natural-language text queries.

## Dataset

Flickr8k dataset containing images and corresponding captions.

## Technologies

- Python
- PyTorch
- Hugging Face Transformers
- CLIP
- KaggleHub
- Google Colab

## How It Works

1. Load images from Flickr8k.
2. Generate image embeddings using CLIP.
3. Convert a natural-language query into a text embedding.
4. Calculate cosine similarity between text and image embeddings.
5. Retrieve the Top-5 most relevant images.

## Example

Input query:

"a man riding a bicycle"

Output:

The system displays the Top-5 images with the highest similarity scores.
