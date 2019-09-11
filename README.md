curl 'https://oapi.dingtalk.com/robot/send?access_token=338d28b77ccf6adfb5c96095225beb9176daa901b3f7858265a3b2c95b918e22' \
   -H 'Content-Type: application/json' \
   -d '{"msgtype": "text", 
        "text": {
             "content": "王姐夫你个负心汉不请客吃饭"
        }
      }'
