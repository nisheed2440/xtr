![XTR LOGO](/src/assets/xtr_logo_black.png "XT Tech Radar")

![XTR Screenshot](/src/assets/xtr_screenshot.PNG "XT Tech Radar Screenshot")

[![All Contributors](https://img.shields.io/badge/all_contributors-16-orange.svg?style=flat-square)](#contributors)

# XT Tech Radar

[XT Tech Radar](https://xt-techradar.com) is a document that sets out to help us get in touch with the recent trends in technology. What to consider when building up a new tech stack, The scalability and maturity of libraries/framesworks or tools that we use on a day to day basis and how they would play in projects. It reflects the unique opinions of some of the architects, associates and thought-leaders in the field of **eXperience Technology** / __XT__. 

It consists of four quadrants:
* Ubiquitous
* Scale/Grow
* Incubate
* De-emphasize

and three rings:
* Concepts
* Tools/SDK's
* Frameworks

For more information on what the quadrants and the rings stand for, please refer to the [FAQ/Info](/ABOUT.md) page.

XT Tech Radar is heavily influenced by the pioneering working done by the [Thoughtworks Technology Radar](https://www.thoughtworks.com/radar). The graphing used for the our radar is a fork from the "Thoughtworks Technology Radar" [git repository](https://github.com/thoughtworks/build-your-own-radar) with alot of our own customizations.

## How To Contribute
The data for the radar is built from a series of `Markdown` or `.md` files located under `./src/docs` folder. Each `.md` file follows a set structure as defined in the [SAMPLE.md](/SAMPLE.md) file (If you are viewing it in Github, click the `Raw` button to view the original file contents). All the `.md` files within the `./src/docs` folder are then combined by a build process into an `output.json` file which is then served to the Radar at run time.

In order for you to contrubute to the radar you would need to do the following:

1. Fork the repository, so that you have a custom copy of it.
2. Next clone the forked repository locally to have a local copy of it.
3. Next within the project folder on the local machine, create the desired `.md` file based on the concepts, frameworks or tools/sdk's you would like to add.
    * If you want to add for example `jQuery Easing`, you will create a file named `jquery-easing.md` under the `./src/docs` folder.
    * This new file will follow the same format as the [SAMPLE.md](/SAMPLE.md) file.
4. You could then run a build locally as described in [installation](#installing-locally) section, to test your changes.
5. Once all the changes look satisfactory, commit the files locally and push it to your remote forked repository.
6. Finally raise a pull request (**PR**) to the original repository. 

**NOTE:** We will validate the PR and provide any feedback on it. If everything looks good, we will merge the changes to our repository and make it avaialble live on [https://xt-techradar.com](https://xt-techradar.com).

## Installing Locally

1. Fork the repository, so that you have a custom copy of it.
2. Next clone the forked repository locally to have a local copy of it.
3. `cd` into the folder containing the local copy. 
4. Run `npm install`.
5. Run `npm run build:dev && node server.js`. This will automatically run the `gulp` and `webpack` buils and start a local dev server on port `:3000` i.e `http://localhost:3000`.





## Contributors

Thanks goes to these wonderful people :thumbsup: :

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
| <a href="https://github.com/nisheed2440"><img src="https://avatars3.githubusercontent.com/u/3470465?v=4" width="100px;"/><br /><sub><b>Nisheed Jagadish</b></sub></a> | <a href="https://github.com/areai51"><img src="https://avatars0.githubusercontent.com/u/357862?v=4" width="100px;"/><br /><sub><b>Vinci Rufus</b></sub></a> | <a href="https://github.com/kritiaggarwal"><img src="https://avatars3.githubusercontent.com/u/7406582?v=4" width="100px;"/><br /><sub><b>Kriti Aggarwal</b></sub></a> | <a href="https://github.com/Ashishdce"><img src="https://avatars1.githubusercontent.com/u/11964636?v=4" width="100px;"/><br /><sub><b>Ashish Jangid</b></sub></a> | <a href="https://github.com/Rsreelakshmi"><img src="https://avatars2.githubusercontent.com/u/31694005?v=4" width="100px;"/><br /><sub><b>Sree</b></sub></a> | <a href="https://github.com/saurabhkinariwala"><img src="https://avatars2.githubusercontent.com/u/30474228?v=4" width="100px;"/><br /><sub><b>Saurabh kinariwala</b></sub></a> |
| :---: | :---: | :---: | :---: | :---: | :---: |
| <a href="https://github.com/subhendukundu"><img src="https://avatars1.githubusercontent.com/u/20059141?v=4" width="100px;"/><br /><sub><b>subhendukundu</b></sub></a> | <a href="https://github.com/ans990"><img src="https://avatars0.githubusercontent.com/u/26963057?v=4" width="100px;"/><br /><sub><b>Anshul</b></sub></a> | <a href="https://github.com/michaelpackiyaraj"><img src="https://avatars2.githubusercontent.com/u/7973694?v=4" width="100px;"/><br /><sub><b>Michael</b></sub></a> | <a href="https://github.com/Yuvaranei"><img src="https://avatars3.githubusercontent.com/u/25721359?v=4" width="100px;"/><br /><sub><b>Yuvaranei Perumal</b></sub></a> | <a href="http://naveenkumarpg.github.io/"><img src="https://avatars3.githubusercontent.com/u/5549558?v=4" width="100px;"/><br /><sub><b>Naveen Setty</b></sub></a> | <a href="https://github.com/sirius93"><img src="https://avatars3.githubusercontent.com/u/6882879?v=4" width="100px;"/><br /><sub><b>Nandan Kumar</b></sub></a> |
| <a href="https://github.com/kumarranjansingh"><img src="https://avatars1.githubusercontent.com/u/12463387?v=4" width="100px;"/><br /><sub><b>Ranjan</b></sub></a> | <a href="https://gigacore.in/"><img src="https://avatars3.githubusercontent.com/u/278541?v=4" width="100px;"/><br /><sub><b>Santhosh Sundar</b></sub></a> | <a href="https://github.com/aniruddh047"><img src="https://avatars2.githubusercontent.com/u/25810438?v=4" width="100px;"/><br /><sub><b>Aniruddh K.</b></sub></a> | <a href="https://github.com/sauryabhatt"><img src="https://avatars3.githubusercontent.com/u/11456238?v=4" width="100px;"/><br /><sub><b>sauryabhatt</b></sub></a> |
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind welcome!