# Phone Images

Some old phone images that are hard to find online, but they are very old and do not receive updates!!

## i9300 - Lineage

The zip is on git-lfs, get with`sudo apt install git-lfs` and then clone the repo.

### Verify signature

```
gpg --verify lineage-14.1-20190217-nightly-i9300-signed.zip.sha256.sig lineage-14.1-20190217-nightly-i9300-signed.zip.sha256

# gpg: Signature made Fri 11 Nov 2022 04:20:10 PM CET
# gpg:                using RSA key C8E80ED0D78B29E498A4CC5A37F6517351088202
# gpg: Good signature from "Eliot Roxbergh <eliot@roxbergh.net>" [ultimate]
# gpg:                 aka "Eliot Roxbergh (MaskClaspFarmerOnion789OffendTaxWrathFoot-2N1) <e@r0x.se>" [ultimate]
# gpg:                 aka "Eliot Lagerström Roxbergh <eliot@fripost.org>" [ultimate]
```


#### Hashes should match

```
cat lineage-14.1-20190217-nightly-i9300-signed.zip.sha256
# b08e7def546ec5f2ebe886678a4a34116bf2712f44d19f2770611c1a4b7aca13  lineage-14.1-20190217-nightly-i9300-signed.zip

sha256sum lineage-14.1-20190217-nightly-i9300-signed.zip
# b08e7def546ec5f2ebe886678a4a34116bf2712f44d19f2770611c1a4b7aca13  lineage-14.1-20190217-nightly-i9300-signed.zip
```

## How the signature was created
```
gpg --detach-sign  lineage-14.1-20190217-nightly-i9300-signed.zip.sha256
```

