#git��������



###��Ҫ����
- ���ύ��mommitted�����ļ��Ѿ�����ȫ�ر����ڱ������ݿ�����
- ���޸ģ�modified���޸���ĳ���ļ�������û���ύ����
- ���ݴ棨staged�������޸ĵ��ļ������´��ύʱҪ������嵥��
###����ʹ��Ҫ��������������
```
git config --global user.name "�������"
git config --global user.email xxx@gmail.com
```
###clone��Ŀ�����ڰ�һ��github�ϵ���Ŀclone�����أ������ر�Ϊ���زֿ�(���ͼ��clone of  download��ť���ͻ���ʾclone��ַ��������git �����뼴��)
```
git clone git@github.com:xhrbtk/component.git
cd component    //�л���component�ֿ�
```
![image.png](https://upload-images.jianshu.io/upload_images/8649258-12826b3176a04d08.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
###����ļ�
```
#ͨ�������д����ļ�  Ȼ��������ݣ�����ֱ�Ӵ�component�ļ��У�Ȼ�����ļ�����ֱ������ļ���
//�����ļ�
touch a.md
//���ļ���д��һ���ַ���
echo "hello" >a.md
git status
```
###���ļ������ݴ���
```
#������ǰ�ļ��������е�������ɾ��ȫ�������ݴ���
git add .    
```
###����ļ����ύ
```
#���ݴ����ĸ����ύ�����ؿ�
git commit -am "add file"
gti status
```
###���͵�Զ�ֿ̲�
```
#��һ��ʹ��
git push origin master
#��ʹ�ù�һ��֮��Ϳ���ֱ����
git push
```