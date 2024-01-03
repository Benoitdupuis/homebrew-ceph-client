homebrew-ceph-fuse

Ref from https://github.com/mulbc/homebrew-ceph-client.
Ref from https://github.com/ailabstw/homebrew-ceph-fuse. Nautilus support was added.

brew cask install osxfuse
brew tap ailabstw/homebrew-ceph-fuse
brew install ceph-fuse
Note If you have previously installed mulbc/homebrew-ceph-client, please:

brew remove ceph-client
