## 期末项目设计

[ppt链接：](https://gitee.com/NFUNM079/audio)
价值主张：满足你所有对艺术展览服务要求的想象
使用户能够更快的找到感兴趣的艺术馆/展览、并兼具打卡、购票、攻略为一体、致力于给用户更好的艺术馆信息服务最好的体验。

发布名称|发布时间|发布人
---|:--:|---:
馆藏——艺术馆信息打卡app|2019.12.2|吴惠怡
<br> 

 #### 

 #### 第一部分
<br> 
##### 一、价值设计 
**市场调查**：市面上存在的博物馆app大都是为两种类型：一类是信息整合类，收集整理所有的展览信息如VART，另一类是艺术馆内展品的展览，如故宫app每日故宫。功能较单一，app使用率较低。随着大众对精神生活的要求提高，大家需要各种展览包括博物馆美术馆的信息，而对应功能的app则稍显枯燥与功能单一。我希望能在提供信息的基础上做出一些趣味的社区交流与互动，增加对展览的兴趣。所以喜欢做出一个结合了艺术馆打卡与信息查询的app。
<br>
**目前我的设想是**：
1.调用地图api，在地图上标注包括博物馆，美术馆在内的艺术馆的位置。并且显示近期展览信息。
2.开启定位服务，用户可以选择根据自身位置选择最近的艺术馆，或是从感兴趣的展览页面查看定位与艺术馆的距离信息。
3.调用百度图像风格转换api，让参观者可以选择公开或者私人观看自己转换风格后的照片进行定位打卡，让参观者可以大概了解展览的内容但又较小程度的透露展品信息。
##### 二、价值主张/最小可行性产品
一个可以查询展览信息并且可以上传风格化照片打卡的app

##### 三、背景
市面上无相关综合类的产品，而相关资讯的作品已经很多，需要一个改善的，有创意的app来满足人们对此类app要求更高的需求。

##### 四、目的
一个更综合，交互性更强的艺术馆展览信息查询app

##### 五、目标
**前期目标：**
1.调用百度地图api，标注地图上的艺术馆信息。
2.调用百度智能定位与凸显规划api，显示位置信息（包括1.以距离条件查看艺术馆信息2.从展览页面查看距离信息）
3.调用百度图像风格转换api，上传转换风格后的照片打卡

**后期目标（加值）：**
1.可以给展览/艺术馆评分或是评论留言，形成推荐机制，促进艺术馆/展览改进服务的同时形成社区文化。此服务需付费购买。
##### 六、用户
1.文艺青年 2.对展览有兴趣的人 3.希望了解各类艺术馆的人

##### 八、1.用户需求
用户案例|对应标题|重要程度
---|:--:|---:
1.用户想要知道最近有什么展览，最近的艺术馆在那|定位查询|重要:
2用户想要知道离自己某个艺术馆怎么去|路程推荐|重要:
3.用户想在艺术馆打卡，留念|拍照打卡|重要:
4.用户想要知道某个艺术馆的评价或是攻略|用户想法|次重要:


2.具体场景分析
1.周末到了，无聊的小do想要去逛逛艺术馆，但不知道附近有多少艺术馆，分别是什么，更不知道有馆内是否有感兴趣的展览。
2.1想要看展览/逛艺术馆的小re想打发时间但是不想去太远，他想去离家里最近的艺术馆。
2.2.小me了解到某地有一个感兴趣的展览，但不知道怎么过去比较方便。
3.小la到了喜欢的艺术馆，想打卡，留作纪念。形成自己的艺术馆打卡记录。
4.小fa觉得某个艺术馆服务太差，可以改善的地方有许多，他想要让艺术馆及感兴趣的参观者知道相关信息。

#### 第二部分：
##### 一、原型文档交互

[原型链接](http://nfunm079.gitee.io/art_gallery)
![首页](https://upload-images.jianshu.io/upload_images/9540329-0631b8a53e202165.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![艺术馆](https://upload-images.jianshu.io/upload_images/9540329-b13a3972bcdcb305.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![附近](https://upload-images.jianshu.io/upload_images/9540329-546c9472eb072f29.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![动态](https://upload-images.jianshu.io/upload_images/9540329-7f176847b9d17373.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![拍照打卡](https://upload-images.jianshu.io/upload_images/9540329-b994b4dfbc389a8b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![展览详情](https://upload-images.jianshu.io/upload_images/9540329-dce29db5c4a8f2ed.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![路程推荐](https://upload-images.jianshu.io/upload_images/9540329-d64d325bad573c9d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

页面均可在原型链接中查看 不再赘述
##### 二、产品结构图
1.产品功能结构图
![馆藏app产品结构图 .png](https://upload-images.jianshu.io/upload_images/9540329-8e8e7f865248a8de.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2.产品信息结构图
![馆藏app信息结构图.png](https://upload-images.jianshu.io/upload_images/9540329-1e04614fafdebd55.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 产品流程图
![产品流程图](https://upload-images.jianshu.io/upload_images/9540329-5cfb854b47055eec.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


4.产品结构图
![馆藏app产品结构图 (2).png](https://upload-images.jianshu.io/upload_images/9540329-e1e58a5635904c2c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 第三部分
##### 一、API的调用
1.路线规划调用
 高德API：
调用：https://restapi.amap.com/v3/direction/drivingorigin=116.45925,39.910031&destination=116.587922,40.081577&output=xml&key=<用户的key>
```代码示例：
import requests

def get_access_token():
     APP_ID = 'xxx'
     API_KEY = 'xxx'
     SECRET_KEY = 'xxx'
key = '6394bd7f35502892ef1927d589903820'
def api(origin,destination):
    url = 'https://restapi.amap.com/v3/direction/walking?parameters'
    params ={
            'key':key,
            'origin':origin,
            'destination':destination
    }        
    response = requests.get(url,params=params)
    data = response.json()
    return data

api("116.481028,39.989643","116.434446,39.90816")     

```
* 输出
```
{'status': '1',
 'info': 'ok',
 'infocode': '10000',
 'count': '1',
 'route': {'origin': '116.481028,39.989643',
  'destination': '116.434446,39.90816',
  'paths': [{'distance': '11222',
    'duration': '8978',
    'steps': [{'instruction': '步行73米向左前方行走',
      'orientation': [],
      'road': [],
      'distance': '73',
      'duration': '58',
      'polyline': '116.480595,39.989705;116.480438,39.989809;116.480438,39.989809;116.480265,39.989905;116.480217,39.989913;116.479844,39.989818',
      'action': '向左前方行走',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '沿阜通东大街向西南步行10米向左前方行走',
      'orientation': '西南',
      'road': '阜通东大街',
      'distance': '10',
      'duration': '8',
      'polyline': '116.479839,39.989813;116.479753,39.989748',
      'action': '向左前方行走',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '沿阜通东大街向西南步行1714米直行',
      'orientation': '西南',
      'road': '阜通东大街',
      'distance': '1714',
      'duration': '1371',
      'polyline': '116.479748,39.989744;116.479714,39.989544;116.478976,39.988889;116.478976,39.988889;116.47855,39.988559;116.47855,39.988559;116.478433,39.988455;116.478433,39.988455;116.478168,39.988203;116.478168,39.988203;116.477817,39.987873;116.477817,39.987873;116.477604,39.987704;116.477604,39.987704;116.47645,39.986879;116.47645,39.986879;116.476137,39.986654;116.476137,39.986654;116.475451,39.986168;116.475451,39.986168;116.475304,39.986059;116.475304,39.986059;116.47513,39.985933;116.47513,39.985933;116.474514,39.985482;116.474206,39.985226;116.474206,39.985226;116.473229,39.984349;116.473229,39.984349;116.472656,39.983837;116.472656,39.983837;116.472582,39.983763;116.472582,39.983763;116.471528,39.982817;116.471528,39.982817;116.470569,39.981953;116.470569,39.981953;116.470499,39.981888;116.470499,39.981888;116.47043,39.981827;116.47043,39.981827;116.470109,39.981541;116.470109,39.981541;116.469349,39.980851;116.469349,39.980851;116.468746,39.980304;116.468746,39.980304;116.468142,39.979766;116.468142,39.979766;116.467921,39.979566;116.46776,39.979518;116.46776,39.979518;116.466363,39.978216',
      'action': '直行',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '沿曙光西路向西南步行2363米直行',
      'orientation': '西南',
      'road': '曙光西路',
      'distance': '2363',
      'duration': '1890',
      'polyline': '116.466359,39.978212;116.464388,39.976424;116.463633,39.975764;116.463433,39.975608;116.463433,39.975608;116.463381,39.975564;116.463381,39.975564;116.463077,39.975339;116.463077,39.975339;116.462878,39.9752;116.462878,39.9752;116.462405,39.974896;116.4602,39.973585;116.4599,39.973385;116.4599,39.973385;116.456536,39.971359;116.456311,39.971207;116.456011,39.970985;116.456011,39.970985;116.455933,39.970916;116.455933,39.970916;116.454622,39.969757;116.454622,39.969757;116.454262,39.969436;116.454262,39.969436;116.453316,39.968563;116.453316,39.968563;116.453264,39.968511;116.453264,39.968511;116.45319,39.968446;116.45319,39.968446;116.452326,39.967682;116.452326,39.967682;116.452075,39.967461;116.452075,39.967461;116.451806,39.967222;116.451806,39.967222;116.451549,39.966984;116.451549,39.966984;116.451302,39.966762;116.451302,39.966762;116.451259,39.966723;116.451259,39.966723;116.45092,39.966419;116.45092,39.966419;116.449731,39.965347;116.449731,39.965347;116.449036,39.964718;116.449036,39.964718;116.448893,39.964583;116.448893,39.964583;116.448872,39.964562;116.448872,39.964562;116.44862,39.96434;116.44862,39.96434;116.448563,39.964288;116.448563,39.964288;116.44806,39.963828;116.44806,39.963828;116.447869,39.963641;116.447869,39.963641;116.447114,39.962964;116.447114,39.962964;116.447053,39.962917',
      'action': '直行',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '沿静安西街向西南步行39米左转',
      'orientation': '西南',
      'road': '静安西街',
      'distance': '39',
      'duration': '31',
      'polyline': '116.447049,39.962912;116.446797,39.962695;116.446797,39.962695;116.44674,39.962648',
      'action': '左转',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '沿北三环东路辅路向东南步行367米右转',
      'orientation': '东南',
      'road': '北三环东路辅路',
      'distance': '367',
      'duration': '294',
      'polyline': '116.446736,39.962643;116.446806,39.9626;116.446806,39.9626;116.446884,39.962548;116.446884,39.962548;116.447279,39.962296;116.447279,39.962296;116.447509,39.96214;116.447509,39.96214;116.447873,39.961901;116.447873,39.961901;116.448147,39.961727;116.448147,39.961727;116.448398,39.961567;116.448398,39.961567;116.448746,39.961328;116.448746,39.961328;116.449093,39.961081;116.449093,39.961081;116.449774,39.960621;116.449774,39.960621;116.449826,39.96059;116.449826,39.96059;116.450035,39.960447',
      'action': '右转',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '沿静安东街向西南步行507米直行',
      'orientation': '西南',
      'road': '静安东街',
      'distance': '507',
      'duration': '406',
      'polyline': '116.450035,39.960443;116.449922,39.960352;116.449922,39.960352;116.449779,39.960217;116.449779,39.960217;116.44967,39.960104;116.44967,39.960104;116.44964,39.960056;116.449505,39.959922;116.449505,39.959922;116.449128,39.959579;116.449128,39.959579;116.448967,39.95944;116.448967,39.95944;116.448906,39.959379;116.448906,39.959379;116.448733,39.959219;116.448733,39.959219;116.448329,39.958859;116.448329,39.958859;116.447839,39.958403;116.447839,39.958403;116.447595,39.958194;116.447595,39.958194;116.447253,39.957895;116.447253,39.957895;116.446849,39.957504;116.446849,39.957504;116.446168,39.956905',
      'action': '直行',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '沿左家庄北斜街向西南步行240米左转',
      'orientation': '西南',
      'road': '左家庄北斜街',
      'distance': '240',
      'duration': '192',
      'polyline': '116.446163,39.956901;116.446124,39.956858;116.446085,39.956845;116.446085,39.956845;116.445551,39.956341;116.445551,39.956341;116.445399,39.956207;116.445399,39.956207;116.445078,39.955929;116.445078,39.955929;116.444948,39.955807;116.444948,39.955807;116.444766,39.955651;116.444766,39.955651;116.444484,39.955464;116.444484,39.955464;116.444332,39.955365;116.444332,39.955365;116.444232,39.955308',
      'action': '左转',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '沿左家庄南斜街向南步行413米右转',
      'orientation': '南',
      'road': '左家庄南斜街',
      'distance': '413',
      'duration': '330',
      'polyline': '116.444227,39.955304;116.444297,39.954818;116.444297,39.954818;116.444319,39.954644;116.444319,39.954644;116.444371,39.954227;116.444371,39.954227;116.444388,39.954119;116.444388,39.954119;116.444462,39.953633;116.444462,39.953633;116.444479,39.953533;116.444479,39.953533;116.444492,39.953394;116.444492,39.953394;116.444562,39.952869;116.444562,39.952869;116.444622,39.952413;116.444622,39.952413;116.444709,39.951901;116.444709,39.951901;116.444744,39.95168;116.444744,39.95168;116.444774,39.951563',
      'action': '右转',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '沿香河园路向西南步行981米右转',
      'orientation': '西南',
      'road': '香河园路',
      'distance': '981',
      'duration': '785',
      'polyline': '116.444774,39.951558;116.444141,39.951128;116.444141,39.951128;116.442569,39.949974;116.442569,39.949974;116.442352,39.949818;116.442352,39.949818;116.442201,39.949701;116.442201,39.949701;116.441211,39.948967;116.441211,39.948967;116.44112,39.948898;116.44112,39.948898;116.440495,39.948372;116.440495,39.948372;116.439944,39.947917;116.439944,39.947917;116.439349,39.947396;116.438989,39.947049;116.438989,39.947049;116.438898,39.946953;116.438898,39.946953;116.438576,39.946584;116.438576,39.946584;116.438464,39.946441;116.438464,39.946441;116.438294,39.946254;116.438294,39.946254;116.438212,39.946159;116.438212,39.946159;116.437921,39.945781;116.437921,39.945781;116.437817,39.945629;116.437817,39.945629;116.437344,39.944891;116.437344,39.944891;116.437326,39.944844',
      'action': '右转',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '沿香河园路向西步行282米左转',
      'orientation': '西',
      'road': '香河园路',
      'distance': '282',
      'duration': '226',
      'polyline': '116.437322,39.944839;116.434961,39.944839;116.434961,39.944839;116.434831,39.944839;116.434831,39.944839;116.434557,39.944839;116.434557,39.944839;116.434444,39.944839;116.434444,39.944839;116.434006,39.944835',
      'action': '左转',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '向南步行63米向右前方行走',
      'orientation': '南',
      'road': [],
      'distance': '63',
      'duration': '50',
      'polyline': '116.434002,39.944831;116.434058,39.94477;116.434054,39.944431;116.434054,39.944431;116.434045,39.944271',
      'action': '向右前方行走',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '步行98米右转',
      'orientation': [],
      'road': [],
      'distance': '98',
      'duration': '78',
      'polyline': '116.434041,39.944266;116.434006,39.944167;116.434006,39.944167;116.433932,39.944167;116.433932,39.944167;116.43355,39.944171;116.43355,39.944171;116.43339,39.944175;116.43339,39.944175;116.43339,39.943898;116.43339,39.943898;116.433464,39.943898',
      'action': '右转',
      'assistant_action': [],
      'walk_type': '4'},
     {'instruction': '沿东直门北大街向南步行310米直行',
      'orientation': '南',
      'road': '东直门北大街',
      'distance': '310',
      'duration': '248',
      'polyline': '116.433464,39.943893;116.433485,39.94332;116.433485,39.94332;116.433516,39.942665;116.433516,39.942665;116.433559,39.941667;116.433559,39.941667;116.433585,39.941089',
      'action': '直行',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '沿东直门南大街向南步行741米',
      'orientation': '南',
      'road': '东直门南大街',
      'distance': '741',
      'duration': '593',
      'polyline': '116.433585,39.941085;116.433615,39.940486;116.433615,39.940486;116.433655,39.939614;116.433655,39.939614;116.433655,39.938828;116.433655,39.938828;116.433685,39.938164;116.433685,39.938164;116.433707,39.93783;116.433707,39.93783;116.433707,39.937457;116.433707,39.937457;116.43372,39.937161;116.43372,39.937161;116.433746,39.93671;116.433746,39.93671;116.433759,39.936324;116.433759,39.936324;116.433767,39.936133;116.433767,39.936133;116.433806,39.935677;116.433806,39.935677;116.433837,39.935122;116.433837,39.935122;116.433867,39.934366;116.433867,39.934366;116.433867,39.934353',
      'action': [],
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '沿东直门南大街向南步行321米直行',
      'orientation': '南',
      'road': '东直门南大街',
      'distance': '321',
      'duration': '257',
      'polyline': '116.433867,39.934349;116.433928,39.933125;116.433928,39.933125;116.433928,39.933112;116.433928,39.933112;116.433958,39.932227;116.433958,39.932227;116.433971,39.931771;116.433932,39.931454',
      'action': '直行',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '沿朝阳门北大街向南步行517米向右前方行走',
      'orientation': '南',
      'road': '朝阳门北大街',
      'distance': '517',
      'duration': '414',
      'polyline': '116.433928,39.93145;116.433958,39.931107;116.433958,39.931107;116.433958,39.931063;116.433958,39.931063;116.433967,39.930846;116.433967,39.930846;116.433967,39.930786;116.433967,39.930786;116.433971,39.93066;116.433971,39.93066;116.433997,39.930226;116.433997,39.930226;116.434032,39.929553;116.434032,39.929553;116.434032,39.929497;116.434032,39.929497;116.43408,39.928555;116.43408,39.928555;116.434089,39.928294;116.434089,39.928294;116.434119,39.927539;116.434119,39.927539;116.434158,39.926749',
      'action': '向右前方行走',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '沿朝阳门桥步行231米左转',
      'orientation': [],
      'road': '朝阳门桥',
      'distance': '231',
      'duration': '185',
      'polyline': '116.434158,39.926745;116.434093,39.926502;116.434036,39.926224;116.434036,39.926037;116.43408,39.92559;116.43408,39.92559;116.43408,39.925516;116.43408,39.925516;116.434097,39.925061;116.434093,39.924753;116.434093,39.924753;116.434193,39.924761',
      'action': '左转',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '步行36米右转',
      'orientation': [],
      'road': [],
      'distance': '36',
      'duration': '29',
      'polyline': '116.434193,39.924761;116.434193,39.925017;116.434284,39.925017',
      'action': '右转',
      'assistant_action': [],
      'walk_type': '20'},
     {'instruction': '沿朝阳门北大街向南步行295米直行',
      'orientation': '南',
      'road': '朝阳门北大街',
      'distance': '295',
      'duration': '236',
      'polyline': '116.434284,39.925017;116.434323,39.92388;116.434323,39.92388;116.434353,39.923273;116.434362,39.922578;116.434362,39.922578;116.434371,39.922348',
      'action': '直行',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '沿朝阳门南大街向南步行726米直行',
      'orientation': '南',
      'road': '朝阳门南大街',
      'distance': '726',
      'duration': '581',
      'polyline': '116.434371,39.922344;116.434366,39.922001;116.434366,39.922001;116.434379,39.921563;116.434379,39.921563;116.434379,39.921519;116.434379,39.921519;116.434401,39.921094;116.434401,39.921094;116.434414,39.920677;116.434414,39.920677;116.434431,39.920304;116.434431,39.920304;116.434444,39.920052;116.434444,39.920052;116.43447,39.919544;116.43447,39.919544;116.434475,39.919453;116.434475,39.919453;116.434505,39.918633;116.434505,39.918633;116.434523,39.918451;116.434523,39.918451;116.434536,39.917982;116.434536,39.917982;116.434562,39.917244;116.434562,39.917244;116.434601,39.916497;116.434601,39.916497;116.434622,39.916063;116.434622,39.916063;116.434631,39.915764;116.434631,39.915764;116.434635,39.915703',
      'action': '直行',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '沿建国门北大街向南步行818米直行',
      'orientation': '南',
      'road': '建国门北大街',
      'distance': '818',
      'duration': '654',
      'polyline': '116.434635,39.915699;116.434644,39.91556;116.434644,39.91556;116.434644,39.915417;116.434644,39.915417;116.434661,39.915065;116.434661,39.915065;116.434661,39.914952;116.434661,39.914952;116.434696,39.914284;116.434696,39.914284;116.434757,39.913555;116.434757,39.913555;116.434757,39.91349;116.434757,39.91349;116.434774,39.913177;116.434774,39.913177;116.434787,39.913025;116.434787,39.913025;116.434796,39.912839;116.434796,39.912839;116.434822,39.912274;116.434822,39.912274;116.434822,39.912248;116.434822,39.912248;116.434852,39.911784;116.434852,39.911784;116.434874,39.91122;116.434874,39.91122;116.434918,39.910109;116.434918,39.910109;116.434965,39.909054;116.434965,39.909054;116.434931,39.908932;116.434887,39.908867;116.434887,39.908867;116.434818,39.908655;116.434826,39.908424;116.434883,39.908303',
      'action': '直行',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '沿建国门南大街向东南步行29米右转',
      'orientation': '东南',
      'road': '建国门南大街',
      'distance': '29',
      'duration': '23',
      'polyline': '116.434883,39.908299;116.434974,39.908194;116.435009,39.908077',
      'action': '右转',
      'assistant_action': [],
      'walk_type': '0'},
     {'instruction': '步行48米到达目的地',
      'orientation': [],
      'road': [],
      'distance': '48',
      'duration': '38',
      'polyline': '116.435009,39.908073;116.434449,39.908073',
      'action': [],
      'assistant_action': '到达目的地',
      'walk_type': '0'}]}]}}
```
2.百度api
调用方式：http://api.map.baidu.com/direction/v2/transitorigin=40.056878,116.30815&destination=31.222965,121.505821&ak=您的AK  //GET请求
```代码示例：

```
* 输出
```

```

2.照片风格化api

HTTP 方法：POST
请求URL： https://aip.baidubce.com/rest/2.0/image-process/v1/style_trans
```代码示例：
 public static string styleTrans(String imagefilename,String resultfilename,String option)

        {

            string token = AccessToken.getAccessToken();

            Console.WriteLine(token);

            string host = "[https://aip.baidubce.com/rest/2.0/image-process/v1/style_trans?access_token=](https://aip.baidubce.com/rest/2.0/image-process/v1/style_trans?access_token=)" + token;

            Encoding encoding = Encoding.Default;

            HttpWebRequest request = (HttpWebRequest)WebRequest.Create(host);

            request.Method = "post";

            request.KeepAlive = true;

            // 图片的base64编码

            string base64 = getFileBase64(imagefilename);

            String str = "image=" + HttpUtility.UrlEncode(base64)+"&option="+option;

            byte[] buffer = encoding.GetBytes(str);

            request.ContentLength = buffer.Length;

            request.GetRequestStream().Write(buffer, 0, buffer.Length);

            HttpWebResponse response = (HttpWebResponse)request.GetResponse();

            StreamReader reader = new StreamReader(response.GetResponseStream(), Encoding.Default);

            string result = reader.ReadToEnd();

            Console.WriteLine("拉伸图像恢复:");

            Console.WriteLine(result);

            JObject jo = (JObject)JsonConvert.DeserializeObject(result);

            String imageBase64 = jo["image"].ToString();

            saveBase64File(imageBase64, resultfilename);

            Console.WriteLine("成功");

            return result;

        }

        public static String getFileBase64(String fileName) {

            FileStream filestream = new FileStream(fileName, [FileMode.Open](http://filemode.open/));

            byte[] arr = new byte[filestream.Length];

            [filestream.Read](http://filestream.read/)(arr, 0, (int)filestream.Length);

            string baser64 = Convert.ToBase64String(arr);

            filestream.Close();

            return baser64;

        }

        public static String saveBase64File(string base64Str, string outPath)

        {

            var contents = Convert.FromBase64String(base64Str);

            using (var fs = new FileStream(outPath, FileMode.Create, FileAccess.Write))

            {

                fs.Write(contents, 0, contents.Length);

                fs.Flush();

            }

            return "finished";

        }

```
* 输出

![8C8785F0541242ABA9386DE54E125DEE.jpg](https://upload-images.jianshu.io/upload_images/9540329-f1b3a80d46d81bb3.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![5A9CBC02D0D946B197541C9A586F5963.jpg](https://upload-images.jianshu.io/upload_images/9540329-26e6156e50a50cde.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

##### 二、API产品概率性
一.高德api的导航与定位服务宣称有着3个优点：
* 超高的服务可用性，持续稳定支持您的业务发展
* 快速的服务响应，服务请求到达高德至完成处理的平均时长不超过200ms
* 全方位的技术支持 工单体系提供全方位的技术支持，更有技术支持专业版可供选择

二、高德路线规划基于全面的路网信息，结合实时路况，有在多端为用户提供准确的路线规划能力。

三.百度旗下的图像风格转变api对于转换图片是有着一定能力的，加上图片转换这个任务的特殊性，极少有出错的可能，更多的情况可能是图片不够美观。

##### 三、与其他产品的比较
* 与百度地图相比，高德地图道路更新上非常及时，拥有更完整的地图：涵盖了全国364个城市的352万公里的路况，且可以通过AR虚拟实景为用户实时导航。[高德与百度性能比较相关文章链接](https://baijiahao.baidu.com/s?id=1620901671158752564&wfr=spider&for=pc)
 * 高德地图定在GPS 10米精度做到90%以上，且可以离线导航。而百度地图定位较慢。
* 目前了解到的国内可以进行图像风格转换的只有百度。

##### 四、API使用风险评估
路线规划与定位等api可谓最早发展的api，完善程度较高，出错率较小。[定位未来发展性相关文章链接](https://segmentfault.com/a/1190000020775948?utm_source=tag-newest)
图像风格转换因其特性出错率较低

##### 五、产品的可行性
1.该产品一定程度上解决了用户需要查询艺术馆及展览信息的需求
2.有小众的艺术馆/展览爱好者的潜在用户
3.有成为社区，形成庞大ucg内容的可能

##### 六、交互需求
输入框：若输入框有默认提示，点击输入框，自动弹出软键盘进行输入
软键盘的弹出及退出机制：当输入框内必须输入的为数字时，弹出数字软键盘，其余时候，弹出文字软键盘；当在软键盘以外区域，点击或向下滑动时，软键盘退去。
##### 七、异常流
1.如果没办法定位正确，建议用户走到较为地标性的建筑附近进行打卡，或是手动输入地点进行定位。
2.路径规划错误时，让用户及时反馈说明。
3.如果照片拍摄时没办法转换到喜欢的照片具体样子，可以建议用户再次拍照，或者转换风格。

##### 八、结果预期
前期可能是个人化的app，供用户查看展览/艺术馆信息及完成打卡。后期可能发展为小众的艺术馆交流社区，不断地产出出行攻略及推荐等，形成此类产品较有公信力的一个社群。

#### 第四部分：清单
1.原型
* 产品原型图链接：http://nfunm079.gitee.io/art_gallery
* 原型链接:https://gitee.com/NFUNM079/art_gallery

2.调用api的链接:

* .路线规划：[https://lbs.amap.com/getting-started/path](https://lbs.amap.com/getting-started/path)

* .图片风格化：[https://ai.baidu.com/tech/imageprocess/style_trans](https://ai.baidu.com/tech/imageprocess/style_trans)

* .地图定位：[https://lbs.amap.com/getting-started/locate](https://lbs.amap.com/getting-started/locate)

