雷达图
======

## 知识点

* 制作雷达图
* type=radar

## 实战演习

~~~html
<script>
...
    var type = 'radar';
    var data = {
        labels: ['伤害', '辅助', '存活', '上手', '价格'],
        datasets: [
            {
                label: '泽拉图',
                data: [70, 60, 50, 50, 70],
                backgroundColor: 'rgba(0, 255, 128, 0.5)',
            },
            {
                label: '雷诺',
                data: [90, 10, 40, 70, 20],
                backgroundColor: 'rgba(0, 0, 0, 0.5)',
            }
        ]
    };

    var options = {
        scale: {
            ticks: {
                suggestedMin: 0,
                suggestedMax: 100,
                stepSize: 20,
            }
        },
        title: {
            display: true,
            text: '风暴英雄',
            fontColor: 'indigo',
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
