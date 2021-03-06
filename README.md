# b2gpopulate

b2gpopulate is a tool to populate a
[Firefox OS](https://developer.mozilla.org/en-US/docs/Mozilla/Firefox_OS)
device with content.

## Requirements

Your device must be running a build of Firefox OS with
[Marionette](https://developer.mozilla.org/docs/Marionette) enabled.

## Installation

Installation is simple:

    pip install b2gpopulate

If you anticipate modifying b2gpopulate, you can instead:

    git clone git://github.com/mozilla/b2gpopulate.git
    cd b2gpopulate
    python setup.py develop

## Running

    Usage: b2gpopulate [options]

    Options:
      -h, --help      show this help message and exit
      --calls=int     number of calls to create. must be one of: [0, 50, 100, 200, 500]
      --contacts=int  number of contacts to create. must be one of: [0, 200, 500, 1000, 2000]
      --events=int    number of events to create. must be one of: [0, 900, 1300, 2400, 3200]
      --messages=int  number of messages to create. must be one of: [0, 200, 500, 1000, 2000]
      --music=int     number of music files to create
      --pictures=int  number of pictures to create
      --videos=int    number of videos to create
      --workload=str  workload type to create. must be one of: ['light', 'medium', 'heavy', 'x-heavy']
