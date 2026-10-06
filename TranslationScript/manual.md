uv run --with pandas --with deep-translator TranslationScript/processor_translator.py "Translations/Unprocessed/AnkiCards_Audio_2026-09-02_16-48_['New HSK1']_unprocessed.csv" > "Translations/Processed/ForEnglish/AnkiCards_Audio_2026-09-02_16-49_['New HSK1']_processed.csv"

and so on (need automated script)



# extraction

automated script

# Compression

uv run TranslationScript/compressor_apkg.py "For French/New HSK1/AnkiCards_Audio_2026-09-02_16-48_['New HSK1'].apkg" "Translations/Processed/ForEnglish/AnkiCards_Audio_2026-09-02_16-49_['New HSK1']_processed.csv" "For English/HSK1/Audio.apkg" english