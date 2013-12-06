effective-tts
=============

## Usage

```
#Streaming play with tts
audite test.mp3 | say "hello"
#Streaming play after tts
audite test.mp3 ; say "hello"
```

## Requirements

* [audite](https://github.com/georgi/audite)
* Portaudio >= 19
* Mpg123 >= 1.14

## Requirements Install

```
brew install portaudio
brew install mpg123

gem install audite
```
