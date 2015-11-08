master
------

* Introduce file in `app/initializers` to setup Rails CSRF integration [#19]
* Prepend Sprockets path to EmberCLI assets.
  Default fingerprinting to no generate `MD5` hash when building in
  `development`.  [#17].

[#19]: https://github.com/rondale-sc/ember-cli-rails-addon/pull/19
[#17]: https://github.com/rondale-sc/ember-cli-rails-addon/pull/17

0.0.13
------

* Disables [Subresource Integrity][SRI], since the asset pipeline URLs no longer
  match the URLs the SRI hashes were generated against.
* Copies `dist/index.html` to `dist/assets/index.html` after a build

[SRI]: https://github.com/jonathanKingston/ember-cli-sri#what-is-it