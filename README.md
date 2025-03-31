# OmniLRS_assets
Assets for the OmniLRS simulator. Large files are hosted via GIT LFS


## Setup

1. Install git LFS (only needed once per user per machine)
```bash
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash
sudo apt install git-lfs
git lfs install
```
2. Clone this git repository
```bash
git clone https://github.com/jaops-space/OmniLRS_assets.git
```
3. Make sure that the LFS tracked files (e.g .USD and .PNG) are properly downloaded (not just pointers). For instance check that assets folder is populated. If not, run
```bash
cd OmniLRS_assets
git lfs fetch
git lfs pull
```

> [!TIP]
> Feel free to fork this repository to work on the assets. The LFS usage will be billed on the quota of this repository, not on you.
Learn more about git LFS: [ref1](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-storage-and-bandwidth-usage#tracking-storage-and-bandwidth-use)
[ref2](https://docs.github.com/en/repositories/working-with-files/managing-large-files/collaboration-with-git-large-file-storage#pushing-large-files-to-forks)
