
To use the extractor on Windows, simply unzip this file and then drag the recorded .ts file onto the extract.bat file. This should create the file output.zip in the same directory.

Remember to move output.zip to another directory or delete it before running the extractor again.

If you instead prefer to use the command line, cd into the directory containing extract.bat and type:

extract.bat <name_of_recorded_file.ts>

This should create output.zip

If you are on linux, use the `extract` command directly like so:

```
chmod 755 extractor
./extractor <name_of_recorded_file.ts> 1003 output.zip
```

In the release, a test recording is included called recording.ts in the sample directory

You can try extracting from this file to verify that the program is working by dragging it onto `extract.bat` or running from the command line.
