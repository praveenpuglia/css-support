# CSS Support

It's hard to get browser support info about individual CSS properties or rules. [caniuse.com](http://caniuse.com) does a good job of showing what features are supported as a whole by browsers but a large use case is to find out a property or value support.

MDN does well at that. It's a community effort that keeps the docs there up-to-date. The problem is that that data isn't available in a useful form. It's exactly like direct content update on CMS. 

It's also hard to know when features landed behind feature flags in browsers and when they made it to stable. 

CSS Support solves those problems by providing keeping the browser support data in a consumable, centralized way. Let this be the source of truth for every __@ rule__, __property__& __value__ in CSS.

## Current Focus

Currently my focus is on gathering data and putting them together in a way that's consumable.

## TODO
- [ ] Get a list of all standard properties.
- [ ] Get a list of all standard `@` rules.
- [ ] Get a list of all standard selectors.
- [ ] Get a list of standard values for a property.
- [ ] Get browser support info for each property.
- [ ] Get browser support info for each value in each property.
- [ ] Put properties, `@` rules, selectors in their own sections.
- [ ] Have a build process to merge browser support info together.


