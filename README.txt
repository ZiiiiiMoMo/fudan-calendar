复旦大学 2026 秋季课表 - iPhone 订阅日历

免费部署方法（GitHub Pages）：

1. 在 GitHub 新建一个 Public（公开）仓库，例如：
   fudan-calendar

2. 把本目录里的 calendar.ics 上传到仓库根目录。

3. 打开仓库：
   Settings -> Pages

4. 在 Build and deployment / Source 中选择：
   Deploy from a branch

5. Branch 选择：
   main
   /(root)

6. 保存后，GitHub Pages 会生成一个网址，格式通常类似：
   https://你的GitHub用户名.github.io/fudan-calendar/

7. 你的课表订阅地址就是：
   https://你的GitHub用户名.github.io/fudan-calendar/calendar.ics

iPhone 添加方式：
设置 -> App -> 日历 -> 日历账户 -> 添加账户 -> 其他 -> 添加已订阅的日历
把上面的 calendar.ics HTTPS 地址粘贴进去即可。

之后如果课表变化，只需替换 GitHub 仓库里的 calendar.ics。
iPhone 的“已订阅日历”会从同一个地址获取更新。

注意：
- GitHub 仓库必须公开，才能使用 GitHub Free 的 Pages。
- 这个文件只包含课程名称、教师、教室、周次等课表信息，请确认你可以接受这些信息公开可访问。
