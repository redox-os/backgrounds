# Redox Desktop Backgrounds

Welcome to the Redox backgrounds repository. It contains all the stock desktop background images for Redox OS/Orbital.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a><br />All content in this repository is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

## Submitting new stock backgrounds:

If you've created a custom desktop background through means of photography, digital art, or other, and wish to have it featured in Redox, please submit a pull request following these guidelines:

- **By submitting your image in a pull request for use as a Redox desktop/wallpaper background, you are agreeing for your image to be included in Redox under the Creative Commons 4.0 International License.**
- One background image per pull request.
- All images should be lossless. (currently supported formats: png)
- The image should be a minimum of 1920x1080 pixels, but preferably 4k and higher if possible. (no scaling!)
- Thumbnail image should be 160x90 pixels.
- The source should be uncropped from the original and have a decent-sized buffer/margin area to allow for framing changes.
- You can provide custom crops/reframes for different aspect ratios, e.g. 16:9, 4:3, 8:5, 7:3. At least 16:9 and 4:3 are required. It's preferred that you also include other ratios like 8:5 and 7:3 if possible, but if it doesn't fit the theme or composition of your image, that's fine. This is because it is preferred for a human to select the framing for each aspect ratio to maintain compositional quality and creative control, but if need be orbital (our desktop enviroment) will do it automatically.
- Use anything you want to actually create the image. Photography, 3D software, image editing software, etc.
- Make anything. Abstract, nature, buildings. Make sure you have all the rights to use and distribute it. (e.g. video games, copyrighted symbols, characters, people in general aren't frowned upon by us but may be by others, so just consider this )
- A new folder with the title of your piece should be made, under which all your files should go. Example directory structure:
```
My-Piece
├── source.png
├── metadata.toml
├── thumb.png
├── 16x9.png
└── 4x3.png
```
- The `metadata.toml` file is parsed by our website generator, as well as orbital. Provide metadata in the `metadata.toml` file.
	- The fields are:
		- `artist_name = <your alias or real name>`
		- `artist_contact = <your email>` (if you're not sure, just use the email you're commiting with)
		- `piece_name = <name of your piece>`
		- More items may be added in the future
	- Example `metadata.toml` file:
```toml
[background]
artist_name = "John Smith"
artist_contact = "jsmith@redox-os.org"
piece_name = "Winter Lights"
```

Once you've checked off everything in this list, send us a PR in this repository.
