# Images Similarity

Just run in the project root dir.

```bash
pipenv install
```

How to use:

```bash
python find_similar_images.py [ahash|phash|dhash|whash-haar|whash-db4] [<threshold>] [<directory>]
```
 
Example

```bash
python find_similar_images.py dhash 20 images
```

Image hash docs [here](https://github.com/JohannesBuchner/imagehash)