# ElementTree_CDATA

版本：python3.5 xml.etree.ElementTree
修改ElementTree，支持生成CDATA节点

用法
import ElementTree as ET
root = ET.Element('data')
root.text = ET.CDATA('a string')
print (tostring(root, encoding='utf-8'))
