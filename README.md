# Task List

**🌐 [https://task-list-5la.pages.dev](https://task-list-5la.pages.dev)**

[English](#english) · [中文](#中文)

---

## English

A cute, simple daily to-do list. Open the link and start adding tasks. No sign-up needed.

### Features

- **One day at a time**: a week strip at the top lets you jump between days. The ← → keys switch days too.
- **Edit**: tap **Edit** (top right) to add a task with a date, time and note.
- **Pick several days at once**: in the Date calendar, tap more than one day to add the same task to each of them.
- **Star**: a starred task shows a reminder on the day before.
- **Countdown**: mark an upcoming task as a countdown, and every day shows how many days are left.
- **Roll over**: unchecked tasks move to today automatically.
- **Notes**: UMass academic calendar dates and Chinese traditional festivals, editable.
- **Learn every day**: tap the line under the title for a short daily English dialogue.
- **Little surprises**: finish everything for the day and the background celebrates with you.

### Your data

- Everyone gets their own private list. Nobody else can see yours.
- At first, your list is saved on this device only.
- Tap **Sync with Google** to keep it safe and use it on your phone and computer.

### Files

| File | What it is |
|---|---|
| `index.html` | The whole page |
| `config.js` | Firebase settings (set once, no need to change) |
| `firestore.rules` | Database rules: each user can only read and write their own data |

### Updating

Upload a new `index.html` to this repository (Add file → Upload files). Cloudflare Pages republishes it within a minute or two. `config.js` stays as it is, and nobody's tasks are affected.

---

## 中文

一个可爱、简洁的每日待办清单。打开网址就能直接用，不用注册。

### 功能

- **每天一页**：顶部的一周日历可以切换日期，键盘的 ← → 也能切换。
- **编辑**：点右上角 **Edit**，填写日期、时间、任务和备注。
- **一次选多天**：在日期的小日历里同时点选多天，同一件事会添加到每一天。
- **星标**：加星的任务会在前一天出现提醒。
- **倒计时**：给未来的事情打上倒计时标记，每天都会显示还剩几天。
- **自动顺延**：没打勾的任务会自动移到今天。
- **Notes**：显示 UMass 校历和中国传统节日，可以自己编辑。
- **每日英语**：点标题下面那行小字，展开当天的英语小对话。
- **小惊喜**：当天的任务全部完成后，背景会有庆祝特效。

### 数据与隐私

- 每个人都有自己独立的清单，别人看不到你的内容。
- 一开始，清单只保存在当前这台设备上。
- 点 **Sync with Google** 用 Google 账号登录后，数据就不会丢，手机和电脑之间也能同步。

### 文件说明

| 文件 | 作用 |
|---|---|
| `index.html` | 整个网页 |
| `config.js` | Firebase 配置（只需设置一次，以后不用改） |
| `firestore.rules` | 数据库规则：每个用户只能读写自己的数据 |

### 如何更新

把新的 `index.html` 上传到这个仓库（Add file → Upload files）。Cloudflare Pages 会在一两分钟内自动重新发布。`config.js` 不用动，也不会影响任何人的任务。
