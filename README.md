# srt-adjust
PHP script to adjust an SRT (subtitle file) forwards or backwards in milliseconds

## Usage

Run `./srt-adjust` with the .srt filename and how many milliseconds you want to adjust. A negative value will make the subtitles start sooner, and a positive value will make them start later.

Examples:
* Make the subtitles in Aliens start a quarter second earlier `./srt-adjust "Aliens (1986).en.srt" -250`
