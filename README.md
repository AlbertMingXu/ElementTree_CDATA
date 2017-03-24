
ElementTree_CDATA<br>
版本：python3.5<br>
xml.etree.ElementTree<br>
修改ElementTree，支持生成CDATA节点<br>
<br>
<br>
　用法：<br>
　　　import ElementTree as ET<br>
　　　root = ET.Element('data')<br>
　　　root.text = ET.CDATA('a string')<br>
　　　print (tostring(root, encoding='utf-8'))<br>
