# Spotify Playlist Analysis

## Table of Contents

- [Overview](#overview) :eyes:
- [Prerequisites](#prerequisites) :books:
- [Setup](#setup) :gear:
- [Code Explanation](#code-explanation) :computer:
- [Results](#results) :chart_with_upwards_trend:
- [Usage](#usage) :bulb:
- [Credits](#credits) :clap:


## Overview
This code retrieves the genres of artists included in several Spotify playlists and analyzes music genre preferences across different individuals using Venn diagrams, t-SNE plots, and UpSet plots.

## Prerequisites
* Spotify API credentials
* spotipy
* matplotlib
* matplotlib_venn
* numpy
* scikit-learn
* pandas
* upsetplot

## Setup
Replace the `[client ID]` and `[secret]` placeholders with your Spotify API credentials.

```python
client_id = '[client ID]'
```
```python
client_secret = '[secret]'
```

## Code Explanation
The code retrieves the genres for each artist in each playlist and uses them to update the genre sets for each person. It then creates Venn diagrams to show the unique and common genres for each person. It also applies t-SNE to create a 3D plot that shows the similarities and differences in genre preferences across individuals. Finally, it uses UpSet plots to visualize the overlap between the genres liked by different people.

## Results
* Venn diagrams show the unique and common genres for each person.
* t-SNE plots show the similarities and differences in genre preferences across individuals.
* UpSet plots show the overlap between the genres liked by different people.

## Usage
1. Set your Spotify API credentials in the code.
2. Run the code.
3. View the generated plots.

## Credits
* spotipy - https://github.com/plamere/spotipy
* matplotlib - https://matplotlib.org/
* matplotlib_venn - https://pypi.org/project/matplotlib-venn/
* numpy - https://numpy.org/
* scikit-learn - https://scikit-learn.org/stable/
* pandas - https://pandas.pydata.org/
* upsetplot - https://pypi.org/project/upsetplot/

