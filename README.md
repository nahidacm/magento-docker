# magento-docker
Docker compose for Magento

# Customize

In line #6, change the volume path to adjust your local app directory

In magento installation, see the params carefully and adjust accordingly.

# Install Magento

`bin/magento setup:install \
--base-url=http://magento24.loc/ \
--db-host=172.1.0.4 \
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
--use-rewrites=1
--elasticsearch-host=elasticsearch
`
