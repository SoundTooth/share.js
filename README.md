# share.js

 *                            +-+ +-+ +-+ +-+ +-+
 *                            |#| |#| |#| +-+ |#|
 *                            |#| |#| |#|     +-+
 *                            +-+ |#| |#|
 *                                +-+ |#|
 *                                    |#| +-+
 *                                    +-+ |#|
 *                                        |#| +-+
 *                            +-+     +-+ |#| |#|
 *                            |#| +-+ |#| |#| |#|
 *                            +-+ +-+ +-+ +-+ +-+
 *       ____                           _  _                  _    _
 *      /  __\ _____ __   _ __ ___  ___| || |_  _____  _____ | |_ / \
 *      | |__ /  _  \\ \ | |\ '_  \/  _  ||  _|/  _  \/  _  \|  _|| |___
 *      \__  \| |_| || |_| || | | || |_| || |__| |_| || |_| || |__|  _  |
 *      |____/\_____/|_____||_| |_|\_____|\___/\_____/\_____/\___/|_| |_|
 *
 *      ================================================================
 *           Copyright ® 2015-2015 Soundtooth.All Rights Reserved.
 *      ================================================================

## Description
- summary: A library of javasciprt to integrate(整合) different share components of popular social platforms into one, with different APIs provided by them.
- support: qq, qzone, weibo, tieba, tencent weibo, renren
- license: MIT

<br />
<br />

## How to use? 

#### 1. Import the Javascript Files

```html
<script type="text/javascript" src="./src/jquery-2.1.4.min.js"></script>
<script type="text/javascript" src="./src/share.min.js"></script>
```

#### 2. Initialize share components

##### qq

```js
/**
 * @param {[type]} $('#share-qq')	[which is an object you want to bind this event]
 */
share.initTencent('qq', $('#share-qq'), title, image); 
```

##### qzone

```js
/**
 * @param {[type]} $('#share-qzone')	[which is an object you want to bind this event]
 */
share.initTencent('qzone', $('#share-qzone'), title, image);
```

##### weibo

```js
/**
 * @param {[type]} appkey	[which you should apply for your website in http://open.weibo.com/connect]
 * @param {[type]} $('#share-weibo')	[which is an object you want to bind this event]
 */
share.initWeibo(appkey, $('#share-weibo'), title, image);
```

##### tieba

```js
/**
 * @param {[type]} $('#share-tieba')	[which is an object you want to bind this event]
 */
share.initTieba($('#share-tieba'), title, image); 
```

##### tencent weibo

```js
/**
 * @param {[type]} appkey	[which you should apply for your website in http://open.weibo.com/connect]
 * @param {[type]} $('#share-tencentweibo')	[which is an object you want to bind this event]
 */
share.initTencentWeibo(appkey, $('#share-tencentweibo'), title, image);
```

## Demo

- click [**here**](http://aleen42.github.io/example/share.js/sample.html) to see.

## Download

- click [**here**](https://raw.githubusercontent.com/SoundTooth/share.js/master/src/share.min.js) to download the src javascript file.

