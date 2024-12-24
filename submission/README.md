# Create conda env:
conda env create --file env.yml

# category-generator.ipynb can be run to crreate embeddings for new datasets, we include trends data to be used:
data/trends.csv

# An embedding output for this is also provided:
data/google_trends.csv

# Run dummy-generator.ipynb with desired parameters to create output files of the methodology. Requires OpenAI API-KEY to be set in constants.py.
# We include most of the outputs we used during our evaluation:
outputs/

# Run attacks.ipynb with desired parameters to attack the desired output fies.