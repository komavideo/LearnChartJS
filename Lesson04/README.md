画一个线图
==========

## 知识点

* type图表属性
* data图表数据

## 实战演习

~~~html
    <script>
        (function () {
            'use strict';

            var type = 'line';
            var data = {
                labels: [2014,2015,2016,2017,2018],
                datasets: [
                    {
                        label: '优酷',
                        data: [100, 200, 400, 800, 1600]
                    },
                    {
                        label: 'Youtube',
                        data: [50, 100, 200, 400, 600]
                    }
                ]
            };

            var ctx = document.getElementById('myChart').getContext('2d');
            var chart = new Chart(ctx, {
                type: type,
                data: data,
                options: {
                    title: {
                        display: true,
                        text: '小马视频',
                        fontColor: 'green',
                        fontSize: '24'
                    }
                }
            });
        })();
    </script>
~~~

## 课程文件

https://github.com/komavideo/LearnChartJS

## 小马视频频道

http://komavideo.com
