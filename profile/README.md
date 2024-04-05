## Repository existing

- tinder-scraper
- tinder-sql-connector

## Projects

### tinder-face-reader

Each time a new photo is uploaded, Tinder's algorithm analyzes the photo to detect whether or not there's a face. If there is a face, it records the coordinates of the face along with the JSON data in the photo. The **tinder-face-reader** connector is there to show where the person's face is, according to their agorithm. Thanks to this module, you can also export only the face and process one or more photos.

### tinder-image-downloader

To view a profile's photos, Tinder generates a URL that follows your account and is perishable over time. To prevent accessibilty being compromised, **tinder-image-downloader** will download all the photos of one or more profiles, in all different sizes. If you don't want to store your images locally *(on your own machine)*, this module lets you upload them to <a href="https://mega.nz">MEGA</a>, a cloud offering **20 GB** storage free of charge.

### tinder-instagram-scraper

This connector finds the Instagram account of a Tinder account. This module searches the account's biography to see if an Instagram account is mentioned, then verifies its existence. In addition to giving you the Instagram account ID, this module will retrieve the profile photo, number of subscribers, number of followers, biography, name, and whether or not the account is private.
