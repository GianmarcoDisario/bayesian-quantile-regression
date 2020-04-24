# bayesian-quantile-regression

In this repo I would like to learn more about (deep) Bayesian quantile regression. In order to do this. The learning is mainly done in the notebooks. Where possible, the knowledge gathered will be put together in proper code. My interest was sparked by [Yu Ri Tan's blog on prediction uncertainty](https://www.yuritan.nl/posts/prediction_uncertainty/).

## Explanation about notebooks

The notebooks will be able to be read standalone, but there will be a progression in knowledge.

### Notebook 1 - Quantile Regression
The first notebook is completely dedicated to quantile regression. It assumes a bit of knowledge about linear regression as well as a bit of (convex) optmization. The quantile regression problem is rewritten into a convex optimization problem which allows for optimal solving of quantile regression. The derivation followed in the notebook is based in large part on [an answer given on Stats Stackexchange](https://stats.stackexchange.com/questions/384909/formulating-quantile-regression-as-linear-programming-problem). This is subsequently worked out in a scikit-learn type class. The second part makes a quick example of how quantile regression can be used in a homoscedastic setting (just like linear regression) as well as in a heteroscedastic setting. If multiple quantiles are estimated, the heteroscadestic properties of the data can be taken into account.

### Notebook 2 - Linear Bayesian Regression with PyMC3
Work in progres...

The notebook will be based on [the blog series of twiecki.io](https://twiecki.io/blog/2013/08/12/bayesian-glms-1/)