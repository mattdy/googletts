# googletts
## Introduction

Simple Python script that takes a single text argument and passes into the Google Translate Text-to-Speech engine.

Breaks the given text down into chunks, separated by punctuation (and by length if necessary), before making the necessary requests

## Changes
### Version 1.1 - 01/08/15
* Update to use new arguments required, now that the translate_tts URL is subject to CAPTCHA verification

## Requirements

mpg123 is required to play the resulting MP3 file returned by Google TTS

## Use

`./googletts "Hello world"`
