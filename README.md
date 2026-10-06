# weibo_face_image
新浪微博表情库


https://api.weibo.com/2/emotions.json?source=1362404091  --> emotions.json
https://weibo.com/ajax/statuses/config  --> statuses_config.json
emotions.json ∪ statuses_config.json --> merged.json

ps: `statuses_config.json`里的"PC热门表情"与`emotions.json`里的category=""视作同一个分类，为"PC热门表情"
