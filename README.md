# dyld_shared_cache_util
MacOS 12.2.1 Monterey compatible version of dyld_shared_cache_util

# Description
Followed the post here: https://lapcatsoftware.com/articles/bigsur.html to recompile dyld_shared_cache_util for Monterey.
Luckily his instructions still work for MacOS 12.2.1.

Uploaded the Xcode project and the relevant binary (for those who are lazy to compile it) in bin.

# Usage
```dyld_shared_cache_util  -extract ~/shared_cache /System/Library/dyld/dyld_shared_cache_x86_64```

<img width="615" alt="Screenshot 2022-02-28 at 9 25 17 PM" src="https://user-images.githubusercontent.com/524826/155990823-9367c8d0-fa54-4e93-bede-eb42d2d45681.png">
