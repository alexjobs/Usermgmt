User Management
===============


Plugin Features:-- 

1. Clean code with formatting 
2. Login 
3. Registration 
4. Cookie login/ Remember me functionality 
5. Add/Edit/Delete User By Admin 
6. Add/Edit/Delete Group By Admin 
7. Change Password 
8. Forgot Password 
9. Change User Password by Admin 
10. List of all Users 
11. List of all Groups 
12. Manage site Permissions using Ajax updation, Permission caching functionality for fast checking 
13. User Email Verification 
14. User Profile View 
15. User activation by Admin 
16. Routing long urls to small urls 
17. Recaptcha support in registration 
18. User email verification by admin 
19. User activation/deactivation by admin 
20. All php constants are now in Upper case 
21. Login cookie name now configurable 
22. 2 functions added-isAdmin(), isGuest() 
23. Passwords hashed with salt(password compatiblity for already registered users) 
24. Restriction on User Group deletion if any user is associated with group 
25. User Email Verification link added 
26. Storing Ip address of user on registration 
27. Some bug fixes- error 404 page issue fixed, security issue fixed, cookie deletion on password change, already defined constants fixed 

Some other plugins are dependent on Cakephp Auth component. I have modified Cakephp Auth component to work other plugins with this user management plugin.
Please move Auth_Component/AuthComponent.php to yourapp/app/Controller/Component/ directory.

It is based on Cakephp 2.x User Mgmt Plugin 1.6 Version (Free), which is based on jedt/SparkPlug plugin. 


TODO:--
1. user user relation
2. group levels 
