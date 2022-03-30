# robot_vision_reference

# ロボットのための３次元物体認識研究の現状と展望
 中京⼤学 ⼯学部
橋本 学

http://isl.sist.chukyo-u.ac.jp/wp-content/uploads/2019/05/RSJ-119thSeminar-slides.pdf

# shot特徴量で物体認識

https://qiita.com/hakuturu583/items/3e82acb083779f388640

# オクルージョンのある物体認識　解説

特徴量マッチングで認識する

https://www.google.co.jp/amp/s/slidesplayer.net/amp/16201704/

# クラスタリング
## ユークリッドクラスタリング
- pcl ros で試す　https://lilaboc.work/archives/20136695.html

- 3d lidar 遠くの点群が疎になるので、遠くの点群のユークリッドトレランスを距離で変える　https://lilaboc.work/archives/20178032.html

- 法線群のクラスタリング

https://lilaboc.work/archives/20163899.html


- 岩石点群クラスタリング

http://www.kameda-lab.org/research/publication/2018/201803_IPSJ/201803_IPSJ_ZhaW.pdf

# ROS関係

python点群処理

https://qiita.com/np_hsgw/items/d45ad46286abb7ac2e5c

実行時以下のようなエラーがでた.

```
Traceback (most recent call last):
  File "cropper.py", line 10, in <module>
    import tf2_sensor_msgs.tf2_sensor_msgs
ModuleNotFoundError: No module named 'tf2_sensor_msgs'
```

解決方法  https://answers.ros.org/question/12890/transforming-pointcloud2/

```
sudo apt install ros-noetic-tf2-sensor-msgs
```

# 論文

- RANSAM for Industrial Bin-Picking (2010)

RANSAMアルゴリズムがばら積みピッキング作業で非常に有効であることが,検証された。
