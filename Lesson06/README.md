标题和图例
==========

## 知识点

* 设置图表的标题
* 设置图表的图例

## 实战演习

~~~html
<script>
...
    var options = {
        scales: {
            yAxes: [{
                ticks: {
                    min: 0,
                    max: 2000
                }
            }]
        },
        title: {
            display: true,
            text: '小马视频',
            fontColor: 'green',
            fontSize: '24',
            position: 'top', //top,left,bottom,right
        },
        legend: {
            position: 'right',
            diaplay: true
        },
        animation: {
            duration: 1000,
            easing: 'easeOutQuart', //easeOutQuart, easeInBounce, ...
        }
    };
...
</script>
~~~

## 课程文件

https://github.com/komavideo/LearnChartJS

## 小马视频频道

http://komavideo.com
