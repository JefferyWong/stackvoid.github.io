---
layout: post
title: ʹ�� Git ���ɱ�׼ Patch
categories: [Tips]
tags: [Website]
---

��������ĳ��̵Ĵ��룬���� Bug �Ľ������Ҫ��ʹ֪ͨ���̣���ʱ�� Patch �ʹ��������ˡ�

�������ҷ����ܽ���ο�������һ����׼��Git����ʶ���Patch��

**1.��ʼ��git����**

ʹ��
 
> git init 

> git add *  //��������ļ�������

> git commit -m "init"  //�ύ�����ļ�������

��������ʼ����ǰ��gitĿ¼�������ǰĿ¼�� .git ���ڣ����������˲��衣

**2.�޸����Code**

�޸���󣬿����� 

> git diff

���鿴���޸�����Щcode���Ա�֤��ȷ�ԡ�

**3.�ύ������**

	git commit --amend  �ύ��Ӧ�޸ģ��������������޸ĵ�˵��
	
	
	git commit -asm   ��дpatch������
	
**4.����patch**

ʹ��

> git format-patch -1 

����patch��

����patch�������� 000*-**.patch

**ʹ��patch**

�õ� patch ��������ֱ�ӵ���ӦĿ¼�£�������  

> git am *.patch  

���ɴ��� patch��


