# Thematic Analysis of Climate Change News across Political Orientations

## Research aim
This project investigates how climate change is discussed in news articles across political orientations, focusing on differences in recurring themes, word usage patterns, and framing. 

## Structure
- `Left` folder: 100 climate-related news articles classified as left-leaning
- `Center` folder: 100 climate-related news articles classified as center-leaning
- `Right` folder: 100 climate-related news articles classified as right-leaning
- `Results (Voyant)` folder: Voyant-generated figures used in research poster
- `metadata.csv`: dataset of all 300 articles (an table overview is provided below)
- `T&M.ipynb`: Jupyter Notebook containing Python code for descriptive statistics
- `Thematic Analysis of Climate CHange News (3).pdf`: research poster of the study conducted
- `README.md` file

The `metadata.csv` file contains the following columns:
| Column Name  | Type | Function |
| ------------- | ------------- | ------------- |
| id  | string | stores the name of each file |
| title  | string  | titles of each article |
| date | date | publication date of the article |
| outlet | string | news outlet of each article |
| language | string | language in which the article was written |
| orientation | string | political orientation label for each article |

## Data
- Sampling: 100 climate & environment related articles per political orientation (300 total)
- Time window: Jan 5 - 29, 2026
- Bias label: outlets were grouped into Left, Center, Right using Ground News' media bias breakdown
- Language Handling: some non-English articles were machine translated

## Reproductibility
1. Make sure the `metadata.csv` is in the same file as the `T&M.ipynb`
2. Open and run `T&M.ipynb` to reproduce descriptive statistics
3. Upload the folders into Voyant Tools to replicate lexical and framing exploration of frequencies, collocates, term trends, etc.

*Note: We suggest downloading Voyant on your own computer because the online version might crash easily*

