# glyph-to-character

The aim is to build parser that can help parse PDF's that have non-standard unicode mapping - a common problem in PDFs containing texts in Indian languages. If glyphs of unique chracters can be extracted, then they can be used to get the correct unicode by querying a VLM with an appropriate prompt. Gemini performs well on this.

# Requirements
The notebook is ready to run. Personal Gemini API Key is required which needs to be updated in _config.py_.
