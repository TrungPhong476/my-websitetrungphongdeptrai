# my-websitetrungphongdeptrai
merry christmas
# MERRYCHRITMAS
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MERRY CHRISTMAS</title>
    <link rel="icon" href="./noel.jpg" type="image/x-icon">
    <link rel="stylesheet" href="styles.css">
</head>

<body >
    <audio id="audio" src="./giangsinh.mp3"></audio>

    <div id="as" class="christmas-message">Merry Christmas</div>
    <div class="tree-container">
        <img src="https://github.com/Panbap/datapanbap/blob/main/image/big_tree.png?raw=true" alt="Cây thông" class="tree-icon">
    </div>

    <div class="container">
        <button id="showButton">
            Thiệp nè
        </button>
    </div>

    <div id="guideInfo" class="hidden">
        <button id="closeButton" class="close-btn">X</button>
        <div id="ax" class="card">
            <div class="imgBox">
                <div class="bark"></div>
                <img
                    src="https://github.com/Panbap/datapanbap/blob/main/image/mery.png?raw=true">
            </div>
            <div class="details">
                <h4 class="color margin">MERRY CHRISTMAS</h4>
                <p>Giáng Sinh đến rồi.</p>
                <p>Chúc nàng mùa lễ ấm áp và ngọt</p>
                <p>ngào như chuyện tình ta sắp tới.</p>
                <p>Chúc nàng có mùa giáng sinh thật rực rỡ.</p>
                <p>Hy vọng chúng ta sẽ có thêm nhiều</p>
                <p>kỷ niệm đẹp trong năm tới.</p>
                <p class="text-right">Chúc mừng Giáng Sinh KimThuỳ!</p>
                <p class="text-right">♥♥</p>
            </div>
        </div>
    </div>
    <script src="script.js"></script>
    <script>
       document.body.addEventListener("click", function() {
            var audio = document.getElementById("audio");
            audio.play();
        });
    </script>

</body>

</html>

