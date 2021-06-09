# WALK≡DAY Visual Arts Gallery
This is the public __code repository__ of a Jekyll static web app largely built in JavaScript for running an online art gallery.

## Highlights
1. __Easy__ setup and __free__ photography website.
2. __No code__ changes required. Just upload your pictures to the repo.
3. __Flexible & fast__ display for __web & mobile__ devices.

## Quick Start
If you have basic knoweldge about web development and you like taking pictures then, this open-source project may help you setup a website to showcase
all your creations without effort.  

**Follow the below steps and your website would be live in no time:**

1. Fork this repo by hitting the `Fork` button at the top right corner.
2. Enable Github Pages from the repo settings.
3. Upload your pictures to `images/fulls` and `images/thumbs` directory. _You can do that on github.com itself or you can clone and push the images to your repo._
4. Add your own custom domain in `CNAME` file or just remove the file if you don't own a domain and use the default domain that GitHub provides ([yourusername].github.io/awalkaday).
5. Update `baseurl` field in `_config.yml` file with whatever domain you used in step 4.
6. And that's it, your website is set. To view, go to [awalkaday.art](http://awalkaday.art) (or whatever you have in the CNAME file) and if you don't have one, you can go to [[yourusername].github.io/awalkaday](http://yourusername.github.io/awalkaday)

And, of course, you can modify the words shown at the landing page bottom in `_config.yml` file as well as few other settings like your Google Analytics, Social Media icons, Contact Forms, etc.
 
## Tips
The website is set up as an [npm](https://www.npmjs.com) package with [gulp](http://gulpjs.com/) to __automate image resizing
and thumbnail generation__. You can just do the following before you push your images to GitHub.

1. Fork and then clone the project to your computer
2. Go inside the project `$ cd awalkaday`
3. Install all dependencies by `$ npm install`
4. Copy all your pictures (possibly jpg, the largest size available, straight from your camera or original files) and put it inside `images` directory
5. Run `$ gulp` to resize the images and to generate thumbnails automatically
6. Push your changes to github.com by using `$ git add --all` and `$ git commit -m "a nice commit message"` and then finally `$ git push origin master`.  

Modified by @daqhris