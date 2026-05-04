# RAG PDF Chunking

This repo contains the notebook `RAG_pdf_podcast.ipynb`, which explores different ways to chunk a Trustworthy AI PDF.

## Setup

```bash
pip install -r requirements.txt
```

## Project Files

- `RAG_pdf_podcast.ipynb`: main notebook with chunking experiments, comparisons, visualizations, and recommendations.
- `requirements.txt`: Python dependencies used by the notebook.
- `lab_content.txt`: original source content used to structure the notebook.
- `data/ai_hleg_ethics_guidelines_for_trustworthy_ai-en_87F84A41-A6E8-F38C-BFF661481B40077B_60419.pdf`: PDF used in the chunking analysis.
- `data/ethics_guidelines_for_trustworthy_ai-fr_87FE7A3C-D03D-9305-81A653DDA84B5A60_60427.pdf`: additional PDF file in the data folder.
- `data/The_Blueprint_For_Trustworthy_AI.m4a`: audio file in the data folder, not used in the current notebook workflow.

## Notes

- The current notebook workflow is PDF-only.
- Semantic chunking is run on a sample of the PDF text and forced to CPU for compatibility.
