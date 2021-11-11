![XD_LAVENDER](https://github.com/xyz-prjkt/xyz_assets/raw/main/xd_la_ba.png)

# xdCAF Xiaomi Redmi Note 7 #
### Setup our local manifest ###

```bash

repo init -u https://github.com/xdroid-CAF/xd_manifest -b eleven

```
```bash

git clone https://github.com/xdCAF-lavender/xd_lavender .repo/local_manifests -b eleven

```
```bash

repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags

```
