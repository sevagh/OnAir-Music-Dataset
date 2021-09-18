# OnAir Music Dataset

This is a dataset of music stems from the OnAir Music project for royalty-free songs:
* [TheOnAir.Music on Instagram <img src="./.github/instagram_logo.svg" height=20px/>](https://www.instagram.com/theonair.music/)
* [OnAir Music on Spotify <img src="./.github/spotify_logo.svg" height=20px/>](https://open.spotify.com/artist/7IYLENV1pGGPvL6wkyl7t5)

The OnAir Music project is created and maintained by:
* Hrag: [@nazguitar on Instagram <img src="./.github/instagram_logo.svg" height=20px/>](https://www.instagram.com/nazguitar/), [NAZ on YouTube <img src="./.github/youtube_logo.svg" height=20px/>](https://www.youtube.com/channel/UCOJWAbfcCw2gkkkRZv1es_A)
* The Crescent MTL Project: [@thecrescentmtl on Instagram](https://www.instagram.com/thecrescentmtl/), [The Crescent on YouTube <img src="./.github/youtube_logo.svg" height=20px/>](https://www.youtube.com/c/TheCrescent)

The dataset on GitHub is maintained by Sevag: [sevagh on GitHub <img src="./.github/github_logo.svg" height=20px/>](https://github.com/sevagh)

The intent of releasing this stems dataset is for free and open Music Demixing research. The stems dataset is licensed under the Creative Commons Attribution Share Alike 4.0 International.

## Music demixing

Read more about Music Demixing on the ISMIR 2021 Music Demixing Challenge [competition page](https://www.aicrowd.com/challenges/music-demixing-challenge-ismir-2021). The task of music demixing or source separation is to separate a mixed song into isolated stems. This can have uses in karaoke, re-mastering old audio, hearing aids, etc.

![mixdemix](./.github/mixdemix.png)

Research for music demixing depends on the availability of music stems that can be used for training or testing machine learning models. We hope that the releasing of this dataset helps future demixing researchers to move the field forward.

## Tagged versions

The track list is small initially, but we are committed to releasing more stems as songs are released on Spotify. They will be added to the dataset and new versions will be published.

The zip is stored with Git LFS in this repo, and git tags will be used to keep track of dataset versions. The list of published versions so far are:

### V3 - released 2021/09/18

**NB** The V3 release consists of two zip files, due to the GitHub LFS 2GB file size limitation. Tracks are grouped by album where it makes sense (misc otherwise).

Track list from the [LoFi Vol. 3](https://open.spotify.com/album/6gcADOwI4LzXaHHwOQbF7D) collection:
* Autumn in NY
* Bouncin Around
* Ramen Rain
* Vibin Vibin
* Yaku

Track list, misc:
* Action
* Ronin
* Set Me Free
* Under My Skin

### V2 - released 2021/09/09

Track list:
* Bouncin Around
* Autumn in NY
* Vibin Vibin
* Yaku
* Ronin
* Action
* Under My Skin

**NB** Under My Skin has been readded with 2 new tracks, Ronin and Action. 7 total tracks.

### V1 - released 2021/09/08

Track list:
* Bouncin Around
* Autumn in NY
* Vibin Vibin
* Yaku

**NB** "Under My Skin" was removed since V0, and 4 new tracks added

### V0 - released 2021/09/02

Track list:
* Under My Skin

## Dataset zip format

The dataset is released as a zip. Each track is a folder containing the mixed song and all of the stems.
