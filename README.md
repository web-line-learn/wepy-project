# С���������������� wepy ʾ��demo
	WePY�����Vue.js�����ļ��Vue�����﷨���͹������ԣ������֮ǰ��δ�Ӵ���Vue���������Ķ�[Vue�Ĺٷ��ĵ�](https://cn.vuejs.org/v2/guide/)������Ϥ��ظ���

# �ο��ĵ�
- [github](https://github.com/Tencent/wepy)
- [�ٷ��ĵ�] (https://tencent.github.io/wepy/document.html#/)

# ��Ŀ������ʹ��
ȫ�ְ�װ npm install wepy-cli -g
��ʼ��һ����Ŀ wepy init standard my-project
��װ����  npm  install
����ʵʱ���� wepy build --watch

# WePY��Ŀ��Ŀ¼�ṹ
������ dist                   С�������д���Ŀ¼����Ŀ¼��WePY��buildָ���Զ��������ɣ��벻Ҫֱ���޸ĸ�Ŀ¼�µ��ļ���
������ node_modules           
������ src                    �����д��Ŀ¼����Ŀ¼Ϊʹ��WePY��Ŀ���Ŀ¼��
|   ������ components         WePY���Ŀ¼���������������ҳ�棬��������ҳ�������������ã�
|   |   ������ com_a.wpy      �ɸ��õ�WePY���a
|   |   ������ com_b.wpy      �ɸ��õ�WePY���b
|   ������ pages              WePYҳ��Ŀ¼����������ҳ�棩
|   |   ������ index.wpy      indexҳ�棨��build�󣬻���distĿ¼�µ�pagesĿ¼����index.js��index.json��index.wxml��index.wxss�ļ���
|   |   ������ other.wpy      otherҳ�棨��build�󣬻���distĿ¼�µ�pagesĿ¼����other.js��other.json��other.wxml��other.wxss�ļ���
|   ������ app.wpy            С���������ȫ�����ݡ���ʽ���������ӵȣ���build�󣬻���distĿ¼������app.js��app.json��app.wxss�ļ���
������ package.json           ��Ŀ��package����


