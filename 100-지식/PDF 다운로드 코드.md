# PDF 다운로드 코드

#100-지식

```
 let jspdf = document.createElement( "script" );

jspdf.onload = function () {

let pdf = new jsPDF();

let elements = document.getElementsByTagName( "img" );

for ( let i in elements) {

let img = elements[i];

if (!/^blob:/.test(img.src)) {

continue ;

}

let canvasElement = document.createElement( 'canvas' );

let con = canvasElement.getContext( "2d" );

canvasElement.width = img.width;

canvasElement.height = img.height;

con.drawImage(img, 0, 0,img.width, img.height);

let imgData = canvasElement.toDataURL( "image/jpeg" , 1.0);

pdf.addImage(imgData, 'JPEG' , 0, 0);

pdf.addPage();

}

pdf.save( "download.pdf" );

};

jspdf.src = 'https://cdnjs.cloudflare.com/ajax/libs/jspdf/1.3.2/jspdf.min.js' ;

document.body.appendChild(jspdf);
```

## 🔗 연결된 카드
- [너드랩](../%EB%B3%B4%EB%93%9C/%EB%84%88%EB%93%9C%EB%9E%A9.md)
