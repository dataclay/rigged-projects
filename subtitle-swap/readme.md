# Subtitle Swap — Sample After Effects Project

A simple Autograf demonstrating a technique to swap SRT-formatted subtitles in After Effects with Templater by using expressions on a text layer.

## Description

This project was created in After Effects 2023. 

## Table of Contents

- [Usage](#usage)
- [License](#license)

## Usage

`SRT` subtitle files will need to be renamed with a `JSX` extension for this technique to work. This is because After Effects does not have a native file handler to import SRT files. This subtitle data is swapped into a layer, as footage, on the After Effects Timeline. The SRT/JSX file data is parsed by the expression on the designated text layer. 

Templater data is in `Subtitle Swap Data.json`. 


> 📝 **Important:** 
> if you're having issues with all of the subtitles showing at once, as seen in this [forum post](https://forums.dataclay.com/post/877) it may be an issue with GitHub changing the `JSX` file line endings from `CRLF` (Windows) to `LF` (Unix/MacOS)—or vice versa. You can open these files in a free advanced text editor like [Visual Studio Code](https://code.visualstudio.com/download) or [Notepad++](https://notepad-plus-plus.org/downloads/) and convert them to see if the issue is resolved. On MacOS, you may need to change `LF` or `CRLF` to `CR` (Macintosh). 


## License

You are free to use and remix the expressions in your own projects. The video samples included are the property of Dataclay. 