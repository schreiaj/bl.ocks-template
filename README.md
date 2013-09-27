#bl.ocks Starter Template

I got so sick of setting up new projects to display on [http://bl.ocks.org] that I built a simple little template I can just pull and use. Figured I'd share it. It uses coffeescript and markdown. The latter isn't optimal but this is a work in progress and I hate writing HTML. If I find myself wanting to use a different tool than markdown, it's a simple change (that's the point of this). I'm opinionated and if you don't like one of my choices for tech stack you can go fork yourself (or this repo).

## Usage

  bundle install

  npm install

  bundle exec foreman start

Then you're ready to edit and create. Seriously, it's that easy. Files will be served at localhost:8000. Coffeescript files will be converted to .js files on save. Markdown will be converted to .html files.
