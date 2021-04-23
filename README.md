# magento-docker
Docker compose for Magento

# Customize

Keep the `docker-compose.yml` file into project root directory.

1. Run: `docker compose up` from project root.
2. create DB from PhpMyAdmin: http://localhost:8000
3. In magento installation, see the params carefully and adjust accordingly.

# Install Magento

```bash
bin/magento setup:install \
--base-url=http://localhost:8888/ \
--db-host=mysql \
--db-name=magento \
--db-user=root \
--db-password=j \
--admin-firstname=admin \
--admin-lastname=admin \
--admin-email=admin@admin.com \
--admin-user=admin \
--admin-password=admin123 \
--language=en_US \
--currency=USD \
--timezone=America/Chicago \
--use-rewrites=1 \
--elasticsearch-host=elasticsearch
```
