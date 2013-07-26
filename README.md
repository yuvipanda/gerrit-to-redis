# gerrit-to-redis #

Simple script that reads from `gerrit stream events` and writes them into
multiple redis *queues*. This is meant to be run on [Wikimedia Tool Labs][1].

A tool can request for access to this service by poking Yuvipanda
