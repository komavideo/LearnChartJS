圆饼图
======

## 知识点

* 制作大饼图
* type=pie

## 实战演习

~~~html
<script>
...
    var type = 'pie'; //pie, doughnut
    var data = {
        labels: ['泽拉图', '雷诺', '小鹿'],
        datasets: [
            {
                data: [70, 40, 55],
                backgroundColor: ['green', 'gray', 'pink']
            }
        ]
    };
    var options = {
        title: {
            display: true,
            text: '风暴英雄',
            fontColor: 'indigo',
            fontSize: '24'
        },
        // cutoutPercentage: 20,
    };
...
</script>
~~~

## 课程文件

https://github.com/komavideo/LearnChartJS

## 小马视频频道

http://komavideo.com
