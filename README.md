# Library Applications Development Inclusive Language
University of Alberta Library Applications Development team commits to use inclusive language instead of problematic terms in our team's projects and documentation with the help of automated tools such as RuboCop's Naming/InclusiveLanguage cop (https://www.rubydoc.info/gems/rubocop/RuboCop/Cop/Naming/InclusiveLanguage).

Utilized the Edmonton Inclusive Language Guide along with the Android Open Source Project Respectful Code and Inclusive Documentation as a guide and reference for terms that are flagged as problematic and their suggested replacements:

* https://www.edmonton.ca/public-files/assets/document?path=PDF/InclusiveLanguageGuide2019.pdf
* https://source.android.com/docs/setup/contribute/respectful-code
* https://developers.google.com/style/inclusive-documentation#ableist-language
* https://developers.google.com/style/word-list

## How to use this in a project
Inherit the included RuboCop cops by inserting this at top of the project's ```.rubocop.yml``` file:
```
inherit_from:
  - https://raw.githubusercontent.com/ualbertalib/library_applications_development_inclusive_language/main/inclusive_language_rubocop.yml
```
