# kibana ���Ļ�

# �yԇ�h�� �汾7.3.2

���E:
---

### 1. ��kibana.yml �����Zϵ

```sh
$ vim /etc/kibana/kibana.yml

���� i18n.locale: "zh-TW" �����Zϵ

```
### 2. �}�u zh-TW.json ���Y�ϊA ָ��·��
```sh
$ cp zh-TW.json /usr/share/kibana/node_modules/x-pack/plugins/translations/translations/zh-TW.json

or

$ cp zh-TW.json /usr/share/kibana/x-pack/plugins/translations/translations/zh-TW.json
```
### 3. ������kibana
```sh
$ systemctl restart kibana.service
```
### 4. done


---

#### ������@ʾ�����ֲ����_ �������޸� zh-TW.json 
�Ѹ��� ����

| **����ǰ** | **������** |
| ------ |:------:|
| ����   |  �Y��  |
| ����   |  �ь�  |
| ��Ϣ   |  ӍϢ  |
| �@��   |  �@�e  |
| �惦   |  ����  |
| �½�   |  ����  |
| ����   |  ����  |
| ���_   |  �_��  |
| ����   |  ����  |
| ���I   |  Log   |
| �]��   |  ע��  |
| 朽�   |  �B�Y  |
| �˺�   |  �˻`  |
| ���   |  ����  |
| ȫ��   | ȫΞĻ |
| ������   | �l���� |
| �űP   | �ŵ� |
| �ȴ�   | ӛ���w |
| �W�j   | �W· |
| ���}   | �֏� |
| ����   | Ҏ�t |
| �}�u   | �}�u |
| ���N��   | ���N�� |
| �ρK   | �ρ� |
| ʾ��   | ���� |
| ����   | ���� |
| �՚v   | �՚v |
| ������   | �ŷ��� |
| ��ӡ   | ��ӡ |
| ����   | ���N |

