# TempCas
Article Dataset的下载链接为：https://drive.google.com/drive/folders/1ViEDrlS3A158TbZcf3pQUgost7LTOY6v?usp=sharing

label.txt为数据标签文件；以空格为分隔符，从第一个特征到最后一个数据格式依次为：  
 #Id  文章ID  
 #all_forward	  该文章的总转发量  
 #all_favorite	#该文章的总收藏数  
 #No_	    #第几个时间段。   以文章的发表时间为起点；每30分钟为一个时间段（Time Slot）；  
 #forwardcnt	 #在该时间段内的转发量  
 #favoritecnt    #在该时间段内的收藏数  
 
 其余文件都为数据文件，以空格为分隔符，从第一个特征到最后一个数据格式依次为：  
#Id   文章ID  
#uin   转发此文章的用户ID  
#preuin     促使此转发的先前用户。比如：uin用户从preuin用户的朋友圈转发了这篇文章，等。  
#No_   第几个时间段。   以文章的发表时间为起点；每30分钟为一个时间段（Time Slot）；  
