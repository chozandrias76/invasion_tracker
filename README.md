# Elden Ring Invasion Tracker
This Ruby gem is designed to automatically track the results of an invasion. It's a time-saving tool for content creators who use Genobot to submit to an invasion leaderboard.

## What it does
The tool uses Optical Character Recognition (OCR) to track invasions in your live gameplay. It can handle a single 4k video input device.

## Usage

### Prebuilt
Check the release page, and download the appropriate binary for the latest version.

### Build your own
Clone the git repository
```bash
git clone https://github.com/chozandrias76/invasion_tracker
```

Change working directory
```bash
cd invasion_tracker
```

Make sure you have ffmpeg & tesseract installed
```ps1
$ choco install ffmpeg
$ choco install tesseract
```

Start the background process
```bash
./bin/invasion_tracker
```

Final output in 
```
/Users/username/Desktop/invasion_tracker:
  /2024/12:
    6.txt
```

## Testing Environment
My test files are taken from the game during real scenarios 

## Contributing
Contributions are welcome! If you're interested in improving this tool or adding support for other platforms, please feel free to submit a pull request or open an issue.

## License
MIT-LICENSE
