# Absolute Path Maker

[![Build Status](https://travis-ci.org/nerd-components/absolute-path.svg?branch=master)](https://travis-ci.org/nerd-components/absolute-path)
[![Coverage Status](https://coveralls.io/repos/github/nerd-components/absolute-path/badge.svg?branch=master)](https://coveralls.io/github/nerd-components/absolute-path?branch=master)
[![StyleCI](https://styleci.io/repos/69555566/shield?branch=master)](https://styleci.io/repos/69555566)

## Usage

```php
use function Nerd\Utils\AbsolutePath\pathMaker;

$make = pathMaker('/some/root');

echo $make('file'); 		// /some/root/file
echo $make('../foo.txt'); 	// /some/foo.txt
echo $make('./other.txt');	// /some/root/other.txt
```
