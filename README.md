# Applied Machine Learning (AML)

Practical implementation and usage of machine learning algorithms, application of machine learning algorithms in real problems using Python.

<ol>
<li>Introduction to machine learning</li>
<li>Introducing Python</li>
  <li>  Reading and cleaning data and plotting</li>
<li>Preprocessing and feature extraction</li>
  <li>  Unsupervised ML for data exploration</li>
  <li>Supervised machine learning</li>
<li>Evaluation and optimisation of the models</li>
</ol>

## Deployment commands
```bash
poetry run jupyter-book build notebooks
git add -A
git commit -m "publish"
poetry run ghp-import -n -p -f notebook/_build/html
```

Useful [guide](https://https://medium.com/@dr.junghoonson/simplest-way-to-publish-your-jupyter-notebooks-on-the-open-web-using-jupyter-book-and-github-pages-eea144031d6f) for pubishing Jupyter Notebooks to GitHub Pages.
