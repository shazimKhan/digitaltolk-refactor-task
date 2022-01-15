I choose this one

Code to refactor
=================
1) app/Http/Controllers/BookingController.php
2) app/Repository/BookingRepository.php

I have categorized my code opinion into three parts which is following

Best thing : It has a repository system which is best practice to understand and accesss the then things easily, also it follows the complete oop standard that I liked it

improvements: I have seen mostly we are using Camel case convention in our all code but in some variables declaration we didn't follow this things

Bad Things:avoid unused import and used variables i have seen the in the booking controller and booking Repository which impacting on your performance 

Terrible things:for me, this is terrible while getting request we are getting the different keys with one name in controller method job_id some of the sides we are getting jobid this is not good because this can stick you into an issue, and maybe you will lose 2,3 hours just for finding what is the issue may be you will put the job_id and but you need to get from jobid mostly this issue happening while you working on apis 