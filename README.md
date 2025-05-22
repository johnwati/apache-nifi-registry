# apache-nifi-registry

curl -v -F template=@KCB_CUSTOMER_INTEG_V10-finale.xml \
  -F "name=MyTemplate" \
  https://localhost:9443/nifi-api/process-groups/root/templates/upload
