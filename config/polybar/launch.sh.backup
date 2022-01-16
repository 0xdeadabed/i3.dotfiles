#!/bin/bash

killall -q polybar

polybar evil_bar 2>&1 | tee -a /tmp/polybar.log & disown

echo "Polybar launched..."
