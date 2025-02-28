# CMSLoseWeight  

## 考試前虛擬機磁碟狀況  

    
## 剛考完試虛擬機磁碟狀況  
![image](https://github.com/user-attachments/assets/0aa86cd1-36ba-4af5-acda-ae136090b392)

## 刪除單一使用者繳交紀錄  
```  
sudo cmsRemoveSubmissions -c 8 -u S01  
``` 
![image](https://github.com/user-attachments/assets/c3cfa183-0781-468e-ada3-e0bf263de8d6)  
## 批量刪除(但是需要一個一個案Y確定)  
```
for i in $(seq -w 1 75); do
  sudo cmsRemoveSubmissions -c 8 -u S$i
done

``` 
![image](https://github.com/user-attachments/assets/c0158a8d-1f17-43fd-8908-6cd4d5f149c8)

