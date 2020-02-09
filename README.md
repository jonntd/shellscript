rclone copy --drive-server-side-across-configs --rc --rc-addr="localhost:5572" -vv --ignore-existing --tpslimit 3 --transfers 3 --drive-chunk-size 32M --disable ListR --drive-acknowledge-abuse Z:/APP Y:/asdf



rclone copy -vv --ignore-existing --tpslimit 3 --transfers 3 --drive-chunk-size 32M --disable ListR --drive-acknowledge-abuse Z:/APP Y:/asdf
