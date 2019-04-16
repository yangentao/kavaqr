使用zxing扫描二维码, 或生成二维码
-----
1. 扫描二维码   
`val qrText :String? = QRImage.scan(File("/Users/entaoyang/a.png"))`   
`println(qrText)`   

2. 生成二维码   
`val q = QRImage("hello kotlin")`   
`//q.icon(File("app icon file"))`   
`q.makeToFile(File("File To Save"))`   

