Upload Card Images
==================

* This git repo is the source of truth for **ALL** SWCCG card images.
* For more information about how the card images are processd, read the [**Card Images**](card-images.md) documentation.
* **Images** are in the [`Images-HT/starwars/`](../Images-HT/starwars/) subdirectory.
* Subdirectories within `starwars` contain **sets**, 1 for each side of the force.
* Within the set directories, the `hires/` directory contains _high resolution_ **png** images.
* When adding new images, **ALWAYS UPLOAD A HIGH RESOLUTION PNG**.
* Card images will for other use cases, such as lower resolution gif images for scomp or holotable, will be automatically generated by the git automations.
* Card images are automatically uploaded to `res.starwarsccg.org/cards` when merged to the `master` branch.


## Image Dimensions

* **High Resolution Images**: 703×980 RGB 120dpi png, *or better*


## Filename CaSe, special characters, and spaces

* All image files should be stored as _lowercase_ to avoid confusion and conflict.
* All image filenames should not have special characters, such as: &, @, -
* All image filenames should not have spaces.

| Incorrect                           | Correct                        |
| ----------------------------------- | ------------------------------ |
| oddballs_torrent_starfighter.png    | oddballstorrentstarfighter.png |
| OddballsTorrentStarfighter.png      | oddballstorrentstarfighter.png |
| "Oddball's Torrent Starfighter.png" | oddballstorrentstarfighter.png |
| Vader&Obi-WanSeeker.png             | vaderobiwanseeker.png          |


## Docking Bays

* Docking Bays should always include the word _`docking bay`_ in their name.

| Incorrect                           | Correct                        |
| ----------------------------------- | ------------------------------ |
| coruscantprivateplatform.gif        | coruscantprivateplatformdockingbay.gif |
| scariflandingpadnine_ai.png         | scariflandingpadninedockingbay_ai.png |
| scariflandingpadnine.gif            | scariflandingpadninedockingbay.gif |




## Instructions for uploading Card Images

* You will need a **[GitHub account](https://www.github.com/)**.
* You will need a **Git client**:
  * [Windows users are recommended to use TortoiseGit. Follow these instructions to install it](git-for-windows-users.md).
  * [MacOS users are recommended to use Sourcetree. Follow these instructions to install it](git-for-macos-users.md)
  * [Users familiar with the commandline are recommended to use `git`.](git-for-shell-users.md)
* **Fork** the `holotable` git repo. **Clone** your fork locally. **Add** the images. **Commit** the changes. **Push** the changes. Create a **pull request**:
  * [For Windows users, you can follow this reference](upload-card-images-windows.md).
  * [For MacOS users, you can follow this reference](upload-card-images-macos.md).
  * [Users familiar with the commandline can follow this reference.](upload-card-images-shell.md)









