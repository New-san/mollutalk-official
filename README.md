# mollutalk-official

This is a translation file for the [MolluTalk Official](https://mollutalk.com/official/en/1)

Please modify the "content" of [lang]/official_[series_no]_[series_idx].json to match the language and make a full request.

If there is a typo or correction, please make a full request.

twitter - [@Raun0129](https://twitter.com/Raun0129)

----

## official_directory.json - [go this way](https://github.com/Raun0129/mollutalk-json)

and any typos in character or site

----
## [lang]/official_[series_no]_[series_idx].json

Blue Archive momotalk. Mollutalk ver.

### Structure
```
[
  {                                             // mollutalk header
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
