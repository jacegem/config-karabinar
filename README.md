# config-karabinar


```
git clone https://github.com/jacegem/config-karabinar.git ~/.config/karabinar
```

## 수정 내역

```
"manipulators": [
    {
        "description": "Change caps_lock to control+option.",
        "from": {
            "key_code": "caps_lock",
            "modifiers": {
                "optional": [
                    "any"
                ]
            }
        },
        "to": [
            {
                "key_code": "left_control",
                "modifiers": [
                    "left_option"
                ]
            }
        ],
        "type": "basic"
    }
```