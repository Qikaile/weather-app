# 天气应用
检查地球上任何城市的当前天气。在公制和英制单位之间切换。

![weather-app](https://cdn.jsdelivr.net/gh/Qikaile/cdn@master/img/weather-app.4n938hwq10u0.gif)

## 本地安装教程

1. `git clone https://github.com/qikaile/weather-app.git`
2. `cd weather-app`
3. `npm install`
4. 登录 [Openweathermap.com](https://openweathermap.org/)
5. 创建 API 密钥
![Snipaste_2021-08-07_17-03-42](https://cdn.jsdelivr.net/gh/Qikaile/cdn@master/img/Snipaste_2021-08-07_17-03-42.uaempqa41r4.jpg)
6. `cp .env.example .env.local`
7. 粘贴 API 密钥 `OPENWEATHER_API_KEY`
打开.env.local文件，修改为OPENWEATHER_API_KEY=API密钥（修改为你的API秘钥）
找到你需要的城市，打开pages文件夹下index.js文件中例：const [input, setInput] = useState("Ma'anshan"); Ma'anshan可以修改为你自己的城市
![Snipaste_2021-08-07_17-07-46](https://cdn.jsdelivr.net/gh/Qikaile/cdn@master/img/Snipaste_2021-08-07_17-07-46.41v3nduq8iy0.jpg)
8. `npm run dev`

## 部署到Vercel
1、fork本项目
2、前往Vercel官网，添加新项目，导入github项目
3、Vercel 环境name为OPENWEATHER_API_KEY    VALUE值为之前获取的API密钥值，添加后点击部署即可。

## 说明：

本项目是来自原作版：<https://github.com/madzadev/weather-app>，本文在此基础做了些许修改。
