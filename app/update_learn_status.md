* 功能: 更新学习进度，把当前节点标记为 学习中 或 已学完，计算整个课程的学习进度百分比，以及本次最新学到的节点 id

* (GET) URL: /api/app/updateLearnStatus/:lesson_id

* request
```
http://apptest.bstcine.com/api/app/updateLearnStatus/42?token=cb84Rvnc&content_id=1397&status=1&last_tag=1&last_position=1000
```

* 备注
last_tag 上一次学习到的片段序号，从 0 开始计数
last_position 上一次学习到的片段播放的位置（毫秒）
status 1:学习中 2:已学完

* response
```
{
    "status": true,
    "data": {}
}
```
