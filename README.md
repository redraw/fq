# linefreq

## Install
```
pip install linefreq
```

## Usage

```
curl -s https://github.com | grep -oE "<\w+>" | fq
<picture> [35] 100.00% ████████████████████████████████████████
     <li> [28] 80.00%  ████████████████████████████████
   <span> [26] 74.29%  ██████████████████████████████
    <div> [13] 37.14%  ███████████████
     <em> [5]  14.29%  ██████
    <var> [5]  14.29%  ██████
 <strong> [3]  8.57%   ███
     <br> [3]  8.57%   ███
   <head> [1]  2.86%   █
  <title> [1]  2.86%   █
     <dt> [1]  2.86%   █
     <dd> [1]  2.86%   █
    <del> [1]  2.86%   █

123 samples.
```

```
usage: fq [-h] [-n TOP] [-t {bar,hist}] [-a] [-w MAX_WIDTH] [-f] [-s] [FILE]

positional arguments:
  FILE                  file or stdin (default: <_io.TextIOWrapper
                        name='<stdin>' mode='r' encoding='utf-8'>)

optional arguments:
  -h, --help            show this help message and exit
  -n TOP, --top TOP     top N samples / bins (default: 15)
  -t {bar,hist}, --type {bar,hist}
                        bar for categorical data, or hist for numerical
                        (default: bar)
  -a, --force-ascii     force ascii *, by default renders unicode (default:
                        False)
  -w MAX_WIDTH, --max-width MAX_WIDTH
                        max symbol width (default: 40)
  -f, --fullscreen      show at full screen (default: False)
  -s, --stats           print stats on exit (only for histogram) (default:
                        True)
```
