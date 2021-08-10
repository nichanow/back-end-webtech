# Strapi application
(ส่วน fornt-end อยู่ที่ https://github.com/nichanow/front-end-webtech)

"การติดตั้งโปรเจค"
1. git clone https://github.com/nichanow/back-end-webtech.git
2. หลังจาก clone เสร็จแล้วให้พิมพ์คำสั่ง 'npm install'
3. เมื่อ install เสร็จแล้วให้พิมพ์คำสั่งว่า 'npm run develop' จากนั้นทำการล็อคอิน 
username : nichathitra.m@ku.th, password: Strapi12345

"โครงสร้าง strapi"
1. History of points earned tables : เก็บ type, prize, point และมี relation กับ user
2. Points usage history table : เก็บ item, image, points_usage และมี relation กับ user
3. Reward : เก็บ item, points, amounts
4. User : เก็บ username, email, role, password
5. Users_data : เก็บ name, age, gender, total_points, check_date มี relation กับ username, history_of_points_earned_tables, points_usage_history_tables


A quick description of your strapi application
