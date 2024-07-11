# songs
Songs for Encore

## Publishing your charts

> [!WARNING]
> No official songs! These will not be accepted.<br>
> Encore does NOT endorse piracy.

To publish a song, the chart must go under review and be validated.
In order to publish a song, follow these steps:

- Fork the `songs` repository

    Create a fork of this repository by clicking on the **Fork** button. *Don't clone it!*

    ![fork](images/fork.png)

- Archive your song
    
    Package the `info.json`, stems, and album art into a folder. After, create a ***zip*** archive of the folder.

    The limit for uploading files is **100 MB**, as set by GitHub. However, we recommend your zip to be under **20 MB**.

    Only **zip** files are accepted.

- Upload the song

    To upload your song as a **zip** archive, press the **Add File** button, located besides the green **Code** button.

    ![add-file](images/add-file.png)

    After, click on the **Upload files** button that shows up in the dropdown menu.

    ![add-new-file](images/add-new-file.png)

    Now, drag your **zip** song to the page.

    After your **zip** is done uploading, it will show up below the space to drag.

    ![fileupload](images/fileupload.png)

    After, click on **Commit changes** to confirm the song upload. Make sure you are committing to the **main** branch.

    *If you'd like to add multiple charts, you should create multiple branches and commit each chart to each branch, then create multiple pull requests, so this process can stay organized.*

- Create the pull request

    Click on the **Contribute** button below **Add file**. After that, click on **Open pull request**

    Under **Add a title**, specify your song name.

    Under **Add a description**, follow the instructions on the PR template.

    When you are done, click on **Create pull request**.

- Wait for approval

    Your chart will be approved after it is verified.

    When your chart is verified and the pull request is merged, you will be able to see it in [FNLookup](https://fnlookup.github.io/encore/), where it will be given an ID.

## Resources for charting

- [Encore REAPER Template](https://github.com/Encore-Developers/songs/raw/main/images/Encore%20Template.zip)

- [Download REAPER](https://www.reaper.fm/download.php)

- [Guide for charting in REAPER](https://docs.google.com/document/d/1b7KcHJ5uX-jcAjeRTStJRxcEvZ5ohYNOeVvezG03vwA/edit#heading=h.u8vd9w9b6n0y)

- [Preview ReaScript](https://github.com/NarrikSynthfox/FNFest_Preview)

### `EVENTS` Track
Used to identify parts of the song:

- `[music_start]`: Defines when the song starts.
- `[music_end]`: Defines when the song finishes.
- `[end]`: Defines when the song ends and the score screen should appear.
