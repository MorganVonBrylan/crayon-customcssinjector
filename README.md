# Crayon: custom CSS injector

Heya! This is a fork of [CustomCSS Injector](https://github.com/blizz31/customcssinjector/)

**You can install it here:** https://addons.mozilla.org/firefox/addon/crayon-custom-css-injector/

Why did I fork it? Here is what I did:

- Updated 3rd-party libraries (Prism and Bliss)
- Improved the pop-up UX:
	- Global/domain/URL rules can now be picked by clicking on the label instead of only the little dot;
	- They also tell you explicitly where the rules will apply;
	- "unsaved changes" indicator;
	- Tells you if the add-on failed to load (happens on special pages like `about:preferences` and such, as well as `mozilla.org` where all addons are disabled);
- Improved granularity: you can now use global, domain and URL rules in tandem instead of them being mutually exclusive for some reason.
- Wildcards in the whitelist and blacklist.
- Most importantly: **an overview page**, accessible via the "overview & help" button in the pop-up
	- Get help with CSS and how the add-on works;
	- See all the rules you have saved;
	- Export/import.

![Crayon logo](icons/crayon_highres.png)

### Licence

Like the original, this project is under the [GNU GPL v3](LICENCE).

### Contribute

I accept pull requests and Liberapay donations: https://liberapay.com/Brylan/

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/brylan)