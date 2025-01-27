# Proliferation history and transcription factor levels drive direct conversion to motor neurons
[<img src="https://img.shields.io/badge/code_license-MIT-green">](./LICENSE)
[<img src="https://img.shields.io/badge/text_license-CC--BY--4.0-green">](https://creativecommons.org/licenses/by/4.0/)

<!-- | Item          | DOI           |
| ------------- |:-------------:|
| Article (preprint)       | [![Article DOI](https://img.shields.io/badge/Article_DOI-10.1101/2022.04.20.488937-green)](https://doi.org/10.1101/2022.04.20.488937)     |
| Software (this repository)      | [![Software DOI](https://img.shields.io/badge/Software_DOI-10.5281/zenodo.7054395-blue)](https://doi.org/10.5281/zenodo.7054395)                                                              |
| Dataset for article figures     | [![Dataset DOI](https://img.shields.io/badge/Dataset_DOI-10.5281/zenodo.7041641-blue)](https://doi.org/10.5281/zenodo.7041641)     | -->

| Item                     | DOI                       |
| ------------------------ |:-------------------------:|
| Article                              | [![Dataset DOI](https://img.shields.io/badge/Article_DOI-TBD-blue)](TBD)      |
| Dataset                              | [![Dataset DOI](https://img.shields.io/badge/Dataset_DOI-10.5281/zenodo.14743917-blue)](https://doi.org/10.5281/zenodo.14743917)       |



## Setting data directory
We use rushd to organge our data analysis. rushd requires you to specify a data directory. After you decide where to put the data locally, create a file called datadir.txt in the GitHub repo that contains the code. The datadir.txt file will contain only the **absolute path** to the folder in which you placed the data.

For example, if you placed the GitHub repo in /Users/username/Documents/GitHub/article-prolif-TF-levels/ and you place the data in /Users/username/Documents/GitHub/article-prolif-TF-levels/data/, then you would place the datadir.txt file in /Users/username/Documents/GitHub/article-prolif-TF-levels/ and it should contain one line:

```
/Users/username/Documents/GitHub/article-prolif-TF-levels/data/
```

## Instructions

1. Download local copy of data
2. Update datadir.txt to point to data folder
3. Use virtual environment with Python 3.9.6
4. Install packages
```
pip install -r requirements.txt
```
