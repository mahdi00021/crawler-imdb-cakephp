# CakePHP Application crawler of site imdb

programmer : mahdi norouzi

## This app getting title id , title , cast , media images of every film

## how to using ?

$extract =  new ExtractorImdb();

//Main method for set Data

$extract-> setLoadDataByUrl($url);

$titleId = $extract-> getTitleId();

$title = $extract-> getTitle();

$cast = $extract-> getCast();

$mediaImages = $extract-> getImages();


## Get json of link imdb


$extract-> getMovieInfoByUrl($url);
