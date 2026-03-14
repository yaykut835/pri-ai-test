# pri-ai-test
A primitive ai model, 
This project is a Character-Level Language Model based on the Transformer architecture. Inspired by Andrej Karpathy's approach, it implements a generative pre-trained transformer from the ground up using PyTorch.

The model is trained on a custom-curated corpus of 10 classic literary works, enabling it to learn and mimic the stylistic nuances of 19th-century prose, dramatic dialogues, and philosophical inquiries.

Multi-Dataset Integration: Automatically downloads and merges 10 distinct datasets (including Shakespeare, Sherlock Holmes, Dracula, and Frankenstein) into a single 15MB training corpus.

Text Preprocessing: Includes a custom clean_gutenberg_text function to strip headers, footers, and license metadata from Project Gutenberg files.

Full Transformer Architecture: Implements Multi-Head Self-Attention, Feed-Forward networks, Residual Connections, and Layer Normalization.

Interactive Inference: Features a prompt-based generation loop where users can provide a "seed" text to guide the model's output.
