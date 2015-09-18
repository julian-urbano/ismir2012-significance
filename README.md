This archive contains the data gathered for the following paper:

 * J. Urbano, S. Downie, B. McFee and M. Schedl, "[How Significant is Statistically Significant? The case of Audio Music Similarity and Retrieval](http://julian-urbano.info/wp-content/uploads/041-how-significant-statistically-significant-case-audio-music-similarity-retrieval.pdf)", *International Society for Music Information Retrieval Conference*, 2012.

A [single ZIP file](https://github.com/julian-urbano/ismir2012-significance/archive/master.zip) can be downloaded as well.

## Data

### Files

 * `template/` HTML task template (live version available [here](http://julian-urbano.github.io/ismir2012-significance/template/)).
 * `data/workers.csv` CSV file with information about all workers, whether accepted or rejected.
 * `data/answers.csv` CSV file with all answers accepted by Crowdflower (except gold examples).

### Format

Some of the columns in the data table are (`N` goes from 1 to 5):

 * `query` ID of the query clip.
 * `dNX` ID of the `N`-th document retrieved by service `X`.
 * `bNX` Broad score given to the `N`-th document retrieved by service `X`.
 * `fNX` Fine score given to the `N`-th document retrieved by service `X`.
 * `agbX` AG@5 score with Broad judgments achieved by service `X`.
 * `agfX` AG@5 score with Fine judgments achieved by service `X`.
 * `ndcgbX` nDCG@5 score with Broad judgments achieved by service `X`.
 * `ndcgfX` nDCG@5 score with Fine judgments achieved by service `X`.
 * `dagb` ΔAG@5 with Broad judgments.
 * `dagf` ΔAG@5 with Fine judgments.
 * `dndcgb` ΔnDCG@5 with Broad judgments.
 * `dndcgf` ΔnDCG@5 with Fine judgments.
 * `ov` Number of documents in common in both services' outputs.

## License

 * Databases and their contents are distributed under the terms of the [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

When using this archive, please cite the above paper:

    @inproceedings{Urbano2012:significant,
      author = {Urbano, Juli\'{a}n and Downie, J. Stephen and Mcfee, Brian and Schedl, Markus},
      booktitle = {International Society for Music Information Retrieval Conference},
      pages = {181--186},
      title = {{How Significant is Statistically Significant? The case of Audio Music Similarity and Retrieval}},
      year = {2012}
    }

The MP3 player used in the template is redistributed from [here](http://flash-mp3-player.net/players/).
