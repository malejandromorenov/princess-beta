# princess_beta
test script ubuntu for install the software in oneline


#!/bin/sh
LIST_OF_APPS="a b c d e"

apt-get update
apt-get install -y $LIST_OF_APPS
