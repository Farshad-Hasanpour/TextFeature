# TextFeature
transforms unstructured text to feature vector using word2vec, lexicon and ... 

## Directories
- test: This directory contains an jupyter Notebook to test and debug code easily

## Instructions
### upgrade
1. change textfeature directory content
2. update setup.py file and change version number
3. remove dist directory to delete older versions
4. run `python setup.py sdist bdist_wheel` to create new version dist
5. run `python -m twine upload dist/*` to upload package
6. commit changes to git and install new version using `pip install textfeature --upgrade`

## Functions
### text_w2v()
...
 - **word_tokens**:
### text_l2v()
...
 - **word_tokens**:
- **lexicon_name**:
- **vector_size**:
