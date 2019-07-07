# Getting the data
* wget http://files.grouplens.org/datasets/movielens/ml-latest-small.zip
* unzip ml-latest-small.zip

# Getting the python script
* wget media.sundog-soft.com/es/MoviesToJson.py

# Running the script python
* python3 MoviesToJson.py > moremovies.json

# Install ES library for python
* sudo pip3 install elasticsearch

# Getting pyhton with library script
* wget http://media.sundog-soft.com/es/IndexRatings.py

# Running the script python
* python3 IndexRatings.py
