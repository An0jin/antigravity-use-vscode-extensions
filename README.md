# extensionsGallery을 찾는다
## extensionsGallery의 내용을 아래와 같이 바꾼다
### 파일위치
* 리눅스(debian 기준)
  * /opt/Antigravity IDE/resources/app/product.json
* 윈도우
  * C:\Users(사용자)\사용자명\AppData\Local\Programs\Antigravity IDE\resources\app\product.json
``` json
"extensionsGallery": {
		"serviceUrl": "https://marketplace.visualstudio.com/_apis/public/gallery",
		"cacheUrl": "https://vscode.blob.core.windows.net/gallery/index",
		"itemUrl": "https://marketplace.visualstudio.com/items",
		"controlUrl": "",
		"recommendationsUrl": ""
	}
```
