# Notes on interviews



## Transcriptions

When cleaning up the transcripts, I plan to clean up words like "um", "ah", etc.

### Auto transcriptions

Zoom's auto-transcription produces closed caption `.vtt` files with timestamps in the form of: 

```
4
00:01:00.140 --> 00:01:02.430
```

To find (and replace) these lines, I used the following regular expression (generated from [RegExr](https://regexr.com)):

```
\n\d+\n\d{2}:\d{2}:\d{2}.\d{3} --> \d{2}:\d{2}:\d{2}.\d{3}
```