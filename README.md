# Tidal Song Playing Bot

## How to setup for local machine.

### Install requirements.
* ``pip install -r requirements.txt``

### Run following command to browsec install extension.
* ``python ``[utils.py](utils.py)

Following variables are defined in [config.py](config.py) file.
* ``LINKS_PER_ACCOUNT = 10``
* ``SONGS_PER_URL = 10``
* ``LIKE_SONG_CHANCE = 20``
* ``FOLLOW_ARTIST_CHANCE = 20``
* ``MINIMUM_SONGS_PER_LINK = 5``
* ``MAX_SONGS_PER_LINK = 20``
* ``MINIMUM_LINKS_PER_ACCOUNT = 1``
* ``MAX_LINKS_PER_ACCOUTN = 20``
* ``PROXY_LIST = []``
* ``MAX_THREADS = 2``
* ``USE_PROXY = False``
* ``USE_BROWSEC = True``


Main directory should contains the credentials.txt file with following format on each line.
* ``emailx:password``
* ``emaily:password``

Finally run
* ``python ``[main.py](main.py)

qulfvt