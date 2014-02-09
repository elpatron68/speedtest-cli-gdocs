speedtest-cli
=============

Command line interface for testing internet bandwidth using
speedtest.net

Versions
--------

speedtest-cli-gdocs works with Python 2.4-3.4

Installation
------------

Github
~~~~~~

::

    pip install git+https://github.com/elpatron68/speedtest-cli-gdocs.git

or

::

    git clone https://github.com/elpatron68/speedtest-cli-gdocs.git
    python speedtest-cli-gdocs/setup.py install

Just download (Like the way it used to be)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

    wget -O speedtest-cli https://raw.github.com/elpatron68/speedtest-cli-gdocs/master/speedtest_cli-gdocs.py
    chmod +x speedtest-cli-gdocs

or

::

    curl -o speedtest-cli https://raw.github.com/elpatron68/speedtest-cli-gdocs/master/speedtest_cli-gdocs.py
    chmod +x speedtest-cli-gdocs

Usage
-----

::

    $ speedtest-cli-gdocs -h
    usage: speedtest-cli-gdocs [-h] [--share] [--simple] [--list] [--server SERVER]
                               [--mini MINI] [--source SOURCE] [--version]
                               [--gmailuser USER] [--gmailpass PASSWORD]
                               [--spreadsheetkey ID] [--worksheetid ID]

    Command line interface for testing internet bandwidth using speedtest.net.
    --------------------------------------------------------------------------
    https://github.com/elpatron68/speedtest-cli-gdocs

    optional arguments:
      -h, --help       show this help message and exit
      --share          Generate and provide a URL to the speedtest.net share
                       results image
      --simple         Suppress verbose output, only show basic information
      --list           Display a list of speedtest.net servers sorted by distance
      --server SERVER  Specify a server ID to test against
      --mini MINI      URL of the Speedtest Mini server
      --source SOURCE  Source IP address to bind to
      --version        Show the version number and exit
      --gmailuser      Google account: user
      --gmailpass      Google account: password
      --spreadsheetkey Key of the spreadsheet (from Google Drive URL - key=)
      --worksheetid    Worksheet ID ('od6' for first sheet)

