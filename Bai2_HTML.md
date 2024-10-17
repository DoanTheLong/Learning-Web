## HTML   
 
##### 1. Khái niệm:  
* HTML: Ngôn ngữ đánh dấu siêu văn bản
* Tag: Câu lệnh của HTML sẽ có dạng :
    * <> </> (ví dụ: ```<h1> văn bản </h1>```)
    * </> (ví dụ: ```<br>```)
    * ```<!-- Ghi chú--->```
##### 2. Cấu trúc cơ bản của HTML:
```
<!DOCTYPE html>
    <html> 
        <head>
            <metameta>
            <title> Tiêu đề trang web </title>
        </head>

        <body>
            ...Phần thân viết ở đây...
        </body>
    </html>
```
##### 3. Một vài tag thông dụng:
* ```<html> </html>``` : thẻ mở đầu của văn bản HTML  
* ```<head> </head>``` : chứa thông tin của tệp  
* ```<meta>```: mô tả nội dung trang  
* ```<link>```: nhúng một tập tin vào tệp  
* ```<script> </script>```: nhúng js vào html  
* ```<style> </style>```: bao tập tin css  
* ```<body> </body>```: chứa nội dung của trang web  
* ```<span> </span>```: chứa nội dung
* ```<p> </p>```: chứa đoạn văn
* ```<a> </a>```: tạo đường link
* ```<img>```: nhúng hình ảnh vào tệp
* ```<form method="" action=""></>```: kết hợp với 1 vài thẻ khác để tạo ra 1 form nhập liệu
    * ```<legend></legend>```: tiêu đề ô nhập liệu
    * ```<fieldset></fieldset>```: nhóm các ô nhập liệu
    * ```<label></label>```: tiêu đề
    * ```<input type=" "></input>```: ô nhập liệu (có các type như bên dưới)
        * checkbox: ô check box
        * text: ô nhập văn bản
    * Ghi chú: Thêm  
        * ```method="Post" ```: gửi dữ liệu và ẩn địa chỉ api
        * ```method="Get" ```: lấy dữ liệu
        * ```action=" link "```: gửi dữ liệu tới trang nàonào 
* Ghi chú: Coi thêm ở web `W3Schools` 