# How To Contribute:
- Copy `Example` directory, and rename it `your-recipe`
- Edit `your-recipe/README.md` and insert your recipe information
- If you need to add an image, please place it in `./media` and ensure there are no name conflicts. `uuid4` file names are recommended. (note: images will be resized via `mogrify -resize 320x240 *`, and HEIC is not supported)
- Add the following code to the main `README.md` under `Recipes`: `- [your-recipe](your-recipe/README.md)`