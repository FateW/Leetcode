Question:

The Hamming distance between two integers is the number of positions at which the corresponding bits are different.
Given two integers x and y, calculate the Hamming distance.
�������ֵĶ�Ӧ����ȡֵ��ͬ�ı�������Ϊ���������ֵĺ������롣
�������£�10101��00110�ӵ�һλ��ʼ�����е�һλ�����ġ�����λ��ͬ����������Ϊ3��

˼·��
Ϊ�˽��������⣬��Ҫ�������裺
1.��������������ת��Ϊ������
2.�������밴����λ�ж��Ƿ���ͬ


���ڵ�һ�㣺
python����ת�������������ú��� bin
>>> b = bin(3) 
>>> b
'0b11'
>>> type(b) #��ȡb������
<class 'str'>

���ڵڶ��㣺
python�������ַ�������Ƭ���ߣ�
a[i-1:i] = b[i-1:i] ������   ȡ���� i-1 ���ַ���b�ĵ� i-1 ���ַ� �Ƚϣ���ͬ��count +1


