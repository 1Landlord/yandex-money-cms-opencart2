1. 	�������� �����!
2. 	���������� ����� ��������� � ������ ������ ��������.
3. 	���� �� ����������� ��� �� ������� � ��� .htaccess ������
	RewriteRule ^yandexbuy/([^?]*)$ index.php?route=yandexbuy/$1 [L,QSA]
	������� ����� ����� RewriteBase / � ����� RewriteRule ^sitemap.xml$ index.php?route=feed/google_sitemap [L]
	������ ����� ���:
	...........................................................................................................
	RewriteBase /
	RewriteRule ^yandexbuy/([^?]*)$ index.php?route=yandexbuy/$1 [L,QSA]
	RewriteRule ^sitemap.xml$ index.php?route=feed/google_sitemap [L]
	RewriteRule ^googlebase.xml$ index.php?route=feed/google_base [L]
	RewriteRule ^download/(.*) /index.php?route=error/not_found [L]
	...........................................................................................................

4.	������� � ������� � Extension --> feed. ��� ������������� ��� ������ � �����������.
5.	��� ������ ������ ����� ��������� ���������� https.

������ .htaccess ����� ����� � readme.