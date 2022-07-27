# page_rank

<p align="center">
    <img src="https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter" alt="jupyterLogo">
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="pythonLogo"> 
</p>

## Description

Implementation and explanation of the Google's Page Rank algorithm for website reference.  
The file `page_rank_exercise` is an explanation of the page rank and the `page_rank_exercise.ipynb` is an application of the page rank on a big dataset.

## Page rank

The page rank is a Google algorithm for website referencing in google search engine.
I made this program in a learning goal, its implementation is interesting to apprehend the basis of website reference.

<p align="center">
    <img src="images/wikipedia_image_page_rank.png" alt="wikipediaImgPageRank">
</p>

> **Note**
> Nowaday's google use other powerfuller algorithms.

## Quick start

To start each program, please install Python (at least version 3.8):
<https://www.python.org/downloads/>

There is only one package needed:
- numpy

You can install it using the pip python package manager:

```bash
pip install numpy
```

You'll also need an IDE like Pycharm, VsCode or any other to start the Jupyter Notebook files.

## Project architecture 

The project is composed of two main files.

The first one is made for the basis learning of the Page Rank algorithm with the basis notions :

- website successors and predecessors referencing influence
- the spider-trap and teleport
- the dead ends

The second file is a test of the algorithm for a bigger set of website than the previous example.
It needs the `hollins.dat` file to work, of course this files is provided with the project.

**Note**
> If you want to learn more about Google's current algorithm, check the google link in the `documentations` section.

## Output

The two jupyter notebok files will display the same way the output.

The website with the most important reference value will be displayed in first than the other more important website.

page_rank.ipynb:

```
1 : ('B', 0.2956000000000001)
2 : ('C', 0.28648000000000007)
3 : ('D', 0.26280000000000003)
4 : ('A', 0.15512000000000004)
```

page_rank_exercise.ipynb:

```
1 : ('http://www.hollins.edu/', 0.0254580229107189)
2 : ('http://www.hollins.edu/admissions/visit/visit.htm', 0.01105341950078871)
3 : ('http://www.hollins.edu/about/about_tour.htm', 0.010282488037670167)
```

## Documentations

Wikipedia:  
<https://en.wikipedia.org/wiki/PageRank>

Google:  
<https://www.google.com/search/howsearchworks/>

Search Engine Land:  
<https://searchengineland.com/what-is-google-pagerank-a-guide-for-searchers-webmasters-11068>

## Contributors

Quentin MOREL :

- @Im-Rises
- <https://github.com/Im-Rises>

[![GitHub contributors](https://contrib.rocks/image?repo=Im-Rises/page_rank)](https://github.com/Im-Rises/page_rank/graphs/contributors)
