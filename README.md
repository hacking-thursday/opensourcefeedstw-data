# 說明

此專案提供所有社群活動資訊與相關連結

## 如何新增社群?
#### 若您的社群有意願加入，請參考 *groups.json* 的 *auto_increment* 欄位將以下資訊填妥讓我們知道 : 


1.  **id** :     不重複的流水號數字
> * (請拉到檔案最尾端看目前編號至第幾號，以不重複為原則，將目前編號+1作為您的唯一編號)
            
2.  **links** :  "http://XXXXX/OOOO/"
> * (若有多個網頁連結請參考以下範例編寫)
            
3.  **name** :   "您的社群名稱"

---
 #### *Example :*
 
```Jason
        {
            "id": 100,
            "links": [
                "http://tw.pyladies.com/",
                "https://twitter.com/PyLadiesTW",
                "https://www.facebook.com/groups/pyladies.taiwan/",
                "https://plus.google.com/107864110865512838634",
                "https://groups.google.com/forum/#!forum/pyladies-taiwan",
                "http://www.meetup.com/PyLadiesTW/"
            ],
            "name": "PyLadies Taiwan"
        }

```
