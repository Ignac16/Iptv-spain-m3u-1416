#!/bin/bash

DIR="$( cd "$( dirname "${BASH_SOURCE[0]}" )" >/dev/null 2>&1 && pwd )"

base=$(streamlink --stream-url https://www.atresplayer.com/directos/atreseries/ best | rev | cut -d/ -f2- | rev)

echo $base/playlist.m3u8
