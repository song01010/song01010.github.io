
<!DOCTYPE html>

<html>

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">

    <title>图片上传</title>

    <link rel="stylesheet" href="index.css"/>

    <script type='text/javascript' src='index.js' charset='utf-8'></script>

</head>

<body>

<form id="mainForm">

    <div class="content">

        <div class="label">图片</div>

        <div class="img-area">

            <div class="container">

                <input type="file" id='id-face' name='face'  accept="image/*" />

                <div id='face-empty-result'>

                   <img style='width:4rem' src="www.taizisong.cn/image/camera.png?raw=true" alt="">


                    <p>第一张</p>

                </div>

                <img style='width: 100%' id='face-result'/>

            </div>

            <div class="container" style='margin-top:0.5rem;'>

                <input type="file" id='id-back' name='back' accept="image/*" />

                <div id='back-empty-result'>

                    <img style='width:4rem' src="www.taizisong.cn/image/camera.png?raw=true" alt="">

                    <p>第二张</p>

                </div>

                <img style='width: 100%' id='back-result'/>

            </div>

        </div>

    </div>

    <div class="btn">

        提交

    </div>

</form>
</body>
</html>
