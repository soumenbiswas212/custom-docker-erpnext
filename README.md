# custom-docker-erpnext
custom-docker-erpnext
docker build --build-arg=FRAPPE_BRANCH=edge -t frappe/erpnext-nginx:soumen-new nginx
docker build --build-arg=FRAPPE_BRANCH=edge -t frappe/erpnext-worker:soumen-new worker

docker build -t frappe/erpnext-nginx:soumen-new nginx
docker build -t frappe/erpnext-worker:soumen-new worker
