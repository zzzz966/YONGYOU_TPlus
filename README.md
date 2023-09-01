# YONGYOU_TPlus
畅捷通TPlus poc  
# 漏洞描述  
用友 畅捷通T+ DownloadProxy.aspx文件存在任意文件读取漏洞，攻击者通过漏洞可以获取服务器上的敏感文件  

# 网络测绘

app="畅捷通-TPlus"

# Usage:  
  python3 TPlus.py -h  
  python3 TPlus.py -u http://www.example.com 单个url测试  
  python3 TPlus.py -f url.txt 批量检测  

# 提示  
会在当前目录生成存在漏洞的vulable.txt文件
# 免责声明
由于传播、利用此文所提供的信息而造成的任何直接或者间接的后果及损失，均由使用者本人负责，作者不为此承担任何责任。
