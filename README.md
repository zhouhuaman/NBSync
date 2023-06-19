# NBSync
We implemented NBSync based on MXNET. Specifically, we added codes in the following files:

src/kvstore/kvstore_dist.h
src/kvstore/kvstore_dist_server.h
src/kvstore/kvstore_local.h
3rdparty/ps-lite/include/ps/kv_app.h
3rdparty/ps-lite/include/internal/message.h
3rdparty/ps-lite/src/van.cc

## Usage

Users can use the files in the 3rdparty/ps-lite/ and src/kvstore directories in this warehouse to replace the files in the corresponding directories in MXNET to use NBSync.


