# My Project

# jto_py_env

This repo contains the environment file for the conda environment that I
use for adhoc analysis

## Environment Documentation

### Python Standard Library

\-[Standard Library](https://docs.python.org/3/library/index.html) -
[os](https://docs.python.org/3/library/os.html#module-os) -
[shutil](https://docs.python.org/3/library/shutil.html#module-shutil) -
[glob](https://docs.python.org/3/library/glob.html#module-glob) -
[sys](https://docs.python.org/3/library/sys.html#module-sys) -
[argparse](https://docs.python.org/3/library/argparse.html#module-argparse) -
[re](https://docs.python.org/3/library/re.html#module-re) -
[math](https://docs.python.org/3/library/math.html#module-math) -
[random](https://docs.python.org/3/library/random.html#module-random) -
[statistics](https://docs.python.org/3/library/statistics.html#module-statistics) -
[urllib.request](https://docs.python.org/3/library/urllib.request.html#module-urllib.request) -
[smtplib](https://docs.python.org/3/library/smtplib.html#module-smtplib) -
[datetime](https://docs.python.org/3/library/datetime.html#module-datetime) -
Data compression -
[zlib](https://docs.python.org/3/library/zlib.html#module-zlib) -
[gzip](https://docs.python.org/3/library/gzip.html#module-gzip) -
[bz2](https://docs.python.org/3/library/bz2.html#module-bz2) -
[lzma](https://docs.python.org/3/library/lzma.html#module-lzma) -
[zipfile](https://docs.python.org/3/library/zipfile.html#module-zipfile) -
[tarfile](https://docs.python.org/3/library/tarfile.html#module-tarfile) -
Performance Management -
[timeit](https://docs.python.org/3/library/timeit.html#module-timeit) -
[profile](https://docs.python.org/3/library/profile.html#module-profile) -
[pstats](https://docs.python.org/3/library/profile.html#module-pstats) -
Quality Control -
[doctest](https://docs.python.org/3/library/doctest.html#module-doctest) -
[unittest](https://docs.python.org/3/library/unittest.html#module-unittest) -
[json](https://docs.python.org/3/library/json.html#module-json)

# System & Environment

| Package                                                    | Description |
|------------------------------------------------------------|-------------|
| [pip](https://pip.pypa.io/en/stable/index.html)            |             |
| [jupyter](https://docs.jupyter.org/en/latest/)             |             |
| [python-dotenv](https://saurabh-kumar.com/python-dotenv/)  |             |
| [deltalake](https://delta-io.github.io/delta-rs/)          |             |
| [pyarrow](https://arrow.apache.org/docs/python/index.html) |             |
| [pylint](https://www.pylint.org/)                          |             |

### Data Acquisition

| Package                                                | Description                                                                                                             |
|--------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------|
| [requests](https://requests.readthedocs.io/en/latest/) | an elegant and simple HTTP library for Python, built for human beings                                                   |
| [pyodbc](https://github.com/mkleehammer/pyodbc/wiki)   | an open source Python module that makes accessing ODBC databases simple                                                 |
| [sqlalchemy](https://docs.sqlalchemy.org/en/20/)       | Python SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL |

### Data Munging & Validation

| Package                                                                                          | Description                         |
|--------------------------------------------------------------------------------------------------|-------------------------------------|
| [polars\[all\]](https://docs.pola.rs/)                                                           | Embarassingly parallel data munging |
| [pandas](https://pandas.pydata.org/docs/)                                                        | data munging                        |
| [snowflake-snowpark-python](https://docs.snowflake.com/en/developer-guide/snowpark/python/index) | data munging in Snowflake           |
| [pandera](https://pandera.readthedocs.io/en/latest/)                                             | data validation                     |
| [miceforest](https://miceforest.readthedocs.io/en/latest/)                                       | Impute missing values               |

### Exploratory Data Analysis (EDA)

| Package                                             | Description                                                                                          |
|-----------------------------------------------------|------------------------------------------------------------------------------------------------------|
| [pyskim](https://github.com/kpj/pyskim)             | a package for EDA at the commandline                                                                 |
| [sweetviz](https://github.com/fbdesignpro/sweetviz) | an open-source Python library that generates beautiful, high-density visualizations to kickstart EDA |

### Statistics, ML, & Data Analytics

<table>
<colgroup>
<col style="width: 12%" />
<col style="width: 87%" />
</colgroup>
<thead>
<tr class="header">
<th>Package</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a
href="https://www.statsmodels.org/stable/index.html">statsmodels</a></td>
<td>Estimation of many different statistical models, as well as for
conducting statistical tests, and statistical data exploration</td>
</tr>
<tr class="even">
<td><a href="https://docs.scipy.org/doc/scipy/">scipy</a></td>
<td><p>SciPy is a collection of mathematical algorithms and convenience
functions</p>
<p><a
href="https://docs.scipy.org/doc/scipy/reference/stats.html#statsrefmanual">scipy.stats</a>
- This module contains a large number of probability distributions,
summary and frequency statistics, correlation functions and statistical
tests, masked statistics, kernel density estimation, quasi-Monte Carlo
functionality, and more. This is a supplement to the base packages <a
href="https://docs.python.org/3/library/statistics.html#module-statistics">statistics</a>.</p>
<p><a
href="https://docs.scipy.org/doc/scipy/reference/linalg.html#module-scipy.linalg">scipy.linalg</a>
- linear algebra library</p></td>
</tr>
<tr class="odd">
<td><a href="https://patsy.readthedocs.io/en/latest/">patsy</a></td>
<td>Package for describing statistical models and building design
matrices</td>
</tr>
<tr class="even">
<td><a href="https://numpy.org/doc/">numpy</a></td>
<td>NumPy is the fundamental package for scientific computing in
Python</td>
</tr>
<tr class="odd">
<td><a
href="https://scikit-learn.org/stable/user_guide.html">scikit-learn</a></td>
<td>Simple and efficient tools for predictive data analysis, including
ML</td>
</tr>
<tr class="even">
<td><a
href="https://www.sktime.net/en/latest/index.html">sktime</a></td>
<td>A unified framework for machine learning with time series</td>
</tr>
<tr class="odd">
<td><a href="https://python.igraph.org/en/stable/">igraph</a></td>
<td>A fast open source python library to analyze graphs/networks</td>
</tr>
<tr class="even">
<td><a
href="https://networkx.org/documentation/stable/">networkx</a></td>
<td>A python package for the creation, manipulation, and study of the
structure, dynamics, and functions of complex networks.</td>
</tr>
<tr class="odd">
<td><a href="https://www.nltk.org/">nltk</a></td>
<td>A leading platform for building Python programs to work with human
language data</td>
</tr>
<tr class="even">
<td><a
href="https://quanteconpy.readthedocs.io/en/latest/">quantecon</a></td>
<td>Open source python library for economic modeling</td>
</tr>
</tbody>
</table>

### Visualization & Reporting

- [altair](https://altair-viz.github.io/getting_started/overview.html)
- [itables](https://mwouts.github.io/itables/quick_start.html#)
- [quarto](https://quarto.org/)
- [matplotlib](https://matplotlib.org/stable/index.html)
- [missingno](https://github.com/ResidentMario/missingno)
- [seaborn](https://seaborn.pydata.org/)
- [plotnine](https://plotnine.org/)
- [patchworklib](https://github.com/ponnhide/patchworklib)

### Diagrams, etc

- [mermaid-py](https://github.com/ouhammmourachid/mermaid-py)
  - [mermaid](https://mermaid.js.org/)
- [graphviz](https://www.graphviz.org/)
- [diagrams](https://diagrams.mingrammer.com/)

### Misc

- [pillow](https://seaborn.pydata.org/)
- [filter](https://kkroening.github.io/ffmpeg-python/)
- [xlsxwriter](https://xlsxwriter.readthedocs.io/)
- [openpyxl](https://openpyxl.readthedocs.io/en/stable/index.html)
- [sympy](https://docs.sympy.org/latest/index.html)
- [ffmpeg-python](https://kkroening.github.io/ffmpeg-python/)
