# GitHub Publish Steps

## 1. Publish the local repository

In GitHub Desktop:

1. Open the local repository folder.
2. Click `Publish repository`.
3. Use the name `uss-texture-packer`.
4. Set visibility to `Public`.
5. Confirm publish.

## 2. Create the GitHub release

On GitHub in the browser:

1. Open the published repository.
2. Go to `Releases`.
3. Click `Draft a new release`.
4. Tag: `v1.0.0`
5. Title: `USS Texture Packer v1.0.0`
6. Paste the contents of `GITHUB_RELEASE_BODY_v1.0.0.md`
7. Upload this file as the release asset:

`D:\WORK\UNREAL\USS\06_LAUNCH_ONLY\FAB_LAUNCH_STAGING\08_Texture_Packaging_Tool_Companion\12_Release_Package\USS_TEXTURE_PACKER_v1_0_0.zip`

## 3. Final check

- The repo itself should contain docs and screenshot only.
- The binary should be attached to the GitHub release, not committed into the repo.
- If everything looks good, click `Publish release`.
