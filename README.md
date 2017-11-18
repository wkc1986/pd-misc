- `alarm-clock.pd`: alarm clock with snooze functionality.
Currently plays a sine pulse.
One day it will be able to trigger your favorite wake-up music.
Maybe.

- `test-auto-file-loader.pd`: given a text file with one audio file path on each line, automatically generates `table`s in a subpatch and reads each file into a table with `soundfiler`.
Idea is to get around the `soundfiler` dropout by preloading every file.
	- **TODO**: either rename arrays using filenames or map file names to arrays so can select arrays by the name of the loaded file
