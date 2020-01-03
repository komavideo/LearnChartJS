线棒成一家
==========

## 知识点

* 混合线图和棒图，组成线棒图

## 实战演习

~~~html
<script>
...
    var type = 'bar';
    var data = {
        labels: [2014, 2015, 2016, 2017, 2018],
        datasets: [
            {
                label: '优酷',
                data: [100, 150, 300, 800, 1600],
                type: 'line',
                fill: false,
                yAxisID: 'youku-axes'
            },
            {
                label: 'Youtube',
                data: [50, 100, 200, 400, 600],
                type: 'bar',
                yAxisID: 'youtube-axes'
            }
        ]
    };

    var options = {
        scales: {
            yAxes: [
                {
                    id: 'youku-axes',
                    type: 'linear',
                    position: 'left',
                    ticks: {
                        min: 0,
                        max: 1800
                    }
                },
                {
                    id: 'youtube-axes',
                    type: 'linear',
                    position: 'right',
                    ticks: {
                        min: 0,
                        max: 800
                    },
                    gridLines: {
                        display: false
                    }
                }
            ]
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
