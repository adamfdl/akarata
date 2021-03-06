# Akarata

[![Code Climate](https://codeclimate.com/github/ikhsanalatsary/akarata/badges/gpa.svg)](https://codeclimate.com/github/ikhsanalatsary/akarata)
[![Test Coverage](https://codeclimate.com/github/ikhsanalatsary/akarata/badges/coverage.svg)](https://codeclimate.com/github/ikhsanalatsary/akarata/coverage)
[![Build Status](https://travis-ci.org/ikhsanalatsary/akarata.svg?branch=master)](https://travis-ci.org/ikhsanalatsary/akarata)
[![Depedencies Status](https://david-dm.org/ikhsanalatsary/akarata.svg)](https://david-dm.org/ikhsanalatsary/akarata)

Akarata is a JavaScript library to retrieve the root / syllable root (stem) from word stem that does have a prefix in front of the word or  suffix at the end of the word in Indonesian. Akarata is derived from the word "akar kata" in indonesian, for easier pronouncing.

Akarata inspired by stem of word in Indonesian based on Porter Stemmer, using algorithm published in *paper* [**A Study of Stemming Effects on Information Retrieval in Bahasa Indonesia**](http://www.illc.uva.nl/Publications/ResearchReports/MoL-2003-02.text.pdf), by Fadillah Z Tala. 

## Installation

npm:

	npm install --save akarata

yarn:

	yarn add akarata

## Usage

Babel:

	import akarata from 'akarata';
	akarata.stem('menikah'); // nikah


JavaScript:

	var akarata = require('akarata');
	akarata.stem('belajar'); // ajar

Or you can directly try it on this web: [akarata.netlify.com](https://akarata.netlify.com).

Atau mencobanya langsung dari web: [akarata.netlify.com](https://akarata.netlify.com).

## Issues
By cause of this module is still in its development process, submit a [ticket]((https://github.com/ikhsanalatsary/akarata/issues/new)) if you are facing an issue.

## Contributing
This module is intended to be a Javascript implementation of [Apache Lucene](http://lucene.apache.org/)'s Bahasa Indonesia word stemmer.

1. Fork this project
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Make changes and add them (`git add .`)
4. Commit your changes (`git commit -m 'Added some new feature'`)
5. Push to the branch (`git push origin my-new-feature`)
6. Create new pull request


### Reference
1. [Great Dictionary of the Indonesian Language](http://bahasa.kemdiknas.go.id/kbbi/index.php)
2. To look up and verify [Indonesian words](http://kateglo.com/)
3. Wikipedia article (in Bahasa) [Prefixes in Bahasa Indonesia](http://id.wikipedia.org/wiki/Prefiks_dalam_bahasa_Indonesia)



## Thanks

First and foremost, I would like to thank to Allah Subhanahu Wa Ta'ala, that without his blessings this project could not be made. I would like to also thank:

- Faidlah Z Tala & [Apache Lucene](http://lucene.apache.org/) as without them this module could not be made
- [Kateglo Bahtera](http://kateglo.com/) for providing an API so this module could separate ambiguous words and validation.
- Adinda Pradity & [Indonesian Stemmer](https://github.com/apraditya/indonesian_stemmer) for the great mentorship along with her project, this module could be implemented in JavaScript
