# mgid/phpmorphy

phpMorphy --- morphological analyzer library for Russian, English, German and Ukrainian languages.  


Source website (in russian): http://phpmorphy.sourceforge.net/  
SF project: http://sourceforge.net/projects/phpmorphy  
Wrapper on Github: https://github.com/cijic/phpmorphy

This library allow retireve follow morph information for any word:
- Base (normal) form
- All forms
- Grammatical (part of speech, grammems) information

## Install

Via Composer
``` bash
$ composer require mgid/phpmorphy
```

## Usage
``` php
$morphy = new mgid\phpMorphy\Morphy('en');
echo $morphy->getPseudoRoot('FIGHTY');
```
