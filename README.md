# spring security + jwt
Project đơn giản về đăng ký, đăng nhập sử dụng spring security + jwt

# kết nối cơ sở dữ liệu mysql (username với password mysql của bạn)
spring.datasource.url=jdbc:mysql://localhost:3306/<tên database>?useSSL=false
spring.datasource.username=<username>
spring.datasource.password=<password>
spring.jpa.generate-ddl=true
  
# insert role
INSERT INTO roles(name) VALUES('ROLE_USER');
INSERT INTO roles(name) VALUES('ROLE_ADMIN');

# swagger-ui
http://localhost:8080/swagger-ui.html#/
