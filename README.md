*******NOTE:All codes are working but will take time to execute depending on system******
****distilgpt2_Working will be able to execute in any system so try it****
    
    # DistilGPT2 arXiv Abstract Generator 

This project explores fine-tuning DistilGPT2 to generate scientific abstracts using a curated subset of the arXiv dataset.

## Project Structure
- `fine_tune.py`: Training script using Hugging Face Transformers
- `evaluation.py`: Evaluation script with BLEU, ROUGE, and Perplexity
- `paper/`: Contains the research paper (`.md` and `.pdf`)
- `outputs/`: Generated abstract samples
- `requirements.txt`: Python dependencies

##  Results
- Final Training Loss: ~3.83
- Validation Perplexity: ~33.91
- BLEU/ROUGE scores included in the paper

##  Setup
```bash
pip install -r requirements.txt

