# PLAGIARIASM_REMOVER
Plagiarism Remover (NLTK)

A lightweight NLTK-based plagiarism remover / paraphraser that replaces words with same-POS synonyms from WordNet.
Designed to run in Google Colab (interactive widget UI) or locally. Useful for producing multiple paraphrase “flavours” by sampling synonyms at random.

⚠️ Academic honesty reminder: This tool is for learning, drafting, and exploring paraphrases — do not use it to cheat or bypass plagiarism checks. Always follow your institution’s policies.

Features

Replace single-word tokens with WordNet synonyms that match original POS tags.

Preserves punctuation, capitalization and spacing.

Interactive UI via ipywidgets (works well in Google Colab).

Optional random seed to reproduce outputs.

Simple, dependency-light implementation (NLTK).

Demo / Screenshot

(Optional: add a screenshot of the Colab UI here)

Quick start
Run in Google Colab (recommended)

Open a new Colab notebook.

Copy the full code from colab_plagiarism_remover.py (or the single-cell code in this repo) into one cell.

Run the cell. The UI will appear below the cell.
