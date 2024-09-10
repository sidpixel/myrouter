# AutoBuild-OpenWrt

Build OpenWrt firware [Lienol's OpenWrt 19.07](https://github.com/Lienol/openwrt) using GitHub Actions
Build OpenWrt firware [Immortalwrt's OpenWrt 18.06](https://github.com/immortalwrt/immortalwrt) using GitHub Actions  

Hereby thank P3TERX for his amazing job: https://github.com/P3TERX/Actions-OpenWrt/

## Usage

- Sign up for [GitHub Actions](https://docs.github.com/en/actions)
- Fork [this GitHub repository](https://github.com/sidpixel/myrouter)
- Click [.github/workflows] folder on the top of repo and you could see few workflow files, Each for one particular architecture(device).
- Edit the workflow file you desire，uncomment push section 3 lines together and submit the commit.(Other 2 methods wait you to discover)
- The build starts automatically. Progress can be viewed on the Actions page.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.
- Default Web Admin IP: `10.0.0.1`, username `root`，password `password`


