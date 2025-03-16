# Lovey Dovey AI聊天应用原型

这是一个类似Lovey Dovey的AI聊天应用的高保真原型，使用HTML和Tailwind CSS实现。

## 项目结构

```
lovey-dovey-app/
├── css/                  # CSS文件夹（暂未使用，使用了内联样式）
├── js/                   # JavaScript文件夹（暂未使用）
├── images/               # 图片资源文件夹（暂未使用，使用了在线图片）
├── pages/                # 页面文件夹
│   ├── character_gallery.html        # 人物卡功能页面
│   ├── character_detail.html         # 角色详情页面
│   ├── chat_list.html                # 聊天列表页面
│   ├── chat_detail.html              # 聊天详情页面
│   ├── model_selection.html          # AI模型选择页面
│   ├── character_creation.html       # 人设卡创作页面
│   ├── character_creation_detail.html # 人设卡创作详情页面
│   ├── community.html                # 兴趣社区页面
│   ├── community_detail.html         # 社区详情页面
│   ├── profile.html                  # 个人中心页面
│   ├── settings.html                 # 设置页面
│   └── components.html               # 通用组件页面
└── index.html            # 主入口文件，使用iframe展示所有页面
```

## 功能列表

1. **人物卡功能页面 (Character Gallery)**
   - 官方角色展示区
   - 角色列表展示(包含角色头像、名称、简介等)
   - 角色详情页(包含角色背景故事、性格特点、对话风格等)
   - 角色分类和筛选功能
   - 角色收藏功能
   - 用户创作角色区
   - 热门角色排行榜
   - 最新角色推荐
   - 点赞和评论功能
   - 分享功能

2. **消息页面 (Chat & Messages)**
   - 多角色会话列表
   - 会话预览
   - 未读消息提醒
   - 置顶会话功能
   - AI模型选择功能
   - 好感度系统
   - 聊天功能

3. **人设卡创作页面 (Character Creation)**
   - 创作引导系统
   - 角色属性编辑
   - 专属头像上传/生成
   - 场景设置

4. **兴趣社区页面 (Community)**
   - 社区管理
   - 社区互动
   - 社交功能

5. **个人中心页面 (Profile)**
   - 基础信息管理
   - 分享奖励系统
   - 其他功能

## 使用方法

1. 打开 `index.html` 文件，可以看到所有页面的预览
2. 点击各个页面可以查看详细设计
3. 所有页面都是使用HTML和Tailwind CSS实现的，可以直接用于开发

## 设计特点

- 使用了iOS设计风格，适配iPhone 15 Pro尺寸
- 添加了顶部状态栏和底部导航栏，模拟真实的手机界面
- 使用了真实的UI图片，而非占位符图片
- 所有界面都是高保真的，可以直接用于开发

## 技术栈

- HTML5
- Tailwind CSS
- Font Awesome 图标库

## 注意事项

- 这是一个静态原型，没有实际的功能实现
- 所有的交互都是模拟的，没有实际的后端支持
- 图片来源于Unsplash，仅用于演示 