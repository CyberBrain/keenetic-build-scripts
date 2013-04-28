My scripts for packages building

Configuration:

Create file ~/.keenetic with this content:

    export DATE="$(date +%F_%H-%M-%S)"
    export RSYNC_DST='rsync://192.168.0.1/keenetic'
    export DIR_KEENETIC="$HOME/keenetic"
    export DIR_LOG="$HOME/log"
    export DIR_MAKEFILES="$HOME/makefiles"
