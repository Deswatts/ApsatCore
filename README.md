## 简介

- 这是 [Apsat](https://github.com/Deswatts/Apsat) 的核心库
- 包含了对 Minecraft 账户的一部分功能

## 示例

```python
# This is a example for get profile from microsoft
from apsat_core import consts, types, get_profile # Import modules

user_name = "" # Input the profile name


if __name__ == '__main__':
    profile = get_profile.getprofile(
        types.ProfileType(
            consts.TYPE_PROFILE | consts.TYPE_MICROSOFT
        ),
        user_name
    ) # Get profile
    print(profile) # Print result to console
```
