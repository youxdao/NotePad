# NotePad

This is an AndroidStudio rebuild of google SDK sample NotePad

##��չ����
����Ŀ��NotePad����������������չ�����£�\<br>
###1NoteList����ʾ��Ŀ����ʱ����ʾ
###2�ʼǲ�ѯ���������ѯ��
###3�ʼ�����(������ʱ����޸�ʱ��)
##��չ���ܽ���
###1NoteList����ʾ��Ŀ����ʱ����ʾ
��NotePadԭӦ���У��ʼ��б�ֻ��ʾ�˱ʼǵı��⡣���ȣ��ҵ��б���item�Ĳ��֣�noteslist_item.xml��Ҫ�ڱ����·���ʱ����ʾ����Ҫ�ڱ����TextView���ټ�һ��ʱ���TextView��
��������ԭӦ���б�itemֻ��Ҫһ�����⣬���Բ���Ҫ���ϱ�Ĳ��֣�����Ҫ���һ��ʱ��TextView����Ҫ�ѱ���TextView��ʱ��TextView���봹ֱ�����Բ���\<br>
NotePadԭӦ���Ѿ�������ʱ�䣬���ǣ��Ⲣ��������ƽ����������ʱ���ʽ������ʱ�������Ҫ����Щ���ݽ���ת����ʹ���ܿ��Ķ���
��ѡ��ķ���ʱ��ʱ�����Ϊ��ʱ���ʽ���룬�Ķ��ط��ֱ�ΪNotePadProvider�е�insert������NoteEditor�е�updateNote������\<br>

###2�ʼǲ�ѯ���������ѯ��
Ҫ��ӱʼǲ�ѯ���ܣ���Ҫ��Ӧ��������һ����������ڡ��ҵ��˵���xml�ļ���list_options_menu.xml�����һ��������item������ͼ���ð�׿�Դ���ͼ��.\<br>
��case�����д��תactivity����֮ǰҪ��д��������activity���½�һ����ΪNoteSearch��activity����������������Ҳ�Ǳʼ��б����Կ���ģ��NoteList��activity�̳�ListActivity��.\<br>
Ҫ��̬����ʾ�����������Ҫ��SearchView�ı��仯���ü���.��̬������ʵ������Ҫ�Ĳ�����onQueryTextChange�����У���onQueryTextChange���������ǣ���SearchView���ı������仯ʱ��ִ�����д��룬\<br>
��������һ����Ҫ�Ĳ��־���Ҫ����ģ��ƥ��������ϸ�ƥ�䣬����ʹ�����ݿ��ѯ����е�LIKE��%�����ʵ�֣�newTextΪ�������������ݣ�String[] selectionArgs = { "%"+newText+"%" };\<br>
���Ҫ��AndroidManifest.xmlע��NoteSearch��\<br>

###3�ʼ�����(������ʱ����޸�ʱ��)
�ʼ����������˵�򵥣�ֻҪ��Cursor����������任�¾Ϳ����ˡ�������NoteList�˵�switch�����case��\<br>

