<!DOCTYPE html>
<html lang="vi">

<head>
    <meta charset="UTF-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1"/>
    <style>
        :root {
            --color-background: #dbedf1;
            --color-blue-text: #0333d3;
            --color-red-text: #ff0040;
            --color-text: #1d1d1d;
            --color-green-line: #3eb63c;
            --color-blue-line: #3da0b4;
            --color-button: #1365f4;
            --color-button-hover: #186dff;
        }
        *{margin: 0; padding: 0;}
        body {
            background: #008fee;
            font-size: 14px;
            color: var(--color-text);
            font-family:  -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            overflow-y: auto;
            overflow-x: hidden;
        }

        #main {
            width: 500px;
            margin: 0 auto;
            background: var(--color-background);
        }

        .guide-header {
            margin-bottom: 5px;
            margin-top: 15px;
            text-align: center;
        }

        .guide {
            font-size: 15px;
            font-weight: 700;
            margin: 5px 20px;
            display: block;
            text-align: center;
        }
        .download-header{
            margin: 5px 20px;
        }
        .download-description{
            display: block;
            margin: 0 20px;
            margin-bottom: 8px;
            font-size: 15px;
        }
        #main table{
            margin: 0 20px;
            width: 460px;
        }
        .button {
            display: block;
            background: var(--color-button);
            border-radius: 6px;
            padding: 8px 0px;
            text-align: center;
            width: 200px;
            margin: 0px auto;
            text-decoration: none;
            color: white;
            font-weight: 500;
            border: none;
            cursor: pointer;
            user-select: none;
        }

        .button:hover {
            background: var(--color-button-hover);
        }

        .button:active {
            background: var(--color-button);
        }

        h1,
        h2,
        .blue-text {
            color: var(--color-blue-text);
        }

        .red-text {
            color: var(--color-red-text);
        }

        .line {
            height: 3px;
            width: 200px;
            margin: 0px auto;
        }

        .blue-line {
            background: var(--color-blue-line);
            width: 300px;
            margin-top: 10px;
        }

        .green-line {
            background: var(--color-green-line);
        }
        @media only screen and (max-width: 1024px) {
            body{
                background: var(--color-background);
            }
            #main {
                width: 700px;
            }
            #main table{
                width: 660px;
            }
        }
        @media only screen and (max-width: 500px) {
            body{
                background: var(--color-background);
            }
            #main {
                width: 100%;
            }
            #main table{
                width: 100%;
                margin: 0;
            }
            .button{
                width: 160px;
            }
        }
    </style>
</head>

<body>

    <table id="main">
        <tr>
            <td>
                <h1 class="guide-header">BẢNG HƯỚNG DẪN</h1>
            </td>
        </tr>
        <tr>
            <td>
                <span class="guide red-text">1. CHỌN HỆ ĐIỀU HÀNH VÀ ẤN BIỂU TƯỢNG BÊN DƯỚI ĐỂ TẢI VỀ MÁY RỒI MỞ LÊN ĐĂNG KÝ TÀI KHOẢN MỚI +
                    ĐĂNG NHẬP MỚI LÀ MỞ THÀNH CÔNG NHÉ</span>
            </td>
        </tr>

        <tr>
            <td>
                <span class="guide blue-text">2. CÁC BẠN PHẢI GIỮ APP ĐỂ ĐƯỢC NHẬN THÊM NHIỀU ƯU ĐÃI KHI CÓ NHỮNG CHƯƠNG TRÌNH SỰ KIỆN MỚI NỮA
                    NHÉ</span>
            </td>
        </tr>
        <tr>
            <td>
                <div class="line green-line"></div>
            </td>
        </tr>
        <tr>
            <td>
                <span class="guide red-text"><span style="font-weight: bolder;color: #a37400;">ĐẶC BIỆT</span>: CÁC BẠN MỞ TÀI KHOẢN NGÂN HÀNG ONLINE LÀ HOÀN TOÀN MIỄN PHÍ NHÉ... CÁC BẠN NÊN LÀM 3APP
                    ĐỂ NHẬN NHIỀU ƯU ĐÃI CÙNG 1 LÚC NHÉ</span>
            </td>
        </tr>
        <tr>
            <td>
                <div class="line green-line"></div>
            </td>
        </tr>
        <tr>
            <td>
                <h2 class="download-header">CAKE BANK</h2>
            </td>
        </tr>
        <tr>
            <td>
                <span class="download-description">
                    Tải về mở lên ấn cake ngay, rồi ấn đăng ký tài khoản mới ở dưới cùng nhé
                </span>
            </td>
        </tr>
        <tr>
            <td>
                <table>
                    <tr>
                        <td>
                            <a class="button">TẢI CAKE ANDROID</a>
                        </td>
                        <td>
                            <a class="button">TẢI CAKE IPHONE</a>
                        </td>
                    </tr>
                </table>
            </td>
        </tr>
        <tr>
            <td>
                <div class="line blue-line"></div>
            </td>
        </tr>
        <tr>
            <td>
                <h2 class="download-header">TNEX BANK</h2>
            </td>
        </tr>
        <tr>
            <td>
                <span class="download-description">
                    Tải về mở lên đăng ký tài khoản TNEX ngay, không được ấn bỏ qua. Ấn bỏ qua là sai nhé
                </span>
            </td>
        </tr>
        <tr>
            <td>
                <table>
                    <tr>
                        <td>
                            <a class="button">TẢI TNEX ANDROID</a>
                        </td>
                        <td>
                            <a class="button">TẢI TNEX IPHONE</a>
                        </td>
                    </tr>
                </table>
            </td>
        </tr>
        <tr>
            <td>
                <div class="line blue-line"></div>
            </td>
        </tr>
        <tr>
            <td>
                <h2 class="download-header">TECHCOMBANK</h2>
            </td>
        </tr>
        <tr>
            <td>
                <span class="download-description">
                    Tải về mở lên đến phần đăng nhập thì ấn mở tài khoản mới ở dưới cùng bên trái nhé
                </span>
            </td>
        </tr>
        <tr>
            <td>
                <table>
                    <tr>
                        <td>
                            <a class="button">TẢI TECH ANDROID</a>
                        </td>
                        <td>
                            <a class="button">TẢI TECH IPHONE</a>
                        </td>
                    </tr>
                </table>
            </td>
        </tr>
        <tr>
            <td>
                <div class="line blue-line"></div>
            </td>
        </tr>
    </table>



</body>

</html>
