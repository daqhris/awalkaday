# awalkaday.art Photography Collection
This is the __code repository__ of a website, mainly built in _JavaScript_, that is used to host a digital photography gallery.  

<img src="https://raw.githubusercontent.com/daqhris/awalkaday/master/assets/icons/awalkaday_art-web_overview.png" alt="website overview screenshot">  

## Highlights
1. __Easy__ setup and __lightweight__ photo gallery.
2. __No complex code__ changes required. 
3. __Responsive & Fast__ display for __Web and Mobile__ devices.

## Quick Start
If you have basic knowledge of web development and you like photography, then this open-source project may help you set up a web application to showcase all your creations without much effort.  

**Follow the steps below and your website will be live in no time:**

1. Fork this repo by hitting the `Fork` button at the top right corner.
2. Enable _Github Pages_ from the repo settings.
3. Upload your pictures to the `images` directory. (You may do that on github.com itself or you may clone and push the images to your repo.)
4. Add your own custom domain in the `CNAME` file or just remove the file if you don't own a domain and use the default domain that GitHub provides.
5. Update the `baseurl` field in the `_config.yml` file with whatever domain you used in step #4.
6. And that's it, your web application is set. To view, go to [beta.awalkaday.art](https://beta.awalkaday.art) (or whatever you have in the CNAME file) and if you don't have one, you can go to [[yourusername].github.io/awalkaday](https://yourusername.github.io/awalkaday).

And, of course, you can modify the words that are shown on the landing page's footer in the `_config.yml` file as well as a few other settings like your social media icons, contact form, etc.  

<img src="https://raw.githubusercontent.com/daqhris/awalkaday/master/assets/icons/awalkaday_art-web_footer.png" alt="website footer screenshot">  
 
## Tips
The website is set up as a [npm](https://www.npmjs.com) package with [gulp](https://gulpjs.com/) to automate image resizing and thumbnail generation.   
You can just do the following before you push your images to GitHub:

1. Fork and then clone the project to your computer.
2. Go inside the project's local folder `$ cd awalkaday`.
3. Install all dependencies by running `$ npm install`. This step might take some time while automatically downloading and installing recent versions of [NodeJS](https://nodejs.org/en/), [ImageMagick](https://imagemagick.org/index.php), [Git](https://git-scm.com/), [Python](https://www.python.org/), Build Tools for your IDE like [Node.js for Visual Studio](https://visualstudio.microsoft.com/vs/features/node-js/) and other required dependencies.
4. Copy all your pictures (if possible in JPG file format, the largest size available, straight from your camera or original files) and put them inside the `images` directory.
5. Run `$ gulp` on the command line inside the git folder in order to resize the images and generate thumbnails.
6. Push your local changes to _github.com_ by using `$ git add --all`, then send a [signed commit](https://docs.github.com/en/github/authenticating-to-github/managing-commit-signature-verification/signing-commits) `$ git commit -S -m "a short and descriptive commit message"` and finally update your remote code repo on GitHub by using `$ git push origin master`.  

## Credits
__Forked__ from: [rampatra/photography](https://github.com/rampatra/photography) — Enhanced for [Jekyll](https://jekyllrb.com/) by [Ram  Patra](https://github.com/rampatra) — Code reused under [GPL-3.0 License](https://raw.githubusercontent.com/rampatra/photography/master/LICENSE).   
__Template__: [Multiverse by HTML5 UP](https://html5up.net/multiverse) — Web designer and developer: [ajlkn](https://aj.lkn.io/).  
__Fonts__: [Source Sans 3](https://github.com/awalkaday/awalkaday-art/blob/master/assets/fonts/SourceSans3-Regular.ttf) — Used under: [SIL Open Font License](https://raw.githubusercontent.com/daqhris/daqhris.github.io/master/style/font/license/OFL.txt).  
__Icons__ made from: [OpenMoji](https://openmoji.org/about/) — Remixed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode).  

## Copyrights
__Code__ Open-source License: [European Union Public License 1.2](https://raw.githubusercontent.com/awalkaday/awalkaday-art/master/LICENSE).    
__Content__ Legal Rights: [Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).  
__Website__ Owner & Developer: [Chris-Armel](https://daqhris.com) [(@daqhris)](https://github.com/daqhris).  

<img src="https://raw.githubusercontent.com/awalkaday/awalkaday-art/master/assets/icons/awalkaday-logo-1x1.png" alt="website logo" width="200" height="200">  
