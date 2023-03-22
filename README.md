# mollutalk-official

This is a translation file for the [MolluTalk Official](https://mollutalk.com/official/en/1)

If there is a typo or correction, please make a full request.

twitter - [@Raun0129](https://twitter.com/Raun0129)

any typos in character or site - [go this way](https://github.com/Raun0129/mollutalk-json)

----
## official_directory.json

There is information about the Blue Archive momotalk.

### Structure
```
[
  {
    "series_no": 189,                     // If you want to add a new official talk, it should be higher than the previous number.
    "series_idx": 3,                      // The order of the series, it should be higher than the previous number.
    "profile_no": 12,                     // Profile picture for this talk. Character number in mollutalk-json/character_directory.json
    "profile_idx": 3,                     // The order of the Profile. Profile number in mollutalk-json/character_directory.json
    "characters": [12],                   // The character number that appears in the talk [...character_no]
    "file_name": "official_189_3.json",   // Corresponding Talk Name, official_[series_no]_[series_idx].json
    "series_title": {
      "kr": "하루카의 인연스토리",
      "jp": "하루카의 인연스토리",
      "en": "하루카의 인연스토리",
      "zh_cn": "하루카의 인연스토리",
      "zh_tw": "하루카의 인연스토리"
    },
    "title": {
      "kr": "차가운 바람, 따듯한 햇볕(번역)",
      "jp": "차가운 바람, 따듯한 햇볕(번역)",
      "en": "차가운 바람, 따듯한 햇볕(번역)",
      "zh_cn": "차가운 바람, 따듯한 햇볕(번역)",
      "zh_tw": "차가운 바람, 따듯한 햇볕(번역)"
    },
    "writer": {                           // The nickname of the person who translated it [...nickname]
      "kr": ["Molru"],
      "jp": [""],
      "en": [""],
      "zh_cn": [""],
      "zh_tw": [""]
    }
  },
  ...
]
```
----
## lang/official_[series_no]_[series_idx].json

Blue Archive momotalk. Mollutalk ver.

### Structure
```
[
  {                                             // mollutalk header - unnecessary
    "title": "고서관의 주인",                    
    "nickname": "Molru",
    "date": "2022-10-23 22:34:13",
    "replyNo": 5,
    "replyGroup": 3,
    "chars": [80]
  },
  [
    {
      "type": "chat",                           // chat type : { chat | reply | image | heart | info }
      "replyNo": 0,                             
      "replyGroup": 0,
      "replyDepth": 0,
      "sCharacter": { "no": 80, "index": 1 },   // Character and Profile number in mollutalk-json/character_directory.json
      "content": "진짜…….",                     // chat text or image src 
      "isFirst": true,                          // chat profile display
      "file": ""                                // Do not use
    },
   ]
   ...
]
```
