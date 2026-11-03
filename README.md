# 上班鼓励器

离想要的生活更近一点：根据月薪与工作日历估算时薪、今日收入和愿望清单进度。

- App: https://joynary.github.io/work-cheer/
- Latest downloadable package: https://github.com/Joynary/work-cheer/releases/latest/download/work-cheer.zip
- Public source and issue tracker: https://github.com/Joynary/work-cheer

## 功能

- 月薪按自定义月工作天数、双休，或可设置参照周的大小周折算为时薪。
- 自定义上班、下班和不计薪休息时间。
- 添加愿望和预算，按当前折算时薪估算还需工作的时间。
- 安装为 PWA，并缓存应用资源以支持离线访问。
- 薪资、计时和愿望数据只保存在当前浏览器。

工资数值均为估算，不含税费、加班费、补贴或工资单差异。午休时段按班次中点估算。

## 本地运行

```sh
python -m http.server 4173 --directory work-cheer
```

Open `http://localhost:4173`. PWA installation requires HTTPS or localhost.

## 更新和发布

Push changes on `main` to deploy GitHub Pages. Push a `v*` tag to create a GitHub Release with `work-cheer.zip`.