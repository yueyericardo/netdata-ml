# netdata-ml
A simple dashboard of [netadata](https://github.com/netdata/netdata) for machine-learning people(include gpu and cpu)

![](https://yyrcd-1256568788.cos.na-siliconvalley.myqcloud.com/yyrcd/2019-08-13-162714.png)

### Usage
copy `ml.html` to `/opt/netdata/netdata-web-files/ml.html`  

### You need to 
1. change `data-gauge-max-value="24000"` at [line 77](https://github.com/yueyericardo/netdata-ml/blob/master/ml.html#L77) to your own RAM Memory in MB

2. change `data-gauge-max-value="6000"` at [line 83](https://github.com/yueyericardo/netdata-ml/blob/master/ml.html#L83) to your own GPU Memory in MB

Then, go to [localhost:19999/ml.html](http://localhost:19999/ml.html), you will see your dashboard!
