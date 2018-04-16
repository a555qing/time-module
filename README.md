# time-module
Python function time
datetime.datetime.now()
datetime.datetime(2018, 4, 16, 11, 45, 52, 510201)
>>> datetime.datetime.time(datetime.datetime.now())
datetime.time(13, 44, 59, 645061)
>>> datetime.datetime.now().time()
datetime.time(13, 45, 57, 400315)
from datetime import datetime
>>> str(datetime.now())
'2018-04-16 14:55:40.796132'

>>> import time
>>> time.time()
1523862286.237929
>>> time.ctime()
'Mon Apr 16 15:09:42 2018'
>>> time.ctime(1523862286.237929)
'Mon Apr 16 15:04:46 2018'
>>> 

>>> import datetime
>>> datetime.datetime.utcnow()
datetime.datetime(2018, 4, 16, 7, 19, 31, 360563)
>>> print(datetime.datetime.utcnow())
2018-04-16 07:24:36.356263

import datetime;pytz
then = datetime.datetime.now(pytz.utc)
then
datetime.datetime(2018, 4, 16, 9, 42, 5, 37090, tzinfo=<UTC>)
