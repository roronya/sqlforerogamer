# sqlforerogamer

[![Build Status](https://travis-ci.org/roronya/sqlforerogamer.svg?branch=master)](https://travis-ci.org/roronya/sqlforerogamer)

## installation

    $ pip install sqlforerogamer

## usage
    >>> import sqlforerogamer
    >>> sqlforerogamer.read_sql("SELECT id  FROM brandlist WHERE id = '1'")
    id
    0  1
