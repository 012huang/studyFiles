## Html
1��<q></q>���ı����ã��Զ���˫���ţ����������á�
2��<blockquote></blockquote>���ı����ã��Զ�����������
3��<br><br />Ϊ���У�&nbsp;Ϊ�ո�<hr />Ϊˮƽ���ߡ�
4��<address></address>��ַ��
5��<code></code>������Ϊһ�д���ʱ����Ϳ���ʹ��<code>��ǩ�ˡ�
6��<pre></pre>���Դ���Σ����С�
7��<table summary="������ı�">��<caption>�����ı�</caption>
8��<a href="Ŀ����ַ" target="_blank">click here!</a>�½�����������д����ӡ�
9��<a href=��mailto: yy@qq.com?cc=xx@qq.com&bcc=zz@qq.com&subject=����&body=���ݡ�>����</a>
����һ�������ã�������߲�����&������cc�����͡�Bcc���ܳ��͡�Subject�����⡣Body�����ݣ�
10��<img src=�� �� alt=�� �� title=�� ��> srcΪͼƬ��ַ��altΪ���ز��ɹ�ʱ�������ı���titleΪͼ��ɼ�ʱͼ���������
11��<form   method="���ͷ�ʽ"   action="�������ļ�">
12��<textarea  rows="����" cols="����">�ı�</textarea>�ı���
13��<input type="radio/checkbox" value="ֵ" name="����"   checked="checked"/>��ѡ�򡢸�ѡ��ͬһ��ĵ�ѡ��ť��name ȡֵһ��Ҫһ�£�����ͬһ��ĵ�ѡ��ť�ſ����𵽵�ѡ�����á�
14��<select><option value=����������ύ��ֵ�� selected=��selected��>��ʾ��ֵ</option></select>������multiple="multiple"ʹ�������б����ж�ѡ��
15��<input type="submit" value="ȷ��"  />��ť��<input type="reset" value="����"  />���ð�ť��
16��<label for="�ؼ�id����">���û�����ѡ�и�label��ǩʱ��������ͻ��Զ�������ת���ͱ�ǩ��صı��ؼ��ϡ�
ע�⣺��ǩ�� for �����е�ֵӦ������ؿؼ��� id ����ֵһ��Ҫ��ͬ��

## CSS
1��>������Ԫ�صĵ�һ��������ո�������Ԫ�ص����к����>�ʺϰ�����ʽʱ�����õ�һ�������ʽ��
2��α��ѡ���a:hover{color:red;}��껬����״̬��
3����Щ����������ҪΪĳЩ��ʽ���þ������Ȩֵ����ô�죿��ʱ�����ǿ���ʹ��!important�������
p{color:red!important;}
p{color:green;}
4�������Ű�
����p{font-family:"Microsoft Yahei";}����һ����ҳϲ�����á�΢���źڡ�
���ִ���p{font-weight:bold;}
����б��p{font-style:italic;}
�����»���p{text-decoration:underline;}
����ɾ����p{text-decoration:line-through;}
��������p{text-indent:2em;} 2em����˼�������ֵ�2����С��
�����м��p{line-height:1.5em;}
���ļ��h1{letter-spacing:50px;} ��ĸ���h1{word-spacing:50px;}
5�������Ű�
����h1{text-align:center;} {text-align:left;} {text-align:right;}
6��Ԫ�ط���
���õĿ�״Ԫ���У�
<div>��<p>��<h1>...<h6>��<ol>��<ul>��<dl>��<table>��<address>��<blockquote> ��<form>
���õ�����Ԫ���У�
<a>��<span>��<br>��<i>��<em>��<strong>��<label>��<q>��<var>��<cite>��<code>
���õ�������״Ԫ���У�
<img>��<input>
7��Ԫ�ط���--�鼶Ԫ��
ÿ���鼶Ԫ�ض����µ�һ�п�ʼ����������Ԫ��Ҳ����һ�С�
Ԫ�صĸ߶ȡ���ȡ��и��Լ����͵ױ߾඼�����á�
Ԫ�ؿ���ڲ����õ�����£���������������100%���͸�Ԫ�صĿ��һ�£��������趨һ����ȡ�
������Ԫ��aת��Ϊ��״Ԫ��a{display:block;}
8��Ԫ�ط���--����Ԫ��
������Ԫ�ض���һ���ϣ�
Ԫ�صĸ߶ȡ���ȼ������͵ײ��߾಻�����ã�
Ԫ�صĿ�Ⱦ��������������ֻ�ͼƬ�Ŀ�ȣ����ɸı䡣
����״Ԫ������Ϊ����Ԫ��
div{display:inline;}
9��Ԫ�ط���--������״Ԫ��
����ͬʱ�߱�����Ԫ�ء���״Ԫ�ص��ص㣬����display:inline-block���ǽ�Ԫ������Ϊ������״Ԫ�ء�
10������ģ�͡��鼶��ǩ
���Ӻ����ݼ�϶��padding,�ڱ߾�,���ĸ�����top,right,bottom,left
���Ӻͺ���֮��ü�϶��margin,��߾�,���ĸ�����top,right,bottom,left
�߿�border���ĸ�����top,right,bottom,left
border-style���߿���ʽ��������ʽ�У�dashed�����ߣ�| dotted�����ߣ�| solid��ʵ�ߣ���
border-color���߿���ɫ���е���ɫ������Ϊʮ��������ɫ����:border-color:#888;//ǰ��ľ��Ų�Ҫ������
border-width���߿��ȣ��еĿ��Ҳ��������Ϊ��thin | medium | thick�������Ǻܳ��ã�������������أ�px����
��дdiv{border:2px  solid  red;}
11��CSS����ģ��
����ģ�����ģ��һ������ CSS ������� ����ĵĸ��
����ҳ�У�Ԫ�������ֲ���ģ�ͣ�
1)����ģ�ͣ�Flow��
2)����ģ�� (Float)
3)��ģ�ͣ�Layer��
CSS������һ�鶨λ��positioning��������֧�ֲ㲼��ģ�͡�
��ģ����������ʽ��
1)���Զ�λ(position: absolute)
2)��Զ�λ(position: relative)
3)�̶���λ(position: fixed)
���Զ�λ������ڸ�������ʵ�ƶ������û�и����󣬸�������body
.a{position:absolute;top:50%;left:50%;transform:translate(-50%,-50%)}
��Զ�λ������ڸ�Ԫ��ԭʼλ�ñ��ˣ���ƫ��ǰ��λ�û��������������ǲ���ǰ���divû��ƫ��ǰ��λ�á�
�̶���λ��fixed����ʾ�̶���λ����absolute��λ�������ƣ�����������ƶ�����������ͼ����Ļ�ڵ���ҳ���ڣ������������ĵ�����Ӱ�졣����̶���ǰ���ڵ�С���

12����ģ�ͼ�д
margin:10px 15px 12px 14px;/*������Ϊ10px��������Ϊ15px��������Ϊ12px��������Ϊ14px*/
1�����top��right��bottom��left��ֵ��ͬ����������룺
margin:10px 10px 10px 10px;
����дΪ��
margin:10px;
2�����top��bottomֵ��ͬ��left�� right��ֵ��ͬ����������룺
margin:10px 20px 10px 20px;
����дΪ��
margin:10px 20px;
3�����left��right��ֵ��ͬ����������룺
margin:10px 20px 30px 20px;
����дΪ��
margin:10px 20px 30px;
ע�⣺padding��border����д������margin��һ�µġ�
13��������д
body{
    font-style:italic;
    font-variant:small-caps; 
    font-weight:bold; 
    font-size:12px; 
    line-height:1.5em; 
    font-family:"����",sans-serif;
}
��ô���еĴ�����ʵ������дΪһ�䣺
body{
    font:italic  small-caps  bold  12px/1.5em  "����",sans-serif;
}
1��ʹ����һ��д��ʽ������Ҫָ�� font-size �� font-family ���ԣ�����������(�� font-weight��font-style��font-varient��line-height)��δָ�����Զ�ʹ��Ĭ��ֵ��
2������дʱ font-size �� line-height �м�Ҫ���롰/��б����
һ���������Ϊ����������վ��Ӣ�Ļ��ǱȽ��ٵģ�����������д����Ƚϳ��ã�
body{
    font:12px/1.5em  "����",sans-serif;
}
ֻ�����ֺš��м�ࡢ�������塢Ӣ���������á�
14������ֵ
px�����أ���em��% �ٷֱȣ�Ҫע����ʵ�����ֵ�λ������Ե�λ��
����ָ������ʾ���ϵ�С��
em���Ǳ�Ԫ�ظ�������� font-size ֵ�����Ԫ�ص� font-size Ϊ 14px ����ô 1em = 14px����� font-size Ϊ 18px����ô 1em = 18px��
p{font-size:12px;line-height:130%}�����иߣ��м�ࣩΪ�����130%��12 * 1.3 = 15.6px����
15������
ˮƽ���У�����Ԫ��ˮƽ����text-align��center��
��������Ԫ��Ϊ��״Ԫ��ʱ�� text-align��center �Ͳ��������ˡ���ʱҲ����������������״Ԫ�غͲ������״Ԫ�ء�
���㶨��Ϳ�״����������Ԫ���ǿ���ͨ�����á�����margin��ֵΪ��auto����ʵ�־��еġ�
������ȵĿ�״Ԫ�������ַ������У������ַ���Ŀǰʹ�õĶ��ȶࣩ��
���� table ��ǩ
���� display;inline ����
���� position:relative �� left:50%;
��ֱ����-��Ԫ�ظ߶�ȷ���ĵ����ı�
���ø�Ԫ�ص� height �� line-height �߶�һ����ʵ��
��ֱ����-��Ԫ�ظ߶�ȷ���Ķ����ı�
1��	vertical-align�Ǵ�ֱ�������ԣ���ֻ�и�Ԫ��Ϊtr��td��ʱ������á���˿�����table���������ı���ʵ�ִ�ֱ���С�ע�⣺td ��ǩĬ������¾�Ĭ�������� vertical-align Ϊ middle��
2��	ͨ����ʩdisplay:table-cell; ���� vertical-align ���ԣ���ע�� IE6��7 ����֧�������ʽ��
display:table-cell;/*IE8���ϼ�Chrome��Firefox*/
vertical-align:middle;/*IE8���ϼ�Chrome��Firefox*/
