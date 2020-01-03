Chart.js初体验
===============

## 知识点

* 编写第一个HeloWorld图表

## 实战演习

~~~html
<!DOCTYPE html>
<html lang="zh-cmn-Hans">
<head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>小马技术 | Chart.js</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" type="text/css" media="screen" href="/myweb/style/main.css" />
    <script src="/myweb/chartjs/Chart.bundle.js"></script>
</head>
<body>
    <canvas id="myChart">
        图表区
    </canvas>

    <script>
        (function () {
            'use strict';

            var ctx = document.getElementById('myChart').getContext('2d');
            var chart = new Chart(ctx, {
                options: {
                    title: {
                        display: true,
                        text: 'Helo World!你好，世界！',
                        fontColor: 'red',
                        fontSize: '24'
                    }
                }
            });
        })();
    </script>
</body>
</html>
~~~

## 课程文件

https://github.com/komavideo/LearnChartJS

## 小马视频频道

http://komavideo.com
