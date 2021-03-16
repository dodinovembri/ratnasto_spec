# Product Category
```sql
CREATE TABLE product_category(
	id VARCHAR(36) NOT NULL,
	status TINYINT NOT NULL,
	sort INT NULL,
	created_at DATETIME NOT NULL,
	updated_at DATETIME NULL,
	creator_id VARCHAR(36) NULL,
	modifier_id VARCHAR(36) NULL,
    product_category_code VARCHAR(36) NOT NULL,
	product_category_name VARCHAR(256) NOT NULL,
	description TEXT NULL,
	PRIMARY KEY (id)
)
```