# Copy-Jira-Commit

# Usage
```
$ yarn
$ yarn dev
$ yarn build
```

# How to install

Step 1: download or git clone

Step 2: open chrome://extensions/

Step 3: load unpacked and choose root dir (parent dir of manifest.json)

# Tree
```
|-- index.html   定义 dev 环境使用的html,可以用于本地造一些页面数据进行测试
|-- manifest.json   定义插件的 manifest,指定 build/main.js
|-- vite.config.json    指定 vite build 生成的Path
|-- build
| `-- main.js   插件运行的 js, 需要每次都生成
|-- src 文件夹使用 vue3.0
```


# TODO
* 需要注意防止 xss 攻击

# History

* 2021-04-16 16:32:04 开放 matchURL 至所有站点
* 2021-04-02 16:16:10 当主面板拖到屏幕外面时，可以缩小，增加拖拽检测区域。
* 2021-03-26 10:06:33 限制拖拽不能移除屏幕区域外部
* 2021-03-22 16:04:05 增加linkifyjs功能，之后需要注意防止 xss 攻击
* 2021-03-18 14:30:56 增加【备忘录列表】功能，包括查看详情和删除功能
* 2021-03-17 10:54:33 增加【打开面板】的功能
* 2021-03-15 18:22:36 切换至 vue 3.0 + vite build.
* 2020-09-25 17:33:21 修复在预览视频时 button 样式问题
* 2020-09-17 17:42:45 复制成功提示
* 2020-09-17 17:42:48 按钮可拖拽
* 2020-09-11 17:42:51 增加复制按钮