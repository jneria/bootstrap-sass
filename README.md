# Bootstrap for Sass StyleSheets

This is a fork of [Bootstrap for Sass](https://github.com/thomas-mcdonald/bootstrap-sass), by Thomas McDonald.  This fork is basically the stylesheets with the ruby stuff stripped out.  It is intended to fit the workflow outlined by WARD PENNEY [here](http://pivotallabs.com/sass-with-bootstrap/).

## Installation

Please see WARD PENNEY's [article](http://pivotallabs.com/sass-with-bootstrap/) for more information on how this is supposed to work.
but basically you should be able to navigate to your "vendors" folder then clone this project there.  Note compared to the folder structure on Ward Penneys site, there is no _bootstrap-responsive.scss in this folder.  That's because this is based on bootstrap 3 and bootstrap 3 is responive by default.  

<!-- ```ruby
gem 'sass-rails', '>= 3.2' # sass-rails needs to be higher than 3.2
gem 'bootstrap-sass', '~> 3.0.0.0.rc'
``` -->

Note, much of the features in bootstrap.scss file are commented out, you should chek this and comment and uncomment as you wish.
## Credits

bootstrap-sass has a number of major contributors:

<!-- feel free to make these link wherever you wish -->
* [Thomas McDonald](https://twitter.com/thomasmcdonald_)
* [Tristan Harward](http://www.trisweb.com)
* Peter Gumeson
* [Gleb Mazovetskiy](https://github.com/glebm)

and a [significant number of other contributors][contrib].

## You're in good company
bootstrap-sass is used to build some awesome projects all over the web, including
[Diaspora](http://diasporaproject.org/), [rails_admin](https://github.com/sferik/rails_admin),
Michael Hartl's [Rails Tutorial](http://railstutorial.org/), [gitlabhq](http://gitlabhq.com/) and
[kandan](http://kandanapp.com/).

[converter]: https://github.com/thomas-mcdonald/bootstrap-sass/blob/3/tasks/converter.rb
[version]: https://github.com/thomas-mcdonald/bootstrap-sass/blob/3/lib/bootstrap-sass/version.rb
[contrib]: https://github.com/thomas-mcdonald/bootstrap-sass/graphs/contributors
[antirequire]: https://github.com/thomas-mcdonald/bootstrap-sass/issues/79#issuecomment-4428595
[jsdocs]: http://getbootstrap.com/javascript/#transitions
