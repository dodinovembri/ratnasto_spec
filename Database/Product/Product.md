# Product
```sql
CREATE TABLE product(
	id VARCHAR(36) NOT NULL,
	status TINYINT NOT NULL,
	sort INT NULL,
	created_at datetime NOT NULL,
	updated_at datetime NULL,
	creator_id VARCHAR(36) NULL,
	modifier_id VARCHAR(36) NULL,
	product_code VARCHAR(36) NOT NULL,
	product_name VARCHAR(256) NOT NULL,
	description TEXT NULL,
	PRIMARY KEY (id)
)
```