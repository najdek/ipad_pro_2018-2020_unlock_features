# Unlock features on iPad Pro 2018/2020

Apple decided to limit some iPadOS features only to the newest M1/M2 iPads.

They were telling us that old iPads are too slow to offer good experience. Guess what? These features work perfectly fine on older iPads.

You'll need [TrollStore](https://github.com/opa334/TrollStore) and [Filza File Manager](https://www.tigisoftware.com/default/?p=439).

------

### Unlock external display Stage Manager
- in Filza navigate to: ``/var/containers/Shared/SystemGroup/systemgroup.com.apple.mobilegestaltcache/Library/Caches/``
- open file ``com.apple.MobileGestalt.plist``
- press (ℹ️) button on ``CacheExtra``
- add new key ``qeaj75wk3HF4DwQ8qbIi7g`` with numeric value ``1``
- save changes and reboot iPad

------

### Unlock "Zoomed Out" display option
- in Filza navigate to: ``/var/containers/Shared/SystemGroup/systemgroup.com.apple.mobilegestaltcache/Library/Caches/``
- open file ``com.apple.MobileGestalt.plist``
- press (ℹ️) button on ``CacheExtra``
- add new key ``sQwlfROu8fcD1Qwm8YJVeg`` with numeric value ``1``
- save changes and the option should be visible in display settings

------

Tested on iPad Pro 12.9 2020 with iPadOS 17.0


[Mobile Gestalt keys source](https://theapplewiki.com/wiki/List_of_MobileGestalt_keys)
