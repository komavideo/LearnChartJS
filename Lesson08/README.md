棒棒图
=======

## 知识点

* 为您画一个棒图
* type=bar

## 实战演习

~~~html
<script>
...
    var type = 'bar'; //line, bar, horizontalBar,...
    var data = {
        labels: [2014, 2015, 2016, 2017, 2018],
        datasets: [
            {
                label: '优酷',
                data: [100, 150, 300, 800, 1600],
                backgroundColor: 'skyblue',
                borderColor: 'black',
                borderWidth: 8,
            },
            {
                label: 'Youtube',
                data: [50, 100, 200, 400, 600],
                //backgroundColor: 'red',
                backgroundColor: [
                    'red',
                    'orange',
                    'yellow',
                    'green',
                    'steelblue',
                ],
                borderColor: 'maroon',
                borderWidth: 8,
            }
        ]
    };

    var options = {
        scales: {
            xAxes: [{
                stacked: true
            }],
            yAxes: [{
                stacked: true
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
