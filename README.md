# xdCAF Xiaomi Redmi Note 7 #

### Setup our local manifest ###

```bash

repo init -u https://github.com/xdroid-CAF/xd_manifest -b twelve

git clone https://github.com/xdCAF-lavender/xd_lavender .repo/local_manifests -b twelve

repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags

```
