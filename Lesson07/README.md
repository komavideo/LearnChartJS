线形变换
========

## 知识点

* data.datasets设定(borderColor, borderWidth, ...)

## 实战演习

~~~html
<script>
...
    var data = {
        labels: [2014, 2015, 2016, 2017, 2018],
        datasets: [
            {
                label: '优酷',
                data: [100, 150, 300, 800, 1600],
                borderColor: 'red',
                borderWidth: 3,
                fill: true,
                backgroundColor: 'rgba(128,0,0,0.5)',
                lineTension: 0,
                pointStyle: 'rect', //circle, cross, crossRot, dash, line, rect, rectRounded, rectRot, star, triangle
                pointRadius: 8,
            },
            {
                label: 'Youtube',
                data: [50, 100, 200, 400, 600],
                borderColor: 'green',
                borderWidth: 5,
                fill: true,
                backgroundColor: 'rgba(0,128,0,0.5)',
                pointStyle: 'triangle',
                pointRadius: 8,
            }
        ]
    };
...
</script>
~~~

## 课程文件

https://github.com/komavideo/LearnChartJS

## 小马视频频道

http://komavideo.com
