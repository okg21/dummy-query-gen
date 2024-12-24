# Create conda env:
conda env create --file env.yml

# category-generator.ipynb can be run to crreate embeddings for new datasets, we include google trends.
data/google_trends.csv

# Run dummy-generator.ipynb with desired parameters to create output files of the methodology. Requires OpenAI API-KEY to be set in constants.py.
# Run attacks.ipynb with desired parameters to attack the desired output fies.