# HandBrakeCLI Batch

Simple script to batch compress videos

## Usage

```
% console compress --help
Usage:
  compress [options] [--] <source> <destination>

Arguments:
  source                Source folder
  destination           Destination folder

Options:
      --auto-increment  Automatically fix the destination filename in case of collision
      --preset=PRESET   HandBrake Preset to use [default: "Very Fast 720p30"]
```

## Dependency

You need to have [Handbrake CLI](https://handbrake.fr/downloads2.php) on your system