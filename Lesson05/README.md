设定坐标轴
==========

## 知识点

* options.yAxes

## 实战演习

~~~html
<script>
...
    var options = {
        scales: {
            yAxes: [{
                ticks: {
                    min: 0,
                    max: 2000,
                    // suggestedMin: 0,
                    // suggestedMax: 2000,
                    // stepSize: 400,
                    // callback: function (value, index, values) {
                    //     return value + '人';
                    // },
                }
            }]
        },
        title: {
            display: true,
            text: '小马视频',
            fontColor: 'green',
            fontSize: '24'
        }
    };
...
</script>
~~~

## 课程文件

https://github.com/komavideo/LearnChartJS

## 小马视频频道

http://komavideo.com
