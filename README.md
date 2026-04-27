# AI for Arts & Humanities B Portfolio

This portfolio explores how generative AI can be used to engage a general audience with cultural heritage that has been preserved through limited or one-sided systems of recording.

## Project Overview

The chosen object is *A Catalogue of Different Specimens of Cloth collected in the Three Voyages of Captain Cook*, held at the University of Glasgow Special Collections. It is a bound volume containing physical fragments of Pacific bark cloth (tapa) gathered during Captain James Cook's voyages in the late eighteenth century, each fragment accompanied by a brief written description.

The catalogue carefully records the textiles' physical qualities, but operates within an eighteenth-century scientific framework that prioritises material properties over the cultural meaning of the textiles. This project approaches the catalogue in two connected ways:

- **As structured data** — the catalogue is transformed into a CSV dataset, which can be searched, compared, and analysed digitally.
- **As a starting point for AI-assisted reconstruction** — generative AI (Microsoft Copilot, using OpenAI's DALL·E 3) is used to attempt to re-situate the textiles within the cultural contexts the catalogue does not record, with each AI output examined critically rather than treated as authoritative.

The portfolio invites the reader to engage with the textiles in three connected ways: by reading about their cultural and historical context, by browsing the catalogue as data, and by reflecting on what AI can and cannot do when extending an archive of this kind.

## Repository Structure

- `ai_arts_portfolio.ipynb` — main project notebook (start here)
- `data/fabrics.csv` — structured dataset built from the catalogue
- `images/` — photographs of the catalogue, individual textile samples, and AI-generated images
- `requirements.txt` — Python packages used in the analysis

## How to View

Open `ai_arts_portfolio.ipynb` to read the project. 

1. **Context** — introduces the object and its cultural and historical background
2. **Design Approach** — explains the methodology and the role of human–AI collaboration
3. **Implementation** — documents the dataset, descriptive analysis, and AI image generation
4. **AI Limitations** — reflects on what the AI tools can and cannot do
5. **References** — full bibliography

## Tools Used

- **ChatGPT (OpenAI)** — used to support the transcription of the catalogue's archival language, particularly where entries used inconsistent spelling, abbreviation, or outdated terminology.
- **Microsoft Copilot (using DALL·E 3)** — used to generate AI images that attempt to re-situate the textiles in cultural context, and to support the simple Python code used to load and analyse the dataset.

Both tools were chosen for their accessibility and free availability. All AI-generated outputs were reviewed and refined through human judgement; the project demonstrates human–AI collaboration rather than autonomous AI generation.

## A Note on Cultural Material

This project engages with Pacific cultural heritage gathered under colonial conditions. The AI-generated images are not presented as authentic reconstructions of Pacific cultural practice. They are presented as evidence of how contemporary AI systems represent, reshape, or omit that practice, and the ethical considerations raised by their use are discussed in Section 3.3 of the notebook.
