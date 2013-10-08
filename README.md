PHP MP3 Chords, Scale and Time Signature Finder
===

### About

Finds the original key used by the mp3 track. Generates Musical Instrument Tabulature and Standard Music Notation.lotting them on a GD canvas.

This code was adapted by [Ixibot](http://ixibot.com).

### Requirements

- PHP 5+
- LAME MP3 Encoder (Windows build available from http://www.rarewares.org/mp3-lame-bundle.php)
- Web server (Apache, etc -- unless modified to run as a command line script)

### Usage/Installation

- Copy to a location on your web server
- Ensure that the 'lame' command is accessible and executable from that directory (for Windows systems, place the downloaded .exe and .dll as linked above into that same directory, or modify the script)
- Ensure the directory support write persmissions, or specify an alternate temporary output directory that does - 
- Launch the script in your browser (e.g. http://localhost/php-waveform-png.php) and upload your MP3 file along with a selection of output settings (dimensions, colours, etc)

### License

Please see the LICENSE file.
