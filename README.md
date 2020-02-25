
<img src="https://i.ytimg.com/vi/JPED8CG8G2w/maxresdefault.jpg">

# spring security + jwt
Project đơn giản sử dụng spring security + jwt
# Build status
Build status of continus integration i.e. travis, appveyor etc. Ex. -

Build Status Windows Build Status
# Kết nối cơ sở dữ liệu mysql
spring.datasource.url=jdbc:mysql://localhost:3306/<tên database>?useSSL=false
spring.datasource.username=<username>
spring.datasource.password=<password>
spring.jpa.generate-ddl=true
  
# Thêm role
INSERT INTO roles(name) VALUES('ROLE_USER');
INSERT INTO roles(name) VALUES('ROLE_ADMIN');

# Hiển thị API sử dụng swagger-ui
http://localhost:8080/swagger-ui.html#/
