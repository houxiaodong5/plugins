    
   #使用lfs上传大文件至github

### 1.安装
    git lfs install
    
### 2.说明想对哪个文件用Git LFS   
    git lfs track "aa.zip"    
    git add .gitattributes
    git commit -m "track aa.zip files using Git LFS"
    
### 3.上传文件命令（如常）   
    git add a.psd
    git commit -m "add psd" 
      
### 4.确认下以上操作成功（如果成功，则能看到输出）
    git lfs ls-files 
       
### 5.push
    git push origin master    

   
   
相关资料链接：
* [上传大文件](https://blog.csdn.net/u_7890/article/details/103861062)
* [Markdown编写](https://www.cnblogs.com/liugang-vip/p/6337580.html)


    
             
