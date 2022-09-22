## step 1
type this in any chat:
`/devtools`
## step 2
click on `explore account data`
## step 3
select m.widgets
## step 4
click edit
## step 5
change the event to this (replacing <username> with your username, e.g. @username:matrix.org).
```json
{
  "type": "m.widgets",
  "content": {
    "stickerpicker": {
      "content": {
        "type": "m.stickerpicker",
        "url": "https://cafkafk.github.io/stickerpicker/web/?theme=$theme",
        "name": "Stickerpicker",
        "data": {}
      },
      "sender": "<username>",
      "state_key": "stickerpicker",
      "type": "m.widget",
      "id": "stickerpicker"
    }
  }
}
```
## step 6
???
## step 7
profit!
