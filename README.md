# ** Giới thiệu **
Project đơn giản về đăng ký, đăng nhập sử dụng spring security + jwt
<img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3D-HYrUs1ZCLI&psig=AOvVaw0-SlYySKXjgHReELUiybBB&ust=1582711881108000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCPjqybC77OcCFQAAAAAdAAAAABAD">
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
