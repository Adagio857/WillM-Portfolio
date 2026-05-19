# Will Manley Video Portfolio

A static video portfolio designed for GitHub Pages. It includes:

- Sizzle reel video at the top of the page
- Project gallery with three selected project videos
- Role descriptions below every video
- Contact section

## Customize

Open `index.html` and replace:

- `willjama@icloud.com` with Will's preferred contact email if it changes
- The project titles and role descriptions with Will's final project information
- The local MP4 filenames in each `<source src="...">` if Will's exported files use different names

The site currently expects these local files:

- `Videos/Main Video/Will Manley Sizzle Reel.mp4`
- `Videos/Full Length Project 01/Narrative Edit.mp4`
- `Videos/Full Length Project 02/Promotional Project.mp4`
- `Videos/Full Length Project 03/Short Film.mp4`

For GitHub Pages, export videos as `.mp4` using H.264 video and AAC audio. Keep each file under 100 MB so GitHub can accept it in the repository.

The hero background is built with CSS, so the page does not require a background image.

## Publish on GitHub Pages

1. Commit and push this folder to the GitHub repository.
2. In GitHub, go to `Settings` > `Pages`.
3. Set the source to the `main` branch and root folder.
4. Save, then open the Pages URL GitHub gives you.
