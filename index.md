<style>
    #forkme_banner {
        display: none;
    }

    header.inner {
        max-width: 960px;
        text-align: center;
    }

    #project_tagline {
        font-size: 32px;
        text-align: center;
    }

    .inner {
        max-width: 720px;
    }

    .yt-wrapper {
        position: relative;
        width: 100%;
    }
    .yt-wrapper:before {
        content: "";
        display: block;
        padding-top: 56.25%;
    }
    .yt-wrapper iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }

    div, img {
        box-sizing: border-box;
        max-width: 100%;
    }

    h2 {
        padding-top: 1em;
    }

    h1, h2, h3 {
        text-align: center;
    }
</style>

<script>
window.addEventListener('DOMContentLoaded', function(){
    var link = document.createElement('link');
    link.type = 'image/x-icon';
    link.rel = 'shortcut icon';
    link.href = "/Final-Movie/favicon.ico"
    document.getElementsByTagName('head')[0].appendChild(link)

    var title = 'ビーコンIoTで函館のまちをハックする';
    var subTitle = 'Beacon FUN 4';
    document.title = subTitle;
    document.getElementById('forkme_banner').remove();
    document.getElementById('project_title').innerHTML = title;
    document.getElementById('project_tagline').innerHTML = subTitle;
    document.getElementById('no_js_h1').style.display = 'none';
    document.getElementById('no_js_h3').style.display = 'none';
});
</script>

<h1 id="no_js_h1">ビーコンIoTで函館のまちをハックする</h1>
<h3 id="no_js_h3">Beacon FUN 4</h3>

## 紹介動画

<div class="yt-wrapper">
    <iframe src="https://youtu.be/sS01Z8hYL7U" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<a href="https://twitter.com/share" class="twitter-share-button" data-hashtags="BF4最終発表,未来大プロジェクト学習" data-count="none" data-lang="ja" data-url="https://beaconfun4.github.io/Final-Movie/" data-text="ビーコンIoTで函館のまちをハックする - Beacon FUN 4  成果発表会">ツイート</a>
<script type="text/javascript" src="https://platform.twitter.com/widgets.js"></script>


## 目的

ビーコンを函館のまちの様々な場所に設置し、ビーコンを活用したサービスを開発する。それによって、新たな価値を生み出し、利用者にこれまでにない体験や魅力を提供することが目的である。
> The purpose is to create new value and provide people unique experiences and attractions. We Install beacons in Hakodate real downtown, and develop services that utilize beacons. 

## ビーコンの特徴

- スマートフォンで受信可能なBluetoothで通信を行う小さなデバイス
> Beacon is a small device that communicate via Bluetooth which can be received by smartphones

- バッテリー消費の少ないBLE (Bluetooth Low Energy) を採用
> The devices uses BLE (Bluetooth Low Energy) which is low battery consumption

- ビーコンから受信端末までの距離の計測、個体の識別が可能
> The device is able to measure distance between it and the receiver, identify individual devices

## 活動内容
<div align="center">
  <a href="https://beaconfun4.github.io/Final-Movie/image/activities.png" target="_blank">
    <img src="image/activities.png" alt="Activities" widht="100%" />
  </a>
</div>

## サービス

<div align="center">
  <a href="https://beaconfun4.github.io/Final-Movie/image/service.png" target="_blank">
    <img src="image/service.png" alt="Services" style="width: 80%;"/>
  </a>
</div>
