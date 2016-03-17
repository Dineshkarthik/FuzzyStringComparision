## String Clustering:

Clustering of strings using Fuzzy String matching and KMeans Algorithm.

## Usage:

> `python string_clustering.py json_file_name field_name no_of_clusters`

  1. json_file_name: Name of the input JSON file
  2. field_name	: Name of the JSON field
  3. no_of_clusters: Number of Clusters into which the string has to be clustered.
    * If the input file is present in another direcoty enter the full path, __D:/FuzzyStringMatch/data/sample_data.json__

> csv or tsv files can also be used. Use Pandas read_csv function. 

#### Ex:
   Here we have the *string_cluster.py* in **src** directory and a sample data *sample_data.json* in **data** directory.

> `python string_clustering.py D:/FuzzyStringMatch/data/sample_data.json field04 25`

* This generates a output file named **Report.txt** with the strings from the JSON field *field04* clustured together into 25 different clusters.
