![](c68cba970fa849bcab745bdffd2de0bc.png)

## 템플릿 저장
```javascript
contentPane.parameterEl.getWidgetByName("p1").setValue("9999");
window.contentPane.refreshAllSheets();
contentPane.exportReportToExcel('simple');
```


## Excel 불러오기
```javascript
contentPane.parameterEl.getWidgetByName("p1").setValue("9999");
window.contentPane.refreshAllSheets();
contentPane.importExcel();
```


## 데이터 삭제 
```javascript
FR.showIframeDialog({        
	url: FR.cjkEncode(FR.servletURL + "?viewlet=DELETE_RAWDATA.cpt&op=write&tbl="+ tbl +"&fld="+ fld + "&val="+val ),
	title: "삭제",
	type: "POST",
	width: 400,
	height: 180        
});
```


## Loading End
```
$('.parameter-container-collapseimg-up').trigger("click");
$('.parameter-container-collapseimg-up').hide(); 
```
