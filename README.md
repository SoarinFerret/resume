# My Resume

*A simple Jekyll + GitHub Pages powered resume template forked from https://github.com/jglovier/resume-template*

*I plan to add my feature additions upstream at some point, but if you'd like to simply fork my resume instead, thats fine too! Just don't copy my achievements :)*

## Docs

### Running locally

#### Using Docker

On Linux:
```bash
docker run -it --rm -v "$PWD":/usr/src/app -p "4000:4000" starefossen/github-pages
```

On Windows (in PowerShell):
```powershell
docker run -it --rm -v "$($PWD.Path):/usr/src/app" -p "4000:4000" starefossen/github-pages
```

#### On your machine

To test locally, run the following in your terminal:

1. Clone repo locally
2. `bundle install`
3. `bundle exec jekyll serve`
4. Open your browser to `localhost:4000`

## Customizing

First you'll want to fork the repo to your own account. Then clone it locally and customize, or use the GitHub web editor to customize.

### Options/configuration

Most of the basic customization will take place in the `/_config.yml` file.


### Editing content

Most of the content configuration will take place in the `/_layouts/resume.html` file. Simply edit the markup there accordingly

## Known Issues

* Rating circles for Software Skills do not line up properly when printing view vs render view
* Text does not wrap around the left sidebar float
* 'Sofware' section in mobile is missing the top header
* Rendering issues for print in Firefox & Edge

## License

The code and styles are licensed under the MIT license. [See project license.](LICENSE)