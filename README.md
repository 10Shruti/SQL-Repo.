## Codecademy Learners Mockup Data 

### Project Goals 
Use knowledge of SQL and analyze some mockup Codecademy learners data.

### Dataset Description
The dataset consists of two tables: **_users_**  and **_progress_**.


#### **users table:**  

`user_id` : Unique identifier for each user (PK).   
`email_domain` : Domain of the user's email address.     
`country` : Country of the user.   
`postal` : Postal code of the user's location.  
`mobile_app` : Indicates whether theuser is using the mobile app.  
`sign_up_at` : Timestamp of user sign-up. 

#### **progress table:**   

`user_id` : Unique identifier for each user(FK).  
`learn_cpp` : Indicates progress in learning cpp.  
`learn_sql` : Indicates progress in learning Sql.  
`learn_html` : Indicates progress in learning html.  
`learn_javascript` : Indicates progress in learning Js.   
`learn_java` : Indicates progress in learning java.  
